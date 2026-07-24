# Contributing

Contributions are welcome through issues or pull requests. A paper is merged only when its identity, scope, metadata, and technical fields can be reviewed from reliable sources.

## First Principle: One Work, One Record

The unit of this catalog is a **scholarly work**, not a URL or a particular copy of a manuscript.

- A preprint and its published version are one record when they are versions of the same work.
- A substantially different follow-up paper is a separate record even if the title or codebase is similar.
- Prefer the published metadata when a publication exists, while retaining useful arXiv, OpenReview, code, and project links.

Use **DOI → arXiv → OpenReview → official paper page** as the link preference. Filenames are never identifiers.

## Scope

In scope are classical packing foundations used by the field, 1D/2D/3D geometric packing, container loading and palletization, online/offline/dynamic variants, learning-based methods, irregular or deformable objects, physical stability, perception, and robotic execution.

Bin picking, pose estimation, manipulation, or stability prediction without a packing policy may remain only when it is already part of the reviewed corpus and is explicitly marked `Scope-adjacent ... | Not a packing policy | ...`.

## Evidence Rules

Use this evidence order:

1. Paper title page and full text.
2. Official DOI landing page, publisher record, arXiv abstract page, or OpenReview record.
3. Official code/project repository.
4. Existing README text only as a discovery hint.

PDF embedded metadata is not authoritative. It is often truncated, inherited from a template, or describes a different manuscript. If text extraction fails, inspect the title page visually or use the official identifier page. Do not infer technical fields from a filename alone.

For each claim, distinguish:

- **Not applicable (reason):** the field is structurally irrelevant, for example `Not applicable (non-RL method)`.
- **Not reported:** the field is relevant, but a full-text search found no reportable value.
- **Unverified:** temporary review state only; it must not be merged into the final README.
- Bare `N/A` is forbidden because it does not distinguish these cases.

## Required Record Fields

Each README entry must include the following fields.

### Identity and citation

- `title`: exact canonical title from the title page/publisher record.
- `authors`: complete author list in paper order.
- `year`: year of the cited version; use the publication year when a published version is canonical.
- `venue`: full journal/conference name, or an explicit preprint venue.
- DOI, arXiv, OpenReview, and official code/project resources when available.

### Keywords

Use a small controlled set that describes the paper itself, not methods mentioned only as baselines: problem dimension, online/offline/dynamic setting, geometry, core method family, robotics, perception, and stability.

### Task

Exactly three parts separated by ` | `:

`Mode | Packing scope/target | Item geometry or attributes`

Examples:

- `Online | Single-container sequential 3D packing | Rigid cuboids`
- `Fully dynamic | Multi-bin packing with arrivals, departures, and repacking | Scalar-sized items`
- `Offline/sequential | Vessel-bay container stowage, not packing inside a container | ISO containers with weight and port-of-discharge attributes`

Do not collapse multi-bin packing, single-container loading, strip packing, knapsack, pallet loading, and vessel-bay stowage into one generic label.

### RL formulation

For an RL method, use exactly:

`State: ... | Action: ... | Reward: ...`

State must name the actual observation/representation, action must identify the learned decisions and degrees of freedom, and reward must describe the optimized signal. A method that uses supervised learning, numerical optimization, or Monte Carlo tree search is not RL merely because the paper discusses RL baselines.

For a non-RL paper use an explicit reason, for example `Not applicable (exact branch-and-bound method)`.

### Physics and vision

Exactly:

`Observation: ... | Stability: ... | Execution: ...`

Separate known geometry from RGB-D/point clouds/height maps, geometric non-overlap from physical support or dynamics, and planning from real robot/gripper/reachability constraints.

### Algorithm and data

Exactly:

`Method: ... | Data: ... | Objective: ...`

Name the paper's proposed method, the true evaluation source, and the actual optimization objective. Do not label generated instances as industrial data or copy baseline methods into the proposed-method field.

## Ordering and Badges

- Papers are ordered chronologically inside each section; ties use canonical title.
- Link to DOI when available, otherwise arXiv abstract, OpenReview, or the best official landing page.
- Link to arXiv abstracts rather than direct PDFs.
- Preserve official code, website, and blog links.
- Surveys and benchmarks with a DOI receive a citation badge.

## Worked Examples

### Non-RL exact method

```text
Title: Algorithm 864: General and robot-packable variants of the three-dimensional bin packing problem
Task: Offline | Multi-bin 3D-BPP with general and robot-packable variants | Rigid cuboids
RL: Not applicable (exact branch-and-bound method)
Physics & Vision: Observation: known item/bin geometry | Stability: geometric non-overlap only | Execution: optional robot-packability constraints
Algo & Data: Method: exact branch-and-bound algorithms and reference software | Data: generated and literature benchmark instances | Objective: minimize bin count subject to optional robot-packability
```

### RL packing method

```text
Title: Learning Efficient Online 3D Bin Packing on Packing Configuration Trees
Task: Online | Single-container sequential 3D packing | Rigid cuboids
RL: State: packing-configuration tree for the current bin and incoming item | Action: choose a feasible tree node / placement | Reward: incremental packed volume and terminal utilization
Physics & Vision: Observation: known item/bin geometry | Stability: explicit stability checks | Execution: no robotic execution
Algo & Data: Method: packing-configuration-tree reinforcement learning | Data: generated streams and constrained benchmark variants | Objective: maximize utilization under practical constraints
```

### Survey

```text
Title: An improved typology of cutting and packing problems
Task: Survey | Problem-family survey | Cutting-and-packing problem taxonomy
RL: Not applicable (non-RL method)
```

## Review Checklist

Before merging a paper:

1. Read the paper and confirm that its title page matches the proposed record.
2. Resolve DOI/arXiv/OpenReview and compare title, full author list, year, and venue.
3. Search the full text for problem definition, state/action/reward, observation, stability, execution, datasets, and objective.
4. Check for title variants, preprints, and publisher versions already represented in the catalog.
5. Confirm the section and chronological position.
6. Verify that no existing record is duplicated and that no field uses an unexplained placeholder.

A contribution is complete only when another reviewer can trace every field to the paper or an official metadata page.
