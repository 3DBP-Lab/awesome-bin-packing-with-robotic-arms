<div align="center">

# 📦 Awesome Bin Packing with Robotic Arms 🦾

A reviewed catalog of geometric bin packing, learning-based packing, physical stability, and robotic execution.

</div>

![cover](cover_pic.png)

## Overview

- [Aim of the project](#aim-of-the-project)
- [Investigation scope](#investigation-scope)
- [Surveys](#surveys-of-bin-packing-with-robotic-arms)
- [Benchmarks](#benchmarks-of-bin-packing-with-robotic-arms)
- [Algorithms and methods](#algorithms-and-methods)
- [Contributing](CONTRIBUTE.md)

## Aim of the Project

Bin packing is a core cost and feasibility problem in logistics. Robotic execution adds perception error, physical stability, reachability, collision avoidance, and real-time decision constraints that do not appear in a purely geometric formulation.

This project provides a single, evidence-backed index for researchers and practitioners and tracks classical foundations, modern optimization and learning methods, and systems that execute packing with robotic arms.

## Investigation Scope

The catalog includes 1D/2D/3D foundations when they directly define the methods or evaluation used by robotic packing research; online and offline packing; regular, irregular, and deformable items; stability and physics; perception; and robot execution. Scope-adjacent perception or manipulation papers are retained only when present in the local corpus and are explicitly marked as not proposing a packing policy.

## Surveys of Bin Packing with Robotic Arms

- ❤️ **Two-dimensional packing problems: A survey** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fs0377-2217%2802%2900123-6-blue.svg)](https://doi.org/10.1016/s0377-2217(02)00123-6) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1016%2Fs0377-2217%2802%2900123-6)](https://scholar.google.com/scholar?q=Two-dimensional%20packing%20problems%3A%20A%20survey)
  > 👨‍🔬 **Authors:** Andrea Lodi; Silvano Martello; Michele Monaci | 📅 **Year:** 2002 | 🏢 **Venue:** European Journal of Operational Research <br>
  > 🔑 **Keywords:** Survey, 2D packing, Cuboids, Approximation algorithms <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Problem-family survey \| 2D bin/strip packing <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: Varies across reviewed studies \| Stability: Reviewed when in scope \| Execution: No single robotic setup <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: systematic literature synthesis/taxonomy, approximation algorithms, heuristic search \| Data: reviewed literature and reported benchmarks \| Objective: maximize utilization/minimize waste, minimize packing height <br>

- ❤️ **Three Dimensional Bin-Packing Issues and Solutions** [![Paper](https://img.shields.io/badge/Paper-Link-4682B4.svg)](https://www.micsymposium.org/mics_2004/Sweep.pdf)
  > 👨‍🔬 **Authors:** Sweep, Seth | 📅 **Year:** 2004 | 🏢 **Venue:** MICS <br>
  > 🔑 **Keywords:** Survey, 3D bin packing, Approximation algorithms, Heuristics <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Offline 3D bin-packing formulations and solution approaches \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: tutorial review and comparative synthesis \| Data: published examples and benchmark instances \| Objective: characterize formulations, bounds, and solution quality <br>

- ❤️ **An improved typology of cutting and packing problems** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.ejor.2005.12.047-blue.svg)](https://doi.org/10.1016/j.ejor.2005.12.047) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1016%2Fj.ejor.2005.12.047)](https://scholar.google.com/scholar?q=An%20improved%20typology%20of%20cutting%20and%20packing%20problems)
  > 👨‍🔬 **Authors:** Gerhard Wäscher; Heike Haußner; Holger Schumann | 📅 **Year:** 2007 | 🏢 **Venue:** European Journal of Operational Research <br>
  > 🔑 **Keywords:** Survey <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Problem-family survey \| Cutting-and-packing problem taxonomy <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: Varies across reviewed studies \| Stability: Reviewed when in scope \| Execution: No single robotic setup <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: systematic literature synthesis/taxonomy \| Data: reviewed literature and reported benchmarks \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Bin Packing Approximation Algorithms: Survey and Classification** [![DOI](https://img.shields.io/badge/DOI-10.1007%2F978-1-4419-7997-1_35-blue.svg)](https://doi.org/10.1007/978-1-4419-7997-1_35) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1007%2F978-1-4419-7997-1_35)](https://scholar.google.com/scholar?q=Bin%20Packing%20Approximation%20Algorithms%3A%20Survey%20and%20Classification)
  > 👨‍🔬 **Authors:** Edward G. Coffman; János Csirik; Gábor Galambos; Silvano Martello; Daniele Vigo | 📅 **Year:** 2013 | 🏢 **Venue:** Handbook of Combinatorial Optimization <br>
  > 🔑 **Keywords:** Survey, Online packing, Offline packing, Approximation algorithms <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Online and offline \| Cutting-and-packing problem taxonomy <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: Varies across reviewed studies \| Stability: Reviewed when in scope \| Execution: No single robotic setup <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: systematic literature synthesis/taxonomy, approximation algorithms \| Data: reviewed literature and reported benchmarks \| Objective: minimize bin count <br>

- ❤️ **A comparative review of 3D container loading algorithms** [![DOI](https://img.shields.io/badge/DOI-10.1111%2Fitor.12094-blue.svg)](https://doi.org/10.1111/itor.12094) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1111%2Fitor.12094)](https://scholar.google.com/scholar?q=A%20comparative%20review%20of%203D%20container%20loading%20algorithms)
  > 👨‍🔬 **Authors:** Xiaozhou Zhao; Julia A. Bennell; Tolga Bektaş; Kath Dowsland | 📅 **Year:** 2016 | 🏢 **Venue:** International Transactions in Operational Research <br>
  > 🔑 **Keywords:** Survey, 3D bin packing, Container loading <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Problem-family survey \| 3D container loading <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: Varies across reviewed studies \| Stability: Reviewed when in scope \| Execution: No single robotic setup <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: systematic literature synthesis/taxonomy \| Data: reviewed literature and reported benchmarks \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Bin packing and cutting stock problems: Mathematical models and exact algorithms** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.ejor.2016.04.030-blue.svg)](https://doi.org/10.1016/j.ejor.2016.04.030) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1016%2Fj.ejor.2016.04.030)](https://scholar.google.com/scholar?q=Bin%20packing%20and%20cutting%20stock%20problems%3A%20Mathematical%20models%20and%20exact%20algorithms)
  > 👨‍🔬 **Authors:** Maxence Delorme; Manuel Iori; Silvano Martello | 📅 **Year:** 2016 | 🏢 **Venue:** European Journal of Operational Research <br>
  > 🔑 **Keywords:** Survey, 1D bin packing, Cutting stock, Mathematical programming, Exact algorithms <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| One-dimensional bin packing and cutting-stock formulations \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: formulation taxonomy and review of exact algorithms \| Data: published models and benchmark families \| Objective: compare formulations, bounds, and exact solution methods <br>

- ❤️ **Approximation and online algorithms for multidimensional bin packing: A survey** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cosrev.2016.12.001-blue.svg)](https://doi.org/10.1016/j.cosrev.2016.12.001) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1016%2Fj.cosrev.2016.12.001)](https://scholar.google.com/scholar?q=Approximation%20and%20online%20algorithms%20for%20multidimensional%20bin%20packing%3A%20A%20survey)
  > 👨‍🔬 **Authors:** Henrik I. Christensen; Arindam Khan; Sebastian Pokutta; Prasad Tetali | 📅 **Year:** 2017 | 🏢 **Venue:** Computer Science Review <br>
  > 🔑 **Keywords:** Survey, Multi-dimensional packing, Online packing, Approximation algorithms <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Online and offline \| Multi-dimensional bin packing <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: Varies across reviewed studies \| Stability: Reviewed when in scope \| Execution: No single robotic setup <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: systematic literature synthesis/taxonomy \| Data: reviewed literature and reported benchmarks \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Cargo Stability in the Container Loading Problem - State-of-the-Art and Future Research Directions** [![DOI](https://img.shields.io/badge/DOI-10.1007%2F978-3-319-71583-4_23-blue.svg)](https://doi.org/10.1007/978-3-319-71583-4_23) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1007%2F978-3-319-71583-4_23)](https://scholar.google.com/scholar?q=Cargo%20Stability%20in%20the%20Container%20Loading%20Problem%20-%20State-of-the-Art%20and%20Future%20Research%20Directions)
  > 👨‍🔬 **Authors:** António G. Ramos; José Fernando Oliveira | 📅 **Year:** 2018 | 🏢 **Venue:** Springer Proceedings in Mathematics & Statistics <br>
  > 🔑 **Keywords:** Survey, Dynamic packing, Container loading, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Problem-family survey \| 3D container loading <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: Varies across reviewed studies \| Stability: Reviewed when in scope \| Execution: No single robotic setup <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: systematic literature synthesis/taxonomy \| Data: reviewed literature and reported benchmarks \| Objective: maintain stability <br>

- ❤️ **On-line three-dimensional packing problems: A review of off-line and on-line solution approaches** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cie.2022.108122-blue.svg)](https://doi.org/10.1016/j.cie.2022.108122) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1016%2Fj.cie.2022.108122)](https://scholar.google.com/scholar?q=On-line%20three-dimensional%20packing%20problems%3A%20A%20review%20of%20off-line%20and%20on-line%20solution%20approaches)
  > 👨‍🔬 **Authors:** Sara Ali; António Galrão Ramos; Maria Antónia Carravilla; José Fernando Oliveira | 📅 **Year:** 2022 | 🏢 **Venue:** Computers & Industrial Engineering <br>
  > 🔑 **Keywords:** Survey, 3D bin packing, Online packing, Offline packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Online and offline \| Cutting-and-packing problem taxonomy <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: Varies across reviewed studies \| Stability: Reviewed when in scope \| Execution: No single robotic setup <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: systematic literature synthesis/taxonomy \| Data: reviewed literature and reported benchmarks \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Machine Learning for the Multi-Dimensional Bin Packing Problem: Literature Review and Empirical Evaluation** [![arXiv](https://img.shields.io/badge/arXiv-2312.08103-b31b1b.svg)](https://arxiv.org/abs/2312.08103)
  > 👨‍🔬 **Authors:** Wu, Wenjie; Fan, Changjun; Huang, Jincai; Liu, Zhong; Yan, Junchi | 📅 **Year:** 2023 | 🏢 **Venue:** arXiv preprint arXiv:2312.08103 <br>
  > 🔑 **Keywords:** Survey, 3D bin packing, Online packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Online and offline \| Cutting-and-packing problem taxonomy <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: Varies across reviewed studies \| Stability: Reviewed when in scope \| Execution: No single robotic setup <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: systematic literature synthesis/taxonomy \| Data: reviewed literature and reported benchmarks \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Deep Study on the Application of Machine Learning in Bin Packing Problems** [![DOI](https://img.shields.io/badge/DOI-10.13053%2Fcys-28-3-5184-blue.svg)](https://doi.org/10.13053/cys-28-3-5184) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.13053%2Fcys-28-3-5184)](https://scholar.google.com/scholar?q=Deep%20Study%20on%20the%20Application%20of%20Machine%20Learning%20in%20Bin%20Packing%20Problems)
  > 👨‍🔬 **Authors:** Jessica González-San-Martín; Laura Cruz-Reyes; Bernabé Dorronsoro; Héctor Fraire-Huacuja; Fausto Balderas-Jaramillo; Marcela Quiroz-Castellanos; Nelson Rangel-Valdez | 📅 **Year:** 2024 | 🏢 **Venue:** Computación y Sistemas <br>
  > 🔑 **Keywords:** Survey, 2D packing, 3D bin packing, Dynamic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Problem-family survey \| 2D bin/strip packing <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: Varies across reviewed studies \| Stability: Reviewed when in scope \| Execution: No single robotic setup <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: systematic literature synthesis/taxonomy, heuristic search \| Data: reviewed literature and reported benchmarks \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Formulations and solutions of pallet loading problems in smart logistics** [![DOI](https://img.shields.io/badge/DOI-10.1080%2F00207543.2025.2566955-blue.svg)](https://doi.org/10.1080/00207543.2025.2566955) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1080%2F00207543.2025.2566955)](https://scholar.google.com/scholar?q=Formulations%20and%20solutions%20of%20pallet%20loading%20problems%20in%20smart%20logistics)
  > 👨‍🔬 **Authors:** Chenyang Zhang; Zijie Chen; Bochen Zhang; Mengchu Zhou | 📅 **Year:** 2026 | 🏢 **Venue:** International Journal of Production Research <br>
  > 🔑 **Keywords:** Survey, Pallet loading, Robotic palletization, Stability, Smart logistics <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Survey \| Pallet-loading formulations, constraints, and solution methods \| Palletized packages and robotic loading scenarios <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (survey paper) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: varies across reviewed studies \| Stability: practical pallet-load stability is reviewed \| Execution: robotic palletization and real-time deployment constraints are reviewed <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: structured survey and taxonomy of pallet-loading formulations and algorithms \| Data: reviewed mathematical, heuristic, learning-based, and robotic-palletizing literature \| Objective: synthesize problem variants, constraints, solution methods, and future research directions <br>

## Benchmarks of Bin Packing with Robotic Arms

- ❤️ **Benchmarking Dynamic Three-Dimensional Bin Packing Problems Using Discrete-Event Simulation** [![DOI](https://img.shields.io/badge/DOI-10.1007%2F978-3-319-31153-1_18-blue.svg)](https://doi.org/10.1007/978-3-319-31153-1_18) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1007%2F978-3-319-31153-1_18)](https://scholar.google.com/scholar?q=Benchmarking%20Dynamic%20Three-Dimensional%20Bin%20Packing%20Problems%20Using%20Discrete-Event%20Simulation)
  > 👨‍🔬 **Authors:** Ran Wang; Trung Thanh Nguyen; Shayan Kavakeb; Zaili Yang; Changhe Li | 📅 **Year:** 2016 | 🏢 **Venue:** Lecture Notes in Computer Science <br>
  > 🔑 **Keywords:** Benchmark, 3D bin packing, Dynamic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline and online/dynamic \| Single or multiple bins \| Rigid cuboids with uncertain attributes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: benchmark/environment design, simulation \| Data: real-world/industrial data with paper-reported evaluation \| Objective: optimize paper-defined packing performance <br>

- ❤️ **PackIt: A virtual environment for geometric planning** [![arXiv](https://img.shields.io/badge/arXiv-2007.11121-b31b1b.svg)](https://arxiv.org/abs/2007.11121) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/princeton-vl/PackIt)
  > 👨‍🔬 **Authors:** A Goyal, J Deng | 📅 **Year:** 2020 | 🏢 **Venue:** ICML <br>
  > 🔑 **Keywords:** Benchmark <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-box geometric planning \| Arbitrarily shaped 3D objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: benchmark/environment design, heuristic search \| Data: paper-reported benchmark/synthetic instances \| Objective: optimize paper-defined packing performance <br>

- ❤️ **DeepPack3D: A Python package for online 3D bin packing optimization by deep reinforcement learning and constructive heuristics** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.simpa.2024.100732-blue.svg)](https://doi.org/10.1016/j.simpa.2024.100732) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1016%2Fj.simpa.2024.100732)](https://scholar.google.com/scholar?q=DeepPack3D%3A%20A%20Python%20package%20for%20online%203D%20bin%20packing%20optimization%20by%20deep%20reinforcement%20learning%20and%20constructive%20heuristics) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/yptsang/DeepPack3D)
  > 👨‍🔬 **Authors:** Y. P. Tsang; D. Y. Mo; K. T. Chung; C. K. M. Lee | 📅 **Year:** 2025 | 🏢 **Venue:** Software Impacts <br>
  > 🔑 **Keywords:** Benchmark, Online packing, 3D bin packing, Deep reinforcement learning, Constructive heuristics, Python <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online with configurable lookahead \| Single-container/pallet loading benchmark \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: candidate cargo dimensions plus bin height maps \| Action: choose candidate/orientation/placement in the included DRL solver \| Reward: compactness / space utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: software package containing a Deep Q-network and four constructive heuristics \| Data: customizable item lists and bundled benchmark examples \| Objective: compare online utilization across solvers <br>

- ❤️ **MixedPalletBoxes Dataset: A Synthetic Benchmark Dataset for Warehouse Applications** [![DOI](https://img.shields.io/badge/DOI-10.3390%2Fasi9010014-blue.svg)](https://doi.org/10.3390/asi9010014) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.3390%2Fasi9010014)](https://scholar.google.com/scholar?q=MixedPalletBoxes%20Dataset%3A%20A%20Synthetic%20Benchmark%20Dataset%20for%20Warehouse%20Applications) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/Robotics-Logistics/MixedPalletBoxes)
  > 👨‍🔬 **Authors:** Adamos Daios; Ioannis Kostavelis | 📅 **Year:** 2026 | 🏢 **Venue:** Applied System Innovation <br>
  > 🔑 **Keywords:** Benchmark, Palletization, Synthetic dataset, Warehouse logistics, Object properties <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Benchmark \| Mixed-palletizing datasets and dynamic picking-list generation \| Rigid cuboid boxes with geometric, material, load, environmental, and handling attributes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (benchmark and dataset paper) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: structured tabular box attributes rather than camera observations \| Stability: load capacity, fragility, and stackability-related attributes are provided \| Execution: intended for robotic mixed-palletizing evaluation; no single robot execution pipeline <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: parameterized synthetic-data generator, seven fixed datasets, FastAPI picking-list generator, and multi-algorithm validation \| Data: seven datasets containing 500 to 100,000 records plus released generation and evaluation code \| Objective: enable reproducible, scalable, and attribute-aware benchmarking of mixed-palletizing algorithms <br>

- ❤️ **RoboBPP: Benchmarking Robotic Online Bin Packing with Physics-based Simulation** [![arXiv](https://img.shields.io/badge/arXiv-2512.04415-b31b1b.svg)](https://arxiv.org/abs/2512.04415) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://robot-bin-packing-benchmark.github.io/)
  > 👨‍🔬 **Authors:** Zhoufeng Wang1 Hang Zhao3 Juzhan Xu4 Shishun Zhang1 Zeyu Xiong1 Ruizhen Hu4 Chenyang Zhu1 Zecui Zeng5 | 📅 **Year:** 2026 | 🏢 **Venue:** arXiv preprint arXiv:2512.04415 <br>
  > 🔑 **Keywords:** Benchmark, Online packing, Robotic packing, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-bin robotic packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: physics/dynamics simulation, explicit stability checks \| Execution: robot manipulator, collision/reachability constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: benchmark/environment design, simulation \| Data: real-world/industrial data with paper-reported evaluation \| Objective: maintain stability <br>

## Algorithms and Methods

- ❤️ **The Three-Dimensional Bin Packing Problem** [![DOI](https://img.shields.io/badge/DOI-10.1287%2Fopre.48.2.256.12386-blue.svg)](https://doi.org/10.1287/opre.48.2.256.12386)
  > 👨‍🔬 **Authors:** Silvano Martello; David Pisinger; Daniele Vigo | 📅 **Year:** 2000 | 🏢 **Venue:** Operations Research <br>
  > 🔑 **Keywords:** 3D bin packing, Exact algorithm, Branch-and-bound, Approximation algorithms, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 3D-BPP \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: lower bounds, single-bin exact packing, and branch-and-bound \| Data: generated instances up to 60 boxes \| Objective: minimize bin count <br>

- ❤️ **Heuristic algorithms for the three-dimensional bin packing problem** [![Paper](https://img.shields.io/badge/Paper-Link-4682B4.svg)](https://www.sciencedirect.com/science/article/pii/S0377221702001340)
  > 👨‍🔬 **Authors:** Andrea Lodi; Silvano Martello; Daniele Vigo | 📅 **Year:** 2002 | 🏢 **Venue:** European Journal of Operational Research <br>
  > 🔑 **Keywords:** 3D bin packing, Cuboids, Tabu search <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 3D-BPP \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: constructive and improvement heuristics \| Data: standard 3D-BPP benchmark instances \| Objective: minimize bin count <br>

- ❤️ **Guided Local Search for the Three-Dimensional Bin-Packing Problem** [![DOI](https://img.shields.io/badge/DOI-10.1287%2Fijoc.15.3.267.16080-blue.svg)](https://doi.org/10.1287/ijoc.15.3.267.16080)
  > 👨‍🔬 **Authors:** Oluf Faroe; David Pisinger; Martin Zachariasen | 📅 **Year:** 2003 | 🏢 **Venue:** INFORMS Journal on Computing <br>
  > 🔑 **Keywords:** 3D bin packing, Guided local search, Heuristics, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 3D-BPP \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: guided local search \| Data: standard 3D-BPP benchmark instances \| Objective: minimize bin count <br>

- ❤️ **A Combinatorial Characterization of Higher-Dimensional Orthogonal Packing** [![DOI](https://img.shields.io/badge/DOI-10.1287%2Fmoor.1030.0079-blue.svg)](https://doi.org/10.1287/moor.1030.0079)
  > 👨‍🔬 **Authors:** Sándor P. Fekete; Jörg Schepers | 📅 **Year:** 2004 | 🏢 **Venue:** Mathematics of Operations Research <br>
  > 🔑 **Keywords:** Multi-dimensional packing, Orthogonal packing, Packing classes, Feasibility <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Fixed-container higher-dimensional orthogonal-packing feasibility \| Axis-aligned d-dimensional boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: packing-class/interval-graph characterization \| Data: theoretical instances \| Objective: decide orthogonal-packing feasibility <br>

- ❤️ **TSpack: A Unified Tabu Search Code for Multi-Dimensional Bin Packing Problems** [![DOI](https://img.shields.io/badge/DOI-10.1023%2Fb%3Aanor.0000039519.03572.08-blue.svg)](https://doi.org/10.1023/b:anor.0000039519.03572.08)
  > 👨‍🔬 **Authors:** Andrea Lodi; Silvano Martello; Daniele Vigo | 📅 **Year:** 2004 | 🏢 **Venue:** Annals of Operations Research <br>
  > 🔑 **Keywords:** 2D packing, 3D bin packing, Multi-dimensional packing, Tabu search <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 2D/3D and higher-dimensional orthogonal packing \| Rectangles and cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: unified tabu-search implementation \| Data: standard published benchmark instances \| Objective: minimize bin count <br>

- ❤️ **Algorithm 864: General and robot-packable variants of the three-dimensional bin packing problem** [![DOI](https://img.shields.io/badge/DOI-10.1145%2F1206040.1206047-blue.svg)](https://doi.org/10.1145/1206040.1206047)
  > 👨‍🔬 **Authors:** Silvano Martello; David Pisinger; Daniele Vigo; Edgar den Boef; Jan Korst | 📅 **Year:** 2007 | 🏢 **Venue:** ACM Transactions on Mathematical Software <br>
  > 🔑 **Keywords:** 3D bin packing, Exact algorithm, Robotic packing, Robot-packability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 3D-BPP with general and robot-packable variants \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: exact branch-and-bound algorithms and reference software \| Data: generated and literature benchmark instances \| Objective: minimize bin count subject to optional robot-packability <br>

- ❤️ **An Exact Algorithm for Higher-Dimensional Orthogonal Packing** [![DOI](https://img.shields.io/badge/DOI-10.1287%2Fopre.1060.0369-blue.svg)](https://doi.org/10.1287/opre.1060.0369)
  > 👨‍🔬 **Authors:** Sándor P. Fekete; Jörg Schepers; Jan C. van der Veen | 📅 **Year:** 2007 | 🏢 **Venue:** Operations Research <br>
  > 🔑 **Keywords:** Multi-dimensional packing, Orthogonal packing, Exact algorithm, Feasibility <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Fixed-container higher-dimensional orthogonal-packing feasibility \| Axis-aligned d-dimensional boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: exact branch-and-bound over packing classes \| Data: theoretical and benchmark instances \| Objective: decide feasibility <br>

- ❤️ **A Maximal-Space Algorithm for the Container Loading Problem** [![DOI](https://img.shields.io/badge/DOI-10.1287%2Fijoc.1070.0254-blue.svg)](https://doi.org/10.1287/ijoc.1070.0254)
  > 👨‍🔬 **Authors:** F. Parreño; R. Alvarez-Valdes; J. M. Tamarit; J. F. Oliveira | 📅 **Year:** 2008 | 🏢 **Venue:** INFORMS Journal on Computing <br>
  > 🔑 **Keywords:** Container loading <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container loading \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: maximal-space constructive algorithm \| Data: standard container-loading benchmarks \| Objective: maximize loaded volume <br>

- ❤️ **Extreme Point-Based Heuristics for Three-Dimensional Bin Packing** [![DOI](https://img.shields.io/badge/DOI-10.1287%2Fijoc.1070.0250-blue.svg)](https://doi.org/10.1287/ijoc.1070.0250)
  > 👨‍🔬 **Authors:** Teodor Gabriel Crainic; Guido Perboli; Roberto Tadei | 📅 **Year:** 2008 | 🏢 **Venue:** INFORMS Journal on Computing <br>
  > 🔑 **Keywords:** 3D bin packing, Extreme points, Heuristics, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 3D-BPP \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: extreme-point placement heuristics \| Data: standard 3D-BPP benchmark instances \| Objective: minimize bin count and improve utilization <br>

- ❤️ **A Hybrid CD/VND Algorithm for Three-Dimensional Bin Packing** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ficcms.2010.460-blue.svg)](https://doi.org/10.1109/iccms.2010.460)
  > 👨‍🔬 **Authors:** Huizhi Yang; Jianguo Shi | 📅 **Year:** 2010 | 🏢 **Venue:** 2010 Second International Conference on Computer Modeling and Simulation <br>
  > 🔑 **Keywords:** 3D bin packing, Caving degree, Variable-neighborhood descent, Heuristics <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 3D-BPP \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: caving-degree construction plus variable-neighborhood descent \| Data: standard literature test instances \| Objective: minimize bin count <br>

- ❤️ **A Tree Search Algorithm for Solving the Container Loading Problem** [![DOI](https://img.shields.io/badge/DOI-10.1287%2Fijoc.1090.0338-blue.svg)](https://doi.org/10.1287/ijoc.1090.0338)
  > 👨‍🔬 **Authors:** Tobias Fanslau; Andreas Bortfeldt | 📅 **Year:** 2010 | 🏢 **Venue:** INFORMS Journal on Computing <br>
  > 🔑 **Keywords:** Container loading, Cuboids, Tree search <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container loading \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: tree search \| Data: paper-reported benchmark/synthetic instances \| Objective: optimize paper-defined packing performance <br>

- ❤️ **A hybrid genetic algorithm with a new packing strategy for the three-dimensional bin packing problem** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.amc.2012.07.036-blue.svg)](https://doi.org/10.1016/j.amc.2012.07.036)
  > 👨‍🔬 **Authors:** Kyungdaw Kang; Ilkyeong Moon; Hongfeng Wang | 📅 **Year:** 2012 | 🏢 **Venue:** Applied Mathematics and Computation <br>
  > 🔑 **Keywords:** 3D knapsack packing, Genetic algorithm, Cuboids, Single bin <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-bin 3D knapsack-style packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: hybrid genetic algorithm with cuboid-space matching \| Data: published computational benchmarks \| Objective: maximize the number/value of items packed <br>

- ❤️ **A biased random key genetic algorithm for 2D and 3D bin packing problems** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.ijpe.2013.04.019-blue.svg)](https://doi.org/10.1016/j.ijpe.2013.04.019) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/rfrancotoso/brkgaAPI)
  > 👨‍🔬 **Authors:** José Fernando Gonçalves; Mauricio G.C. Resende | 📅 **Year:** 2013 | 🏢 **Venue:** International Journal of Production Economics <br>
  > 🔑 **Keywords:** 2D packing, 3D bin packing, Genetic algorithm, Maximal spaces <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 2D and 3D packing \| Rectangles and cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: biased random-key genetic algorithm plus maximal-space placement \| Data: 858 published problem instances \| Objective: minimize bin count <br>

- ❤️ **Interior-Point Based Online Stochastic Bin Packing** [![DOI](https://img.shields.io/badge/DOI-10.2139%2Fssrn.2673951-blue.svg)](https://doi.org/10.2139/ssrn.2673951)
  > 👨‍🔬 **Authors:** Varun Gupta; Ana Radovanovic | 📅 **Year:** 2015 | 🏢 **Venue:** SSRN Electronic Journal <br>
  > 🔑 **Keywords:** Online packing, Stochastic bin packing, Interior-point method, Scalar items <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online stochastic \| Multi-bin one-dimensional packing \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: interior-point/linear-programming-based online policy \| Data: stochastic synthetic instances \| Objective: minimize expected bin usage/cost <br>

- ❤️ **An Online Packing Heuristic for the Three-Dimensional Container Loading Problem in Dynamic Environments and the Physical Internet** [![DOI](https://img.shields.io/badge/DOI-10.1007%2F978-3-319-55792-2_10-blue.svg)](https://doi.org/10.1007/978-3-319-55792-2_10)
  > 👨‍🔬 **Authors:** Chi Trung Ha; Trung Thanh Nguyen; Lam Thu Bui; Ran Wang | 📅 **Year:** 2017 | 🏢 **Venue:** Lecture Notes in Computer Science <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Dynamic packing, Container loading <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container loading \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: heuristic search \| Data: real-world/industrial data with paper-reported evaluation \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Small Boxes Big Data: A Deep Learning Approach to Optimize Variable Sized Bin Packing** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Fbigdataservice.2017.18-blue.svg)](https://doi.org/10.1109/bigdataservice.2017.18)
  > 👨‍🔬 **Authors:** Feng Mao; Edgar Blanco; Mingang Fu; Rohit Jain; Anurag Gupta; Sebastien Mancel; Rong Yuan; Stephen Guo; Sai Kumar; Yayang Tian | 📅 **Year:** 2017 | 🏢 **Venue:** 2017 IEEE Third International Conference on Big Data Computing Service and Applications (BigDataService) <br>
  > 🔑 **Keywords:** Variable-sized bin packing, Deep learning, Offline packing, Scalar items <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Variable-sized multi-bin one-dimensional packing \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: deep classifier coupled to a bin-allocation heuristic \| Data: large synthetic training/evaluation sets \| Objective: minimize packing cost and bin usage <br>

- ❤️ **Solving a New 3D Bin Packing Problem with Deep Reinforcement Learning Method** [![arXiv](https://img.shields.io/badge/arXiv-1708.05930-b31b1b.svg)](https://arxiv.org/abs/1708.05930)
  > 👨‍🔬 **Authors:** Hu, Haoyuan; Zhang, Xiaodong; Yan, Xiaowei; Wang, Longfei; Xu, Yinghui | 📅 **Year:** 2017 | 🏢 **Venue:** arXiv preprint arXiv:1708.05930 <br>
  > 🔑 **Keywords:** 3D flexible bin packing, Deep reinforcement learning, Pointer network, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single variable-size/wrapping-bin 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: item-dimension sequence \| Action: choose the next item in the packing order \| Reward: negative enclosing-bin surface area / solution cost <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: pointer-network reinforcement learning for item order \| Data: generated cuboid instances \| Objective: minimize enclosing-bin surface area <br>

- ❤️ **A Multi-task Selected Learning Approach for Solving New Type 3D Bin Packing Problem** [![arXiv](https://img.shields.io/badge/arXiv-1804.06896-b31b1b.svg)](https://arxiv.org/abs/1804.06896)
  > 👨‍🔬 **Authors:** L Duan, H Hu, Y Qian, Y Gong, X Zhang, Y Xu, J Wei | 📅 **Year:** 2018 | 🏢 **Venue:** arXiv <br>
  > 🔑 **Keywords:** 3D flexible bin packing, Selected learning, Multi-task learning, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single variable-size/wrapping-bin 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: item dimensions and current partial solution \| Action: jointly choose next item and orientation \| Reward: negative enclosing-bin surface area, combined with supervised loss during selected learning <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: selected supervised/reinforcement multi-task learning for order and orientation \| Data: released large-scale generated order dataset \| Objective: minimize enclosing-bin surface area <br>

- ❤️ **Online-bounded analysis** [![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs10951-017-0536-y-blue.svg)](https://doi.org/10.1007/s10951-017-0536-y)
  > 👨‍🔬 **Authors:** Joan Boyar; Leah Epstein; Lene M. Favrholdt; Kim S. Larsen; Asaf Levin | 📅 **Year:** 2018 | 🏢 **Venue:** Journal of Scheduling <br>
  > 🔑 **Keywords:** Online algorithms, Competitive analysis, Online-bounded analysis, Theory <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Analysis framework \| Online one-dimensional optimization problems including bin packing \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: online-bounded performance analysis \| Data: adversarial theoretical instances \| Objective: compare online algorithms against a constrained offline optimum <br>

- ❤️ **Packing Irregular Objects in 3D Space via Hybrid Optimization** [![DOI](https://img.shields.io/badge/DOI-10.1111%2Fcgf.13490-blue.svg)](https://doi.org/10.1111/cgf.13490) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/MbBrainz/irregular-object-packing)
  > 👨‍🔬 **Authors:** Y. Ma; Z. Chen; W. Hu; W. Wang | 📅 **Year:** 2018 | 🏢 **Venue:** Computer Graphics Forum <br>
  > 🔑 **Keywords:** 3D bin packing, Irregular objects <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container geometric packing \| Irregular/general 3D objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: heuristic search \| Data: paper-reported benchmark/synthetic instances \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Quasi-Monte-Carlo Tree Search for 3D Bin Packing** [![Paper](https://img.shields.io/badge/Paper-Link-4682B4.svg)](https://link.springer.com/chapter/10.1007/978-3-030-03398-9_33)
  > 👨‍🔬 **Authors:** Li, Hailiang; Wang, Yan; Ma, DanPeng; Fang, Yang; Lei, Zhibin | 📅 **Year:** 2018 | 🏢 **Venue:** Chinese Conference on Pattern Recognition and Computer Vision <br>
  > 🔑 **Keywords:** 3D bin packing, Monte Carlo tree search, Quasi-Monte Carlo, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container/open-dimension 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: quasi-Monte-Carlo tree search \| Data: generated and standard 3D packing instances \| Objective: maximize utilization and reduce packing height <br>

- ❤️ **Ranked reward: Enabling self-play reinforcement learning for combinatorial optimization** [![arXiv](https://img.shields.io/badge/arXiv-1807.01672-b31b1b.svg)](https://arxiv.org/abs/1807.01672)
  > 👨‍🔬 **Authors:** A Laterre, Y Sun, K Beguir, C Rousseau, T Inst | 📅 **Year:** 2018 | 🏢 **Venue:** arXiv <br>
  > 🔑 **Keywords:** Reinforcement learning, Self-play, Combinatorial optimization, Bin packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Combinatorial packing benchmark within a general self-play framework \| Paper-defined regular items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: all items plus current placements \| Action: choose an unplaced item, position, and orientation \| Reward: terminal solution quality reshaped to a percentile-ranked reward <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: self-play reinforcement learning with percentile-ranked rewards \| Data: generated combinatorial-optimization instances \| Objective: improve terminal solution quality without labeled optima <br>

- ❤️ **A Multi-task Selected Learning Approach for Solving 3D Flexible Bin Packing Problem** [![DOI](https://img.shields.io/badge/DOI-10.65109%2Fphej7266-blue.svg)](https://doi.org/10.65109/phej7266)
  > 👨‍🔬 **Authors:** Lu Duan; Haoyuan Hu; Yu Qian; Yu Gong; Xiaodong Zhang; Jiangwen Wei; Yinghui Xu | 📅 **Year:** 2019 | 🏢 **Venue:** International Joint Conference on Autonomous Agents and Multiagent Systems <br>
  > 🔑 **Keywords:** 3D flexible bin packing, Selected learning, Multi-task learning, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single variable-size/wrapping-bin 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: selected multi-task learning for order and orientation \| Data: real e-commerce orders and synthetic instances \| Objective: minimize enclosing-bin surface area/cost <br>

- ❤️ **Deep-Pack: A Vision-Based 2D Online Bin Packing Algorithm with Deep Reinforcement Learning** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Fro-man46459.2019.8956393-blue.svg)](https://doi.org/10.1109/ro-man46459.2019.8956393) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/JeepWay/DeepPack)
  > 👨‍🔬 **Authors:** Olyvia Kundu; Samrat Dutta; Swagat Kumar | 📅 **Year:** 2019 | 🏢 **Venue:** 2019 28th IEEE International Conference on Robot and Human Interactive Communication (RO-MAN) <br>
  > 🔑 **Keywords:** 2D packing, Online packing, Deep reinforcement learning, Double DQN, Vision <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-bin 2D placement \| Rectangles <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: binary images of current bin occupancy and incoming rectangle \| Action: choose a placement pixel (or reject/terminate) \| Reward: compact adjacency and retained grouped empty area <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: image-based Double DQN placement policy \| Data: generated rectangle streams \| Objective: maximize packing density and preserve usable empty space <br>

- ❤️ **Multi-objective 3D bin-packing problem** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ficmsao.2019.8880442-blue.svg)](https://doi.org/10.1109/icmsao.2019.8880442)
  > 👨‍🔬 **Authors:** Jasim Hasan; Jihene Kaabi; Youssef Harrath | 📅 **Year:** 2019 | 🏢 **Venue:** 2019 8th International Conference on Modeling Simulation and Applied Optimization (ICMSAO) <br>
  > 🔑 **Keywords:** 3D bin packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 3D packing with weight balance \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: two-phase layer-combination constructive algorithm \| Data: FedEx real-world cases \| Objective: minimize bin count and balance bin weight <br>

- ❤️ **Stable Bin Packing of Non-convex 3D Objects with a Robot Manipulator** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ficra.2019.8794049-blue.svg)](https://doi.org/10.1109/icra.2019.8794049)
  > 👨‍🔬 **Authors:** Fan Wang; Kris Hauser | 📅 **Year:** 2019 | 🏢 **Venue:** 2019 International Conference on Robotics and Automation (ICRA) <br>
  > 🔑 **Keywords:** 3D packing, Irregular objects, Robotic packing, Stability, Non-convex objects <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container robotic packing \| Rigid non-convex 3D objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known 3D meshes \| Stability: support and static-stability constraints \| Execution: robot-manipulator reachability and collision constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: stability-aware geometric search and robot-motion feasibility filtering \| Data: simulated and physical object sets \| Objective: maximize packing density while preserving stable, executable placements <br>

- ❤️ **A Generalized Reinforcement Learning Algorithm for Online 3D Bin-Packing** [![arXiv](https://img.shields.io/badge/arXiv-2007.00463-b31b1b.svg)](https://arxiv.org/abs/2007.00463) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://nsidn98.github.io/publication/packman)
  > 👨‍🔬 **Authors:** Richa Verma; Aniruddha Singhal; Harshad Khadilkar; Ansuma Basumatary; Siddharth Nayak; Harsh Vardhan Singh; Swagat Kumar; Rajesh Sinha | 📅 **Year:** 2020 | 🏢 **Venue:** arXiv preprint arXiv:2007.00463 <br>
  > 🔑 **Keywords:** Online packing, 3D bin packing, Deep reinforcement learning, Lookahead, Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online with fixed lookahead \| One or more bins of arbitrary size \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: current bin packing plus a fixed lookahead of upcoming box dimensions \| Action: choose bin, location, and orientation for the next box \| Reward: packed-volume efficiency with a bin-count/competitive-ratio objective <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: robot manipulator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: generalized deep reinforcement learning placement policy \| Data: simulated streams and laboratory robot validation \| Objective: maximize volume efficiency and empirical competitive ratio <br>

- ❤️ **Fully dynamic bin packing revisited** [![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs10107-018-1325-x-blue.svg)](https://doi.org/10.1007/s10107-018-1325-x)
  > 👨‍🔬 **Authors:** Sebastian Berndt; Klaus Jansen; Kim-Manuel Klein | 📅 **Year:** 2020 | 🏢 **Venue:** Mathematical Programming <br>
  > 🔑 **Keywords:** Dynamic packing, 1D bin packing, Repacking, Approximation algorithms <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Fully dynamic \| Multi-bin packing with arrivals, departures, and repacking \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: dynamic rounding and approximation algorithms \| Data: adversarial theoretical sequences \| Objective: minimize bin count while bounding migration/repacking <br>

- ❤️ **Simultaneous Planning for Item Picking and Placing by Deep Reinforcement Learning** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Firos45743.2020.9340929-blue.svg)](https://doi.org/10.1109/iros45743.2020.9340929)
  > 👨‍🔬 **Authors:** Tatsuya Tanaka; Toshimitsu Kaneko; Masahiro Sekine; Voot Tangkaratt; Masashi Sugiyama | 📅 **Year:** 2020 | 🏢 **Venue:** 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) <br>
  > 🔑 **Keywords:** Online packing, Container loading, Deep reinforcement learning, Tree search, Approximation algorithms, Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-tote robotic pick-and-place packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: tote/container occupancy and local pick-place features \| Action: jointly choose picking and placing positions \| Reward: container occupancy / successful loading <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: deep reinforcement learning for joint picking and placing \| Data: simulated tote-packing episodes \| Objective: maximize container occupancy and successful placements <br>

- ❤️ **Smart Packing Simulator for 3D Packing Problem Using Genetic Algorithm** [![DOI](https://img.shields.io/badge/DOI-10.1088%2F1742-6596%2F1447%2F1%2F012041-blue.svg)](https://doi.org/10.1088/1742-6596/1447/1/012041) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/mcruggiero/Genetic_Bin/tree/master)
  > 👨‍🔬 **Authors:** U. Khairuddin; N. A. Z. M. Razi; M. S. Z. Abidin; R. Yusof | 📅 **Year:** 2020 | 🏢 **Venue:** Journal of Physics: Conference Series <br>
  > 🔑 **Keywords:** 3D bin packing, Palletization, Genetic algorithm <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single variable-size container arrangement \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: adaptable-chromosome genetic algorithm and 3D simulator \| Data: generated box sets \| Objective: minimize required container size <br>

- ❤️ **TAP-Net: Transport-and-Pack using Reinforcement Learning** [![arXiv](https://img.shields.io/badge/arXiv-2009.01469-b31b1b.svg)](https://arxiv.org/abs/2009.01469) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/Juzhan/TAP-Net)
  > 👨‍🔬 **Authors:** Ruizhen Hu, Juzhan Xu, Bin Chen, Minglun Gong, Hao Zhang, Hui Huang | 📅 **Year:** 2020 | 🏢 **Venue:** ACM Trans. Graph <br>
  > 🔑 **Keywords:** 3D bin packing, Robotic packing, Deep reinforcement learning, Precedence graph, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single target-container transport-and-pack planning \| Rigid cuboids with accessibility constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: transport precedence graph plus current target-container packing \| Action: choose next box and orientation \| Reward: mean of compactness, pyramidality, and stability <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: precedence-graph reinforcement learning \| Data: generated box sets and simulated robot tasks \| Objective: jointly optimize compactness, pyramidality, and stability <br>

- ❤️ **A generalized algorithm and framework for online 3-dimensional bin packing in an automated sorting center** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ficc54714.2021.9703142-blue.svg)](https://doi.org/10.1109/icc54714.2021.9703142)
  > 👨‍🔬 **Authors:** Ankush Ojha; Marichi Agarwal; Aniruddha Singhal; Chayan Sarkar; Supratim Ghosh; Rajesh Sinha | 📅 **Year:** 2021 | 🏢 **Venue:** 2021 Seventh Indian Control Conference (ICC) <br>
  > 🔑 **Keywords:** Online packing, 3D bin packing, Automated sorting, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Sequential 3D packing in an automated sorting center \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: robot manipulator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: generalized constructive framework and heuristic \| Data: sorting-center cases and generated streams \| Objective: maximize utilization with stable feasible placements <br>

- ❤️ **A Novel Heuristic Algorithm for Online 3D Bin Packing** [![DOI](https://img.shields.io/badge/DOI-10.23919%2Ficcas52745.2021.9649790-blue.svg)](https://doi.org/10.23919/iccas52745.2021.9649790)
  > 👨‍🔬 **Authors:** Thanh-Hung Nguyen; Viet-Thang Tran; Phan-Quan Doan; Thi-Thoa Mac | 📅 **Year:** 2021 | 🏢 **Venue:** 2021 21st International Conference on Control, Automation and Systems (ICCAS) <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-bin sequential packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: robot manipulator, palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: heuristic search \| Data: paper-reported benchmark/synthetic instances \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Attend2Pack: Bin Packing through Deep Reinforcement Learning with Attention** [![arXiv](https://img.shields.io/badge/arXiv-2107.04333-b31b1b.svg)](https://arxiv.org/abs/2107.04333) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/larson-7/RL_Bpp)
  > 👨‍🔬 **Authors:** Jingwei Zhang, Bin Zi, Xiaoyu Ge | 📅 **Year:** 2021 | 🏢 **Venue:** arXiv preprint arXiv:2107.04333 <br>
  > 🔑 **Keywords:** 3D bin packing, Offline packing, Online packing, Attention, Deep reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline with online variant \| Single-container 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: encoded item set plus partial packing configuration \| Action: sequence agent selects the next item; placement agent selects orientation and position \| Reward: terminal bin utility / utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: attention-based sequence and placement policies \| Data: generated 3D packing instances \| Objective: maximize utilization <br>

- ❤️ **Jampacker: An Efficient and Reliable Robotic Bin Packing System for Cuboid Objects** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Flra.2020.3043168-blue.svg)](https://doi.org/10.1109/lra.2020.3043168)
  > 👨‍🔬 **Authors:** Marichi Agarwal; Swagata Biswas; Chayan Sarkar; Sayan Paul; Himadri Sekhar Paul | 📅 **Year:** 2021 | 🏢 **Venue:** IEEE Robotics and Automation Letters <br>
  > 🔑 **Keywords:** Robotic packing, 3D bin packing, Cuboids, Fault recovery, Corner points <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container robotic packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: robot manipulator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: internal-corner-point placement with execution monitoring and recovery \| Data: simulation and real-robot box trials \| Objective: maximize utilization and execution reliability <br>

- ❤️ **Learning Efficient Online 3D Bin Packing on Packing Configuration Trees** [![OpenReview](https://img.shields.io/badge/OpenReview-Paper-8E44AD.svg)](https://openreview.net/forum?id=bfuGjlCwAq) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/alexfrom0815/Online-3D-BPP-PCT)
  > 👨‍🔬 **Authors:** Zhao, Hang; Yu, Yang; Xu, Kai | 📅 **Year:** 2021 | 🏢 **Venue:** ICLR <br>
  > 🔑 **Keywords:** Online packing, 3D bin packing, Packing configuration tree, Deep reinforcement learning, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container sequential 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: packing-configuration tree for the current bin and incoming item \| Action: choose a feasible tree node / placement \| Reward: incremental packed volume and terminal utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: packing-configuration-tree reinforcement learning \| Data: generated streams and constrained benchmark variants \| Objective: maximize utilization under practical constraints <br>

- ❤️ **Learning to Pack: A Data-Driven Tree Search Algorithm for Large-Scale 3D Bin Packing Problem** [![DOI](https://img.shields.io/badge/DOI-10.1145%2F3459637.3481933-blue.svg)](https://doi.org/10.1145/3459637.3481933)
  > 👨‍🔬 **Authors:** Qianwen Zhu; Xihan Li; Zihan Zhang; Zhixing Luo; Xialiang Tong; Mingxuan Yuan; Jia Zeng | 📅 **Year:** 2021 | 🏢 **Venue:** CIKM '21: Proceedings of the 30th ACM International Conference on Information & Knowledge Management <br>
  > 🔑 **Keywords:** 3D bin packing, Tree search <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Large-scale 3D container loading \| Heterogeneous cuboid cargo <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: CNN-guided tree search \| Data: large-scale Huawei industrial orders plus synthetic instances \| Objective: maximize loading rate <br>

- ❤️ **Low Cost Bin Picking Solution for E-Commerce Warehouse Fulfillment Centers** [![arXiv](https://img.shields.io/badge/arXiv-2109.12234-b31b1b.svg)](https://arxiv.org/abs/2109.12234)
  > 👨‍🔬 **Authors:** Avnish Gupta, Akash Jadhav, Pradyot VN Korupolu | 📅 **Year:** 2021 | 🏢 **Venue:** arXiv preprint arXiv:2109.12234 <br>
  > 🔑 **Keywords:** Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Scope-adjacent bin picking/perception \| Not a packing policy \| General objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: point cloud, vision \| Stability: geometric non-overlap only \| Execution: robot manipulator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: paper-specific optimization/learning method \| Data: paper-reported benchmark/synthetic instances \| Objective: estimate 6D object poses <br>

- ❤️ **Multi-objective 3D bin packing problem with load balance and product family concerns** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cie.2021.107518-blue.svg)](https://doi.org/10.1016/j.cie.2021.107518)
  > 👨‍🔬 **Authors:** Seda Erbayrak; Vildan Özkır; U. Mahir Yıldırım | 📅 **Year:** 2021 | 🏢 **Venue:** Computers & Industrial Engineering <br>
  > 🔑 **Keywords:** 3D bin packing, Container loading, Cuboids, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 3D packing with balance and product-family constraints \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: multi-objective mixed-integer programming \| Data: numerical and generated test instances \| Objective: minimize bin count and balance deviation while maximizing family unity <br>

- ❤️ **Online 3D Bin Packing with Constrained Deep Reinforcement Learning** [![DOI](https://img.shields.io/badge/DOI-10.1609%2Faaai.v35i1.16155-blue.svg)](https://doi.org/10.1609/aaai.v35i1.16155) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/alexfrom0815/Online-3D-BPP-DRL)
  > 👨‍🔬 **Authors:** Hang Zhao; Qijin She; Chenyang Zhu; Yin Yang; Kai Xu | 📅 **Year:** 2021 | 🏢 **Venue:** Proceedings of the AAAI Conference on Artificial Intelligence <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Deep reinforcement learning, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container sequential 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bin height map plus current/lookahead item dimensions \| Action: choose a feasible 2D placement (orientation in the extension) \| Reward: placed-volume fraction / final space utilization; feasibility handled as a constraint mask <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: RGB-D/depth \| Stability: explicit stability checks \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: constrained deep reinforcement learning with feasibility masks \| Data: generated streams and paper-reported benchmarks \| Objective: maximize utilization subject to geometric/physical feasibility <br>

- ❤️ **Robot Packing With Known Items and Nondeterministic Arrival Order** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ftase.2020.3024291-blue.svg)](https://doi.org/10.1109/tase.2020.3024291)
  > 👨‍🔬 **Authors:** Fan Wang; Kris Hauser | 📅 **Year:** 2021 | 🏢 **Venue:** IEEE Transactions on Automation Science and Engineering <br>
  > 🔑 **Keywords:** Online packing, Irregular objects, Robotic packing, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container geometric packing \| Irregular/general 3D objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: robot manipulator, collision/reachability constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: paper-specific optimization/learning method \| Data: paper-reported benchmark/synthetic instances \| Objective: maintain stability <br>

- ❤️ **Robotic Pick-and-Place With Uncertain Object Instance Segmentation and Shape Completion** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Flra.2021.3060669-blue.svg)](https://doi.org/10.1109/lra.2021.3060669)
  > 👨‍🔬 **Authors:** Marcus Gualtieri; Robert Platt | 📅 **Year:** 2021 | 🏢 **Venue:** IEEE Robotics and Automation Letters <br>
  > 🔑 **Keywords:** Scope-adjacent, Robotic pick-and-place, Instance segmentation, Shape completion, Regrasp planning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Scope-adjacent manipulation \| Uncertainty-aware pick-place and regrasp planning, not a packing policy \| General objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (uncertainty-aware regrasp planning, not RL) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: RGB-D instance segmentation and shape completion \| Stability: grasp/place uncertainty model \| Execution: robot-manipulator regrasp planning <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: uncertainty-aware perception and regrasp planning \| Data: simulated and physical manipulation scenes \| Objective: improve pick-place success under uncertain object shape <br>

- ❤️ **Solving 3D Bin Packing Problem via Multimodal Deep Reinforcement Learning** [![DOI](https://img.shields.io/badge/DOI-10.65109%2Fuxma6584-blue.svg)](https://doi.org/10.65109/uxma6584)
  > 👨‍🔬 **Authors:** Yuan Jiang; Zhiguang Cao; Jie Zhang | 📅 **Year:** 2021 | 🏢 **Venue:** International Joint Conference on Autonomous Agents and Multiagent Systems <br>
  > 🔑 **Keywords:** 3D bin packing, Deep reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single variable-height/large 3D container \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: box-sequence features plus CNN-encoded spatial view state \| Action: sequentially choose item, orientation, and position \| Reward: utilization-based return optimized with A2C/GAE <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: multimodal deep reinforcement learning for sequence, orientation, and position \| Data: generated instances up to 100+ boxes \| Objective: maximize utilization / minimize packing height <br>

- ❤️ **Dense Robotic Packing of Irregular and Novel 3D Objects** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ftro.2021.3097261-blue.svg)](https://doi.org/10.1109/tro.2021.3097261)
  > 👨‍🔬 **Authors:** Fan Wang; Kris Hauser | 📅 **Year:** 2022 | 🏢 **Venue:** IEEE Transactions on Robotics <br>
  > 🔑 **Keywords:** Robotic packing, Irregular objects, 3D vision, Stability, Novel objects <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container robotic packing \| Irregular and previously unseen rigid 3D objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: height map \| Stability: explicit stability checks \| Execution: collision/reachability constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: geometry- and stability-aware robotic packing pipeline \| Data: simulated objects and real-robot trials \| Objective: maximize compactness and stable placement success <br>

- ❤️ **Learning practically feasible policies for online 3D bin packing** [![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs11432-021-3348-6-blue.svg)](https://doi.org/10.1007/s11432-021-3348-6)
  > 👨‍🔬 **Authors:** Hang Zhao; Chenyang Zhu; Xin Xu; Hui Huang; Kai Xu | 📅 **Year:** 2022 | 🏢 **Venue:** Science China Information Sciences <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Deep reinforcement learning, Robotic packing, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container sequential 3D packing with practical constraints \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bin height map and current item \| Action: choose a feasibility-masked placement and orientation \| Reward: packed-volume utilization with penalties/constraints for infeasible placements <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: robot manipulator, collision/reachability constraints, palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: feasibility-constrained deep reinforcement learning \| Data: generated streams and real-system constraints \| Objective: maximize utilization while ensuring executable placements <br>

- ❤️ **One model packs thousands of items with Recurrent Conditional Query Learning** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.knosys.2021.107683-blue.svg)](https://doi.org/10.1016/j.knosys.2021.107683)
  > 👨‍🔬 **Authors:** Dongda Li; Zhaoquan Gu; Yuexuan Wang; Changwei Ren; Francis C.M. Lau | 📅 **Year:** 2022 | 🏢 **Venue:** Knowledge-Based Systems <br>
  > 🔑 **Keywords:** 2D packing, 3D bin packing, Recurrent conditional query learning, Offline packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container 2D/3D geometric packing \| Rectangles and cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: recurrent conditional query learning \| Data: generated instances containing up to thousands of items \| Objective: maximize utilization at large scale <br>

- ❤️ **Online 3D Bin Packing Reinforcement Learning Solution with Buffer** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Firos47612.2022.9982095-blue.svg)](https://doi.org/10.1109/iros47612.2022.9982095)
  > 👨‍🔬 **Authors:** Aaron Valero Puche; Sukhan Lee | 📅 **Year:** 2022 | 🏢 **Venue:** 2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Deep reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online with finite buffer \| Single-container sequential 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bin height map, current item, and buffer state \| Action: place the item or defer it to the buffer \| Reward: placed volume minus wasted-space cost <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: robot manipulator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: buffer-aware deep reinforcement learning \| Data: generated online streams \| Objective: maximize utilization and reduce wasted space <br>

- ❤️ **Robot Online 3D Bin Packing Strategy Based on Deep Reinforcement Learning and 3D Vision** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ficnsc55942.2022.10004170-blue.svg)](https://doi.org/10.1109/icnsc55942.2022.10004170)
  > 👨‍🔬 **Authors:** Jie Jia; Huiliang Shang; Xiong Chen | 📅 **Year:** 2022 | 🏢 **Venue:** 2022 IEEE International Conference on Networking, Sensing and Control (ICNSC) <br>
  > 🔑 **Keywords:** Online packing, Robotic palletization, 3D vision, Deep reinforcement learning, Monte Carlo tree search <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online with lookahead \| Robotic pallet loading \| Rigid cartons <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: 3D-vision object features plus packing-configuration tree \| Action: choose a feasible placement node and orientation \| Reward: packed-volume / space utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: point-cloud size/pose estimation \| Stability: packing-configuration-tree feasibility \| Execution: intelligent palletizing robot <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: Actor-Critic plus Monte Carlo tree search on a packing configuration tree \| Data: simulated and physical palletizing trials \| Objective: maximize utilization and robust execution <br>

- ❤️ **Towards Online 3D Bin Packing: Learning Synergies between Packing and Unpacking via DRL** [![Paper](https://img.shields.io/badge/Paper-Link-4682B4.svg)](https://proceedings.mlr.press/v205/song23a.html)
  > 👨‍🔬 **Authors:** Shuai Song, Shuo Yang, Ran Song, Shilei Chu, yibin Li, Wei Zhang | 📅 **Year:** 2022 | 🏢 **Venue:** Knowl.-Based Syst <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Deep reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container robotic packing with corrective unpacking \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: current bin configuration plus incoming/buffered items \| Action: pack an item or unpack/reorder placed items \| Reward: compactness/utilization with invalid-action penalties <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: synergistic pack/unpack deep reinforcement learning \| Data: simulated streams and robot evaluation \| Objective: improve utilization and recover from poor placements <br>

- ❤️ **A Constructive Heuristic Algorithm for 3D Bin Packing of Irregular Shaped Items** [![DOI](https://img.shields.io/badge/DOI-10.1007%2F978-3-031-15644-1_29-blue.svg)](https://doi.org/10.1007/978-3-031-15644-1_29) [![arXiv](https://img.shields.io/badge/arXiv-2206.15116-b31b1b.svg)](https://arxiv.org/abs/2206.15116)
  > 👨‍🔬 **Authors:** Qiruyi Zuo; Xinglu Liu; Wai Kin Victor Chan | 📅 **Year:** 2022 | 🏢 **Venue:** City, Society, and Digital Transformation <br>
  > 🔑 **Keywords:** 3D packing, Irregular objects, Deformable items, Constructive heuristics <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container 3D packing \| Irregular and shape-changing items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (constructive heuristic method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item and container geometry \| Stability: geometric non-overlap and container-boundary feasibility only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: dynamic-volume constructive heuristic with an item shape-changing factor \| Data: generated irregular-item instances \| Objective: maximize space utilization while accommodating irregular or deformable item geometry <br>

- ❤️ **Adjustable Robust Reinforcement Learning for Online 3D Bin Packing** [![DOI](https://img.shields.io/badge/DOI-10.52202%2F075280-2262-blue.svg)](https://doi.org/10.52202/075280-2262) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/panyxy/ar2l_bpp)
  > 👨‍🔬 **Authors:** Yuxin Pan; Yize Chen; Fangzhen Lin | 📅 **Year:** 2023 | 🏢 **Venue:** Advances in Neural Information Processing Systems 36 <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Dynamic packing, Deep reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online with adjustable robustness \| Single-container sequential 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: packed items, observed incoming items, and potential placement positions \| Action: select an observed item and feasible placement \| Reward: weighted expected and worst-case utilization returns <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: adjustable robust reinforcement learning \| Data: generated online streams and paper-reported real distributions \| Objective: balance expected and worst-case utilization <br>

- ❤️ **Compliant‐based robotic 3D bin packing with unavoidable uncertainties** [![DOI](https://img.shields.io/badge/DOI-10.1049%2Fcth2.12432-blue.svg)](https://doi.org/10.1049/cth2.12432)
  > 👨‍🔬 **Authors:** Wei Shuai; Yang Gao; Peichen Wu; Guowei Cui; Qinghao Zhuang; Rongya Chen; Xiaoping Chen | 📅 **Year:** 2023 | 🏢 **Venue:** IET Control Theory & Applications <br>
  > 🔑 **Keywords:** Online packing, Robotic packing, 3D bin packing, Deformed boxes, Compliance, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container robotic packing under perception/planning/execution uncertainty \| Deformed cuboid cases <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: low-cost depth sensing and box geometry \| Stability: close-contact/friction strategy \| Execution: compliant end-effector and contact-rich robot motion <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: EMS candidate placement plus dense/deviation-tolerant stacking and compliant motion planning \| Data: simulation and 30 physical packing trials \| Objective: maintain stability, robustness, and high utilization under uncertainty <br>

- ❤️ **Learning Based 2D Irregular Shape Packing** [![DOI](https://img.shields.io/badge/DOI-10.1145%2F3618348-blue.svg)](https://doi.org/10.1145/3618348)
  > 👨‍🔬 **Authors:** Zeshi Yang; Zherong Pan; Manyi Li; Kui Wu; Xifeng Gao | 📅 **Year:** 2023 | 🏢 **Venue:** ACM Transactions on Graphics <br>
  > 🔑 **Keywords:** 2D irregular packing, Irregular polygons, Learning-based packing, Offline packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-sheet/atlas 2D irregular packing \| Irregular polygons <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: learning-assisted irregular-shape grouping and placement \| Data: paper-reported polygon datasets \| Objective: maximize packing ratio <br>

- ❤️ **Learning Physically Realizable Skills for Online Packing of General 3D Shapes** [![DOI](https://img.shields.io/badge/DOI-10.1145%2F3603544-blue.svg)](https://doi.org/10.1145/3603544) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/alexfrom0815/IR-BPP)
  > 👨‍🔬 **Authors:** Hang Zhao; Zherong Pan; Yang Yu; Kai Xu | 📅 **Year:** 2023 | 🏢 **Venue:** ACM Transactions on Graphics <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container geometric packing \| Irregular/general 3D objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: RGB-D/depth \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: paper-specific optimization/learning method \| Data: paper-reported benchmark/synthetic instances \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Learning to multi-vehicle cooperative bin packing problem via sequence-to-sequence policy network with deep reinforcement learning model** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cie.2023.108998-blue.svg)](https://doi.org/10.1016/j.cie.2023.108998)
  > 👨‍🔬 **Authors:** Ran Tian; Chunming Kang; Jiaming Bi; Zhongyu Ma; Yanxing Liu; Saisai Yang; Fangfang Li | 📅 **Year:** 2023 | 🏢 **Venue:** Computers & Industrial Engineering <br>
  > 🔑 **Keywords:** 3D bin packing, Multi-vehicle loading, Deep reinforcement learning, Sequence-to-sequence <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Cooperative multi-vehicle 3D loading \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: remaining item sequence and current multi-vehicle load state \| Action: choose the next item in the packing sequence; placement uses LBPS/MVCBPS \| Reward: cumulative packed volume / average vehicle utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: sequence-to-sequence policy plus LBPS/MVCBPS placement \| Data: generated multi-vehicle instances \| Objective: maximize average vehicle utilization <br>

- ❤️ **Learning to Solve 3-D Bin Packing Problem via Deep Reinforcement Learning and Constraint Programming** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ftcyb.2021.3121542-blue.svg)](https://doi.org/10.1109/tcyb.2021.3121542)
  > 👨‍🔬 **Authors:** Yuan Jiang; Zhiguang Cao; Jie Zhang | 📅 **Year:** 2023 | 🏢 **Venue:** IEEE Transactions on Cybernetics <br>
  > 🔑 **Keywords:** 3D bin packing, Deep reinforcement learning, Constraint programming, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single variable-height 3D container \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: box-sequence state plus CNN-encoded spatial view state \| Action: sequentially choose item, orientation, and position \| Reward: utilization-based return; constraint programming refines the DRL solution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: multimodal deep reinforcement learning refined by constraint programming \| Data: generated and standard benchmark instances \| Objective: maximize utilization and minimize packing height <br>

- ❤️ **Online Bin Packing with Predictions** [![DOI](https://img.shields.io/badge/DOI-10.1613%2Fjair.1.14820-blue.svg)](https://doi.org/10.1613/jair.1.14820)
  > 👨‍🔬 **Authors:** Spyros Angelopoulos; Shahin Kamali; Kimia Shadkami | 📅 **Year:** 2023 | 🏢 **Venue:** Journal of Artificial Intelligence Research <br>
  > 🔑 **Keywords:** Online packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online with predictions \| Multi-bin one-dimensional packing \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: paper-specific optimization/learning method \| Data: paper-reported benchmark/synthetic instances \| Objective: minimize bin count <br>

- ❤️ **Planning Irregular Object Packing via Hierarchical Reinforcement Learning** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Flra.2022.3222996-blue.svg)](https://doi.org/10.1109/lra.2022.3222996) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/Chiba9/Irregular-Object-Packing)
  > 👨‍🔬 **Authors:** Sichao Huang; Ziwei Wang; Jie Zhou; Jiwen Lu | 📅 **Year:** 2023 | 🏢 **Venue:** IEEE Robotics and Automation Letters <br>
  > 🔑 **Keywords:** 3D packing, Irregular objects, Hierarchical reinforcement learning, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container 3D packing \| Irregular rigid objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: irregular-object geometry and current container configuration \| Action: hierarchical object/region selection followed by placement pose \| Reward: compactness and physical stability <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: height map \| Stability: explicit stability checks \| Execution: robot manipulator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: hierarchical reinforcement learning for object/region/pose decisions \| Data: simulated irregular-object sets \| Objective: maximize compactness while preserving stability <br>

- ❤️ **SDF-Pack: Towards Compact Bin Packing with Signed-Distance-Field Minimization** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Firos55552.2023.10341940-blue.svg)](https://doi.org/10.1109/iros55552.2023.10341940) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/kwpoon/SDF-Pack)
  > 👨‍🔬 **Authors:** Jia-Hui Pan; Ka-Hei Hui; Xiaojie Gao; Shize Zhu; Yun-Hui Liu; Pheng-Ann Heng; Chi-Wing Fu | 📅 **Year:** 2023 | 🏢 **Venue:** 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) <br>
  > 🔑 **Keywords:** 3D packing, Irregular objects, Signed-distance field, Optimization <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container/open-dimension 3D packing \| General irregular rigid objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: height map, signed-distance field \| Stability: geometric non-overlap only \| Execution: robot manipulator, collision/reachability constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: signed-distance-field minimization \| Data: simulated mesh-object sets \| Objective: maximize compactness / minimize occupied container volume <br>

- ❤️ **Solving 3D packing problem using Transformer network and reinforcement learning** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.eswa.2022.119153-blue.svg)](https://doi.org/10.1016/j.eswa.2022.119153)
  > 👨‍🔬 **Authors:** Quanqing Que; Fang Yang; Defu Zhang | 📅 **Year:** 2023 | 🏢 **Venue:** Expert Systems with Applications <br>
  > 🔑 **Keywords:** 3D packing, Transformer, Deep reinforcement learning, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single variable-height 3D container \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: multi-plane container features plus remaining-box features \| Action: choose box, orientation, and placement position \| Reward: reduction in unused-volume/gap ratio <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: Transformer policy optimized with reinforcement learning \| Data: generated cuboid instances \| Objective: minimize gap ratio and packing height <br>

- ❤️ **Think inside the box: 3D bin packing visualized with spatial AR and automated depth feedback** [![Paper](https://img.shields.io/badge/Paper-Link-4682B4.svg)](https://www.diva-portal.org/smash/record.jsf?pid=diva2:1801204)
  > 👨‍🔬 **Authors:** K Wihl | 📅 **Year:** 2023 | 🏢 **Venue:** DiVA <br>
  > 🔑 **Keywords:** 3D bin packing, Spatial augmented reality, Human-in-the-loop, Depth feedback <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline plan with interactive execution \| Human-assisted single-container packing \| Rigid cuboids/consumer goods <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: depth feedback and spatial AR \| Stability: plan-defined geometric support \| Execution: human placement guided by projected feedback <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: precomputed 3D packing plan with spatial-AR/depth guidance \| Data: physical user packing trials \| Objective: improve placement accuracy and realized fit <br>

- ❤️ **Towards reliable robot packing system based on deep reinforcement learning** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.aei.2023.102028-blue.svg)](https://doi.org/10.1016/j.aei.2023.102028)
  > 👨‍🔬 **Authors:** Heng Xiong; Kai Ding; Wan Ding; Jian Peng; Jianfeng Xu | 📅 **Year:** 2023 | 🏢 **Venue:** Advanced Engineering Informatics <br>
  > 🔑 **Keywords:** Online packing, Robotic packing, Deep reinforcement learning, Stability, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container robotic packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bin height map, current item, and learned feasibility mask \| Action: choose placement position and orientation \| Reward: utilization with infeasible/unsafe-placement penalties <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: collision/reachability constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: feasibility-masked deep reinforcement learning \| Data: simulation and robot packing trials \| Objective: maximize utilization and reliable placement success <br>

- ❤️ **World-Model-Based Control for Industrial box-packing of Multiple Objects using NewtonianVAE** [![arXiv](https://img.shields.io/badge/arXiv-2308.02136-b31b1b.svg)](https://arxiv.org/abs/2308.02136)
  > 👨‍🔬 **Authors:** Y Kato, R Okumura, T Taniguchi | 📅 **Year:** 2023 | 🏢 **Venue:** arXiv <br>
  > 🔑 **Keywords:** Robotic packing, World model, NewtonianVAE, Vision, Industrial objects <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Sequential \| Single-box industrial robotic packing \| Multiple regular manufactured objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: in-hand RGB vision and learned world state \| Stability: learned Newtonian dynamics representation \| Execution: robot-manipulator placement control <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: NewtonianVAE world-model-based control \| Data: physical multi-object box-packing trials \| Objective: improve placement accuracy and task success <br>

- ❤️ **3D dynamic heterogeneous robotic palletization problem** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.ejor.2024.02.007-blue.svg)](https://doi.org/10.1016/j.ejor.2024.02.007)
  > 👨‍🔬 **Authors:** Wenbin Zhu; Ying Fu; You Zhou | 📅 **Year:** 2024 | 🏢 **Venue:** European Journal of Operational Research <br>
  > 🔑 **Keywords:** 3D bin packing, Dynamic packing, Palletization, Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Dynamic \| Pallet loading \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: robot manipulator, gripper constraints, collision/reachability constraints, palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: paper-specific optimization/learning method \| Data: paper-reported benchmark/synthetic instances \| Objective: optimize paper-defined packing performance <br>

- ❤️ **A Dynamic Multi-modal deep Reinforcement Learning framework for 3D Bin Packing Problem** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.knosys.2024.111990-blue.svg)](https://doi.org/10.1016/j.knosys.2024.111990)
  > 👨‍🔬 **Authors:** Anhao Zhao; Tianrui Li; Liangcai Lin | 📅 **Year:** 2024 | 🏢 **Venue:** Knowledge-Based Systems <br>
  > 🔑 **Keywords:** 3D bin packing, Dynamic packing, Deep reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/dynamic \| Single variable-height 3D container \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: dynamic box features plus gradient height map \| Action: choose box and orientation; placement is heuristic \| Reward: stepwise reduction in bin gap ratio <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: height map \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: dynamic multimodal deep reinforcement learning with heuristic placement \| Data: generated cuboid instances \| Objective: minimize gap ratio and packing height <br>

- ❤️ **An efficient DRL model for online 3D bin packing combining object rearrangement and stable placement** [![arXiv](https://img.shields.io/badge/arXiv-2408.09694-b31b1b.svg)](https://arxiv.org/abs/2408.09694)
  > 👨‍🔬 **Authors:** P Zhou, Z Gao, C Li, NY Chong | 📅 **Year:** 2024 | 🏢 **Venue:** IEEE International Conference on Automation Science and Engineering <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Dynamic packing, Deep reinforcement learning, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container packing with rearrangement \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bin height map, incoming object, and rearrangeable placed objects \| Action: direct placement or stable rearrangement \| Reward: compactness/utilization plus placement stability <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: deep reinforcement learning for direct placement/rearrangement \| Data: generated streams and benchmark comparisons \| Objective: maximize utilization with stable placements <br>

- ❤️ **Dynamics simulation-based packing of irregular 3D objects** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cag.2024.103996-blue.svg)](https://doi.org/10.1016/j.cag.2024.103996)
  > 👨‍🔬 **Authors:** Qiubing Zhuang; Zhonggui Chen; Keyu He; Juan Cao; Wenping Wang | 📅 **Year:** 2024 | 🏢 **Venue:** Computers & Graphics <br>
  > 🔑 **Keywords:** 3D packing, Irregular objects, Rigid-body dynamics, Simulation <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container/open-dimension 3D packing \| Irregular rigid objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: robot manipulator, collision/reachability constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: rigid-body dynamics simulation and search \| Data: simulated irregular-shape instances \| Objective: maximize utilization / minimize required volume <br>

- ❤️ **Efficient Reinforcement Learning of Task Planners for Robotic Palletization Through Iterative Action Masking Learning** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Flra.2024.3440731-blue.svg)](https://doi.org/10.1109/lra.2024.3440731)
  > 👨‍🔬 **Authors:** Zheng Wu; Yichuan Li; Wei Zhan; Changliu Liu; Yun-Hui Liu; Masayoshi Tomizuka | 📅 **Year:** 2024 | 🏢 **Venue:** IEEE Robotics and Automation Letters <br>
  > 🔑 **Keywords:** Palletization, Deep reinforcement learning, Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Robotic pallet loading \| Rigid cuboid boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: pallet configuration and available boxes \| Action: select a box and masked placement pose \| Reward: utilization and stability, with invalid actions masked <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: collision/reachability constraints, palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: deep reinforcement learning \| Data: paper-reported benchmark/synthetic instances \| Objective: optimize paper-defined packing performance <br>

- ❤️ **Enhancing Robotics Online 3D Bin Packing: A Comparative Study of Conventional Heuristic and Deep Reinforcement Learning Approaches** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Fcase59546.2024.10711723-blue.svg)](https://doi.org/10.1109/case59546.2024.10711723)
  > 👨‍🔬 **Authors:** Heng Xiong; Kai Ding; Wan Ding; Xuchong Qiu; Klaus Janschek; Jianfeng Xu | 📅 **Year:** 2024 | 🏢 **Venue:** 2024 IEEE 20th International Conference on Automation Science and Engineering (CASE) <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Offline packing, Deep reinforcement learning, Robotic packing, Vision <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container robotic packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bin height map and incoming box \| Action: choose placement position/orientation \| Reward: packed-volume / utilization return used by the evaluated DRL baseline <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: comparative evaluation of conventional heuristics and deep reinforcement learning \| Data: simulated streams and robot-relevant cases \| Objective: maximize utilization <br>

- ❤️ **FamiPacking: a diffusion model for guiding 3D bin packing** [![DOI](https://img.shields.io/badge/DOI-10.1049%2Ficp.2023.3199-blue.svg)](https://doi.org/10.1049/icp.2023.3199)
  > 👨‍🔬 **Authors:** C. -J. Peng; L. Lo; H. Xie; C. -C. Chiu; W. -H. Hsueh; S. -C. Huang; H. -H. Shuai; W. -H. Cheng | 📅 **Year:** 2024 | 🏢 **Venue:** IET Conference Proceedings <br>
  > 🔑 **Keywords:** 3D bin packing, Diffusion model, Offline packing, Industrial logistics <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: diffusion-based packing guidance \| Data: FamilyMart industrial orders plus generated instances \| Objective: reduce bin/material use and increase utilization <br>

- ❤️ **GOPT: Generalizable Online 3D Bin Packing via Transformer-Based Deep Reinforcement Learning** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Flra.2024.3468161-blue.svg)](https://doi.org/10.1109/lra.2024.3468161) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/Xiong5Heng/GOPT)
  > 👨‍🔬 **Authors:** Heng Xiong; Changrong Guo; Jian Peng; Kai Ding; Wenjie Chen; Xuchong Qiu; Long Bai; Jianfeng Xu | 📅 **Year:** 2024 | 🏢 **Venue:** IEEE Robotics and Automation Letters <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Deep reinforcement learning, Transformer, Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container 3D packing across varying bin dimensions \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: current item plus candidate subspaces from the Placement Generator \| Action: select a candidate placement/orientation \| Reward: packed-volume / space-utilization return <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: RGB-D/depth, vision \| Stability: geometric non-overlap only \| Execution: robot manipulator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: placement generator plus Transformer deep-reinforcement-learning policy \| Data: generated in- and out-of-distribution bins plus robot deployment \| Objective: maximize utilization and cross-bin generalization <br>

- ❤️ **Heuristics Integrated Deep Reinforcement Learning for Online 3D Bin Packing** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ftase.2023.3235742-blue.svg)](https://doi.org/10.1109/tase.2023.3235742)
  > 👨‍🔬 **Authors:** Shuo Yang; Shuai Song; Shilei Chu; Ran Song; Jiyu Cheng; Yibin Li; Wei Zhang | 📅 **Year:** 2024 | 🏢 **Venue:** IEEE Transactions on Automation Science and Engineering <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Irregular objects, Deep reinforcement learning, Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container robotic packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bin height map and current item \| Action: choose among heuristic-generated placement candidates \| Reward: incremental packed volume / final utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: deep reinforcement learning integrating physics, packing, and unpacking heuristics \| Data: simulated episodes and a real logistics system \| Objective: maximize utilization and reliable completion <br>

- ❤️ **Key point is key in resolving the offline three-dimensional bin packing problem** [![OpenReview](https://img.shields.io/badge/OpenReview-Paper-8E44AD.svg)](https://openreview.net/forum?id=4Y4hPWUppN)
  > 👨‍🔬 **Authors:** X Tian, H Qi | 📅 **Year:** 2024 | 🏢 **Venue:** OpenReview <br>
  > 🔑 **Keywords:** Offline packing, 3D bin packing, Key points, Action masking, Deep reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container/open-height 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: dimensions of unpacked boxes plus current packed-bin layout \| Action: choose orientation and a masked key-point placement \| Reward: final loading rate / utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: key-point action masking integrated with existing reinforcement-learning solvers \| Data: generated offline cuboid instances \| Objective: improve loading rate, convergence speed, and scalable box count <br>

- ❤️ **Online computation with untrusted advice** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.jcss.2024.103545-blue.svg)](https://doi.org/10.1016/j.jcss.2024.103545)
  > 👨‍🔬 **Authors:** Spyros Angelopoulos; Christoph Dürr; Shendan Jin; Shahin Kamali; Marc Renault | 📅 **Year:** 2024 | 🏢 **Venue:** Journal of Computer and System Sciences <br>
  > 🔑 **Keywords:** Online algorithms, Untrusted advice, Robustness, 1D bin packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online with advice \| Multi-bin one-dimensional packing \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: advice-augmented online algorithms with consistency/robustness guarantees \| Data: adversarial theoretical sequences \| Objective: minimize bin count despite untrusted predictions <br>

- ❤️ **Online Three-Dimensional Bin Packing: A DRL Algorithm with the Buffer Zone** [![DOI](https://img.shields.io/badge/DOI-10.2478%2Ffcds-2024-0005-blue.svg)](https://doi.org/10.2478/fcds-2024-0005)
  > 👨‍🔬 **Authors:** Jiawei Zhang; Tianping Shuai | 📅 **Year:** 2024 | 🏢 **Venue:** Foundations of Computing and Decision Sciences <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Deep reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online with buffer \| Single-container sequential 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bin grid/height state, current item, and buffer state \| Action: choose a front-left-bottom placement or buffer the item \| Reward: item-volume gain minus normalized wasted space <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: buffer-zone deep reinforcement learning with front-left-bottom placement \| Data: generated online streams \| Objective: maximize packed volume and reduce wasted space <br>

- ❤️ **Pattern Based Learning and Optimisation Through Pricing for Bin Packing Problem** [![DOI](https://img.shields.io/badge/DOI-10.2139%2Fssrn.4822673-blue.svg)](https://doi.org/10.2139/ssrn.4822673)
  > 👨‍🔬 **Authors:** Huayan Zhang; Ruibin Bai; Tie-Yan Liu; Jiawei Li; Bingchen Lin; Jianfeng Ren | 📅 **Year:** 2024 | 🏢 **Venue:** arXiv preprint arXiv:2409.04456 <br>
  > 🔑 **Keywords:** Online packing, Pattern learning, Column generation, Pricing, Scalar items <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online stochastic \| Multi-bin one-dimensional packing \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: learned packing patterns and dual-pricing optimization \| Data: generated/distributional item streams \| Objective: minimize bin count and expected packing cost <br>

- ❤️ **Simulation-Assisted Learning for Efficient Bin-Packing of Deformable Packages in a Bimanual Robotic Cell** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Firos58592.2024.10802246-blue.svg)](https://doi.org/10.1109/iros58592.2024.10802246) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/RROS-Lab/IROS2024-Bin-Packing)
  > 👨‍🔬 **Authors:** Omey M. Manyar; Hantao Ye; Meghana Sagare; Siddharth Mayya; Fan Wang; Satyandra K. Gupta | 📅 **Year:** 2024 | 🏢 **Venue:** 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) <br>
  > 🔑 **Keywords:** Robotic packing, Deformable packages, Bimanual manipulation, Supervised learning, Simulation <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-bin bimanual robotic packing \| Deformable packages <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (supervised packing-score prediction plus online numerical optimization, not RL) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: package/bin geometry and predicted packing score \| Stability: deformable-body simulation \| Execution: bimanual robotic cell <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: supervised packing-score prediction plus basin-hopping online optimization \| Data: simulated training data and real bimanual trials \| Objective: maximize packing score and execution efficiency <br>

- ❤️ **Solving Offline 3D Bin Packing Problem with Large-sized Bin via Two-stage Deep Reinforcement Learning** [![DOI](https://img.shields.io/badge/DOI-10.65109%2Fdgdy9293-blue.svg)](https://doi.org/10.65109/dgdy9293)
  > 👨‍🔬 **Authors:** Hao Yin; Fan Chen; Hongjie He | 📅 **Year:** 2024 | 🏢 **Venue:** International Joint Conference on Autonomous Agents and Multiagent Systems <br>
  > 🔑 **Keywords:** 3D bin packing, Offline packing, Deep reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single large variable-height 3D container \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: remaining-box features plus current spatial/bin state \| Action: jointly choose item index and orientation, then a BCP placement \| Reward: reduction in packing height / increase in utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: two-stage deep reinforcement learning plus bidirectional cooperative packing \| Data: generated offline instances \| Objective: maximize space utilization <br>

- ❤️ **RoboPack: Learning Tactile-Informed Dynamics Models for Dense Packing** [![arXiv](https://img.shields.io/badge/arXiv-2407.01418-b31b1b.svg)](https://arxiv.org/abs/2407.01418)
  > 👨‍🔬 **Authors:** Bo Ai; Stephen Tian; Haochen Shi; Yixuan Wang; Cheston Tan; Yunzhu Li; Jiajun Wu | 📅 **Year:** 2024 | 🏢 **Venue:** Robotics: Science and Systems (RSS) <br>
  > 🔑 **Keywords:** Robotic packing, Dense packing, Tactile sensing, Dynamics model, Model-predictive control, Deformable objects <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Sequential \| Dense packing of items into a nearly full tray, including creating space through deformation \| Rigid and deformable objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (learned tactile-informed dynamics model with model-predictive control, not RL) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: RGB-D vision plus a compliant Soft-Bubble tactile sensor; keypoint-particle scene representation \| Stability: learned dynamics over multi-object contact, including indirectly interacted objects \| Execution: real robot arm performing non-prehensile insertion under tactile feedback <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: recurrent graph neural network estimating latent physics vectors from visuo-tactile interaction histories, used for dynamics prediction and MPC planning \| Data: about 30 minutes of real-world interaction data per task \| Objective: identify feasible insertion locations and complete dense packing without excessive force (12/15 seen-object and 10/15 unseen-object success) <br>

- ❤️ **3D Vision robot online packing platform for deep reinforcement learning** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.rcim.2024.102941-blue.svg)](https://doi.org/10.1016/j.rcim.2024.102941)
  > 👨‍🔬 **Authors:** Xingyu Mu; Quanmin Kan; Yong Jiang; Chao Chang; Xincheng Tian; Lelai Zhou; Yongguo Zhao | 📅 **Year:** 2025 | 🏢 **Venue:** Robotics and Computer-Integrated Manufacturing <br>
  > 🔑 **Keywords:** Online packing, Robotic palletization, 3D vision, Deep reinforcement learning, Cuboids <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Robotic mixed-case pallet loading \| Rigid cuboid boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: 3D-vision item dimensions plus current pallet packing-configuration tree \| Action: choose a feasible placement node and orientation \| Reward: placed-item volume normalized by pallet capacity <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: vision \| Stability: explicit stability checks \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: 3D-vision packing-configuration tree with ACKTR policy learning \| Data: simulated and physical palletizing trials \| Objective: maximize pallet utilization <br>

- ❤️ **A deep reinforcement learning approach for online and concurrent 3D bin packing optimisation with bin replacement strategies** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.compind.2024.104202-blue.svg)](https://doi.org/10.1016/j.compind.2024.104202)
  > 👨‍🔬 **Authors:** Y.P. Tsang; D.Y. Mo; K.T. Chung; C.K.M. Lee | 📅 **Year:** 2025 | 🏢 **Venue:** Computers in Industry <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Dynamic packing, Palletization, Deep reinforcement learning, Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online/concurrent \| Multi-bin 3D packing with active-bin replacement \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: active-bin height maps, current item, and concurrent/buffer state \| Action: choose placement/orientation and when to replace the active bin \| Reward: utilization balanced against bin-replacement cost <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: deep reinforcement learning with concurrency/buffer and bin-replacement decisions \| Data: discrete-event simulation and generated streams \| Objective: balance utilization against replacement cost <br>

- ❤️ **ASAP: Learning Generalizable Online Bin Packing via Adaptive Selection After Proposal** [![arXiv](https://img.shields.io/badge/arXiv-2501.17377-b31b1b.svg)](https://arxiv.org/abs/2501.17377)
  > 👨‍🔬 **Authors:** Han Fang Joint Institute of Michigan Shanghai Jiao Tong University Shanghai, China han.fang@sjtu.edu.cn &Paul Weng Duke Kunshan University Jiangsu, China paul.weng@dukekunshan.edu.cn &Yutong Ban Joint Institute of Michigan Shanghai Jiao Tong University Shanghai, China yban@sjtu.edu.cn | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2501.17377 <br>
  > 🔑 **Keywords:** Online packing, 3D bin packing, Deep reinforcement learning, Meta-learning, Adaptation <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container sequential packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: current item plus current bin/candidate-action state \| Action: proposal policy suggests placements; selection policy chooses one \| Reward: terminal space utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: proposal/selection policies with pre-training, post-training, and meta-learning \| Data: generated in- and out-of-distribution discrete/continuous instances \| Objective: maximize utilization with rapid test-distribution adaptation <br>

- ❤️ **Bin Packing Optimization via Deep Reinforcement Learning** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Flra.2025.3534070-blue.svg)](https://doi.org/10.1109/lra.2025.3534070)
  > 👨‍🔬 **Authors:** Baoying Wang; Zhaohui Lin; Weijie Kong; Huixu Dong | 📅 **Year:** 2025 | 🏢 **Venue:** IEEE Robotics and Automation Letters <br>
  > 🔑 **Keywords:** 2D packing, 3D bin packing, Deep reinforcement learning, Robotic packing, Height map <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin 2D/3D packing with robotic validation \| Regular rectangles and cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: current bin height map plus remaining/current item features \| Action: choose item and placement \| Reward: utilization / bin-cost objective <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: height map \| Stability: geometric non-overlap only \| Execution: gripper constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: pointer-network actor-critic for order plus height-map placement \| Data: generated instances and a robot demonstration \| Objective: maximize compactness and minimize bin count <br>

- ❤️ **Collaborate sim and real: Robot Bin Packing Learning in Real-world and Physical Engine** [![arXiv](https://img.shields.io/badge/arXiv-2511.19932-b31b1b.svg)](https://arxiv.org/abs/2511.19932)
  > 👨‍🔬 **Authors:** Lidi Zhang1\equalcontrib, Han Wu2\equalcontrib, Liyu Zhang3, Ruofeng Liu4, Haotian Wang2, Chao Li3, Desheng Zhang5, Yunhuai Liu1, Tian He2 | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2511.19932 <br>
  > 🔑 **Keywords:** Online packing, Robotic packing, Sim-to-real, Physics engine, Deep reinforcement learning, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container robot packing with sim-to-real training \| Rigid packages with physical properties <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: item physical properties, current container packing, and feasible EMS candidates \| Action: choose a robot-feasible placement pose \| Reward: stepwise placed-item volume; terminal failure receives zero <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: item geometry and randomized physical properties \| Stability: gravity-driven physics simulation and collapse feedback \| Execution: real logistics robot with online feedback <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: physics-engine reinforcement learning with domain randomization and real-world fine-tuning \| Data: simulated episodes and production feedback \| Objective: reduce packing collapse while maintaining utilization <br>

- ❤️ **Container loading planning using reinforcement learning based on curriculum learning** [![DOI](https://img.shields.io/badge/DOI-10.1093%2Fjcde%2Fqwaf070-blue.svg)](https://doi.org/10.1093/jcde/qwaf070)
  > 👨‍🔬 **Authors:** Youngsu Kim; Kyungho Lee; Youngsoo Han; Cheolho Ryu | 📅 **Year:** 2025 | 🏢 **Venue:** Journal of Computational Design and Engineering <br>
  > 🔑 **Keywords:** Container stowage, Vessel bay planning, Deep reinforcement learning, Curriculum learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Vessel-bay container stowage, not packing inside a container \| ISO containers with weight and port-of-discharge attributes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bay-slot grid with loadability, weight, port-of-discharge, and selected-container features \| Action: move, select, or drop a container \| Reward: drop-only reward subject to loading, balance, and unloading constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known bay slots and container attributes \| Stability: vessel balance and loadability constraints \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: PPO reinforcement learning with curriculum learning \| Data: generated vessel-bay scenarios \| Objective: produce adaptable loading plans satisfying balance and unloading constraints <br>

- ❤️ **GFPack++: Attention-Driven Gradient Fields for Optimizing 2D Irregular Packing** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ficcv51701.2025.01674-blue.svg)](https://doi.org/10.1109/iccv51701.2025.01674) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/TimHsue/GFPack-pp)
  > 👨‍🔬 **Authors:** Tianyang Xue; Lin Lu; Yang Liu; Mingdong Wu; Hao Dong; Yanbin Zhang; Renmin Han; Baoquan Chen | 📅 **Year:** 2025 | 🏢 **Venue:** 2025 IEEE/CVF International Conference on Computer Vision (ICCV) <br>
  > 🔑 **Keywords:** 2D packing, Irregular objects <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container geometric packing \| Irregular/general 3D objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: collision/reachability constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: paper-specific optimization/learning method \| Data: paper-reported datasets/benchmark instances \| Objective: maximize utilization/minimize waste <br>

- ❤️ **HERB: Human-augmented efficient reinforcement learning for bin-packing** [![arXiv](https://img.shields.io/badge/arXiv-2504.16595-b31b1b.svg)](https://arxiv.org/abs/2504.16595) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/NunoDuarte/herb)
  > 👨‍🔬 **Authors:** G Perovic, NF Duarte, A Dehban, G Teixeira | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv <br>
  > 🔑 **Keywords:** Irregular objects, Deep reinforcement learning, Robotic packing, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Single-container 3D packing with human augmentation \| Irregular rigid objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bin height map plus top-down projection of the next irregular object \| Action: continuous planar position and rotation \| Reward: simple success, compactness, or compactness-plus-stability variants <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: height map, vision \| Stability: explicit stability checks \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: human-augmented continuous-control reinforcement learning \| Data: simulated irregular objects and human interventions \| Objective: improve sample efficiency, compactness, and stability <br>

- ❤️ **Improved Approximation Algorithms for Three-Dimensional Bin Packing** [![arXiv](https://img.shields.io/badge/arXiv-2503.08863-b31b1b.svg)](https://arxiv.org/abs/2503.08863)
  > 👨‍🔬 **Authors:** Debajyoti Kar; Arindam Khan; Malin Rau | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2503.08863 <br>
  > 🔑 **Keywords:** 3D bin packing, 3D strip packing, Minimum-volume bounding box, Approximation algorithms <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| 3D bin packing, strip packing, and minimum-volume bounding-box variants \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: polynomial-time approximation algorithms \| Data: theoretical instances \| Objective: improve approximation ratios for bin count, height, and bounding volume <br>

- ❤️ **Improved Approximation Algorithms for Three-Dimensional Knapsack** [![arXiv](https://img.shields.io/badge/arXiv-2503.19365-b31b1b.svg)](https://arxiv.org/abs/2503.19365)
  > 👨‍🔬 **Authors:** Jansen, Klaus; Kar, Debajyoti; Khan, Arindam; Sreenivas, K. V. N.; Tutas, Malte | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2503.19365 <br>
  > 🔑 **Keywords:** 3D bin packing, Cuboids, Approximation algorithms <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-bin three-dimensional knapsack \| Profit-weighted rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: container-structured approximation algorithms \| Data: theoretical instances \| Objective: maximize packed profit with improved approximation ratios <br>

- ❤️ **Learning packing-and-unpacking synergistic policy via LLM-guided DRL for robust online robotic packing** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.aei.2025.103572-blue.svg)](https://doi.org/10.1016/j.aei.2025.103572)
  > 👨‍🔬 **Authors:** Shuo Yang; Shuai Song; Ran Song; Jiyu Cheng; Yibin Li; Wei Zhang | 📅 **Year:** 2025 | 🏢 **Venue:** Advanced Engineering Informatics <br>
  > 🔑 **Keywords:** Online packing, Robotic packing, Deep reinforcement learning, Large language model, Packing and unpacking <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container robotic packing with corrective unpacking \| Rigid/general objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: bin height/voxel state plus incoming and placed-item features \| Action: pack or unpack/reorder items, including placement pose \| Reward: compactness and stability with invalid-action penalties <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: LLM-guided deep reinforcement learning for pack/unpack decisions \| Data: simulated and physical robot episodes \| Objective: improve compactness, stability, and robustness <br>

- ❤️ **LLM-Pack: Intuitive Grocery Handling for Logistics Applications** [![arXiv](https://img.shields.io/badge/arXiv-2503.08445-b31b1b.svg)](https://arxiv.org/abs/2503.08445)
  > 👨‍🔬 **Authors:** Blei, Yannik; Krawez, Michael; Jülg, Tobias; Krack, Pierre; Walter, Florian; Burgard, Wolfram | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2503.08445 <br>
  > 🔑 **Keywords:** Dynamic packing, Palletization, Robotic packing, Vision <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Dynamic \| Pallet loading \| Heterogeneous grocery objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: RGB-D/depth \| Stability: geometric non-overlap only \| Execution: robot manipulator, palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: paper-specific optimization/learning method \| Data: paper-reported datasets/benchmark instances \| Objective: optimize paper-defined packing performance <br>

- ❤️ **One4Many-StablePacker: An Efficient Deep Reinforcement Learning Framework for the 3D Bin Packing Problem** [![arXiv](https://img.shields.io/badge/arXiv-2510.10057-b31b1b.svg)](https://arxiv.org/abs/2510.10057)
  > 👨‍🔬 **Authors:** Lei Gao1, Shihong Huang2, Shengjie Wang2, Hong Ma2, Feng Zhang1, Hengda Bao1, Qichang Chen1, Weihua Zhou3 | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2510.10057 <br>
  > 🔑 **Keywords:** 3D bin packing, Offline packing, Dynamic packing, Deep reinforcement learning, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container 3D packing across varied item distributions \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: current item plus height-map/empty-space representation \| Action: choose a stable placement candidate and orientation \| Reward: compactness/utilization with stability and feasibility terms <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: general-purpose stable-packing deep reinforcement learning \| Data: multiple generated and real-world distributions \| Objective: maximize utilization while preserving stability <br>

- ❤️ **Online 3D Bin Packing with Fast Stability Validation and Safe Rearrangement Planning** [![DOI](https://img.shields.io/badge/DOI-10.2139%2Fssrn.5669305-blue.svg)](https://doi.org/10.2139/ssrn.5669305)
  > 👨‍🔬 **Authors:** ZIYAN GAO; Lijun Wang; Yuntao Kong; Nak Young Chong | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2507.09123 <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-bin sequential packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: collision/reachability constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: heuristic search \| Data: real-world/industrial data with paper-reported evaluation \| Objective: maximize utilization/minimize waste, maintain stability <br>

- ❤️ **Online Bin Packing with Item Size Estimates** [![arXiv](https://img.shields.io/badge/arXiv-2505.09321-b31b1b.svg)](https://arxiv.org/abs/2505.09321)
  > 👨‍🔬 **Authors:** Gehnen, Matthias; Usdenski, Andreas | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2505.09321 <br>
  > 🔑 **Keywords:** Online packing, Item-size estimates, Competitive analysis, Scalar items <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online with size estimates \| Multi-bin one-dimensional packing \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: prediction-augmented online algorithms with competitive guarantees \| Data: theoretical/adversarial sequences with estimates \| Objective: minimize bin count <br>

- ❤️ **OPA-Pack: Object-Property-Aware Robotic Bin Packing** [![arXiv](https://img.shields.io/badge/arXiv-2505.13339-b31b1b.svg)](https://arxiv.org/abs/2505.13339)
  > 👨‍🔬 **Authors:** Jia-Hui Pan, Yeok Tatt Cheah, Zhengzhe Liu, Ka-Hei Hui, Xiaojie Gao, Pheng-Ann Heng, Yun-Hui Liu, Chi-Wing Fu | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2505.13339 <br>
  > 🔑 **Keywords:** Robotic packing, Object properties, Deep reinforcement learning, Everyday objects, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container robotic packing with compatibility/pressure constraints \| Heterogeneous everyday objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: height map \| Stability: explicit stability checks \| Execution: robot manipulator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: object-property-aware deep Q-learning with retrieval support \| Data: simulated and physical everyday-object sets \| Objective: compact packing while separating incompatible items and limiting pressure <br>

- ❤️ **Physical question, virtual answer: Optimized real-time physical simulations and physics-informed learning approaches for cargo loading stability** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.orp.2025.100329-blue.svg)](https://doi.org/10.1016/j.orp.2025.100329)
  > 👨‍🔬 **Authors:** Philipp Gabriel Mazur; Johannes Werner Melsbach; Detlef Schoder | 📅 **Year:** 2025 | 🏢 **Venue:** Operations Research Perspectives <br>
  > 🔑 **Keywords:** Cargo stability, Pallet loading, Physics simulation, Physics-informed learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Evaluation/prediction \| Cargo/pallet loading stability, not a packing policy \| Rigid cuboid cargo <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: cargo geometry and physical parameters \| Stability: real-time rigid-body simulation and physics-informed recurrent prediction \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: calibrated real-time physics engine plus physics-informed recurrent model \| Data: simulated and paper-reported cargo configurations \| Objective: predict dynamic loading stability accurately and quickly <br>

- ❤️ **Physics-Aware Robotic Palletization With Online Masking Inference** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ficra55743.2025.11128204-blue.svg)](https://doi.org/10.1109/icra55743.2025.11128204) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/tianqi-zh/palletization)
  > 👨‍🔬 **Authors:** Tianqi Zhang; Zheng Wu; Yuxin Chen; Yixiao Wang; Boyuan Liang; Scott Moura; Masayoshi Tomizuka; Mingyu Ding; Wei Zhan | 📅 **Year:** 2025 | 🏢 **Venue:** 2025 IEEE International Conference on Robotics and Automation (ICRA) <br>
  > 🔑 **Keywords:** Online packing, Robotic palletization, Deep reinforcement learning, Action masking, Physics, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Robotic pallet loading \| Cuboid boxes with size, density, and rigidity attributes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: pallet configuration plus selected-box size, density, and rigidity \| Action: choose a placement from the learned stability mask \| Reward: stable placed-volume fraction <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: physics/dynamics simulation, explicit stability checks \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: reinforcement-learning task planner with online-learned action masks \| Data: simulated training and real robotic palletizer trials \| Objective: maximize stable packed volume across varying box properties <br>

- ❤️ **RoboPacker: An Autonomous Robotic Packing System for General Objects** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Ftase.2025.3633306-blue.svg)](https://doi.org/10.1109/tase.2025.3633306)
  > 👨‍🔬 **Authors:** Zhenyu Wu; Ziwei Wang; Sichao Huang; Zhan Liu; Xiuwei Xu; Haibin Yan; Jiwen Lu | 📅 **Year:** 2025 | 🏢 **Venue:** IEEE Transactions on Automation Science and Engineering <br>
  > 🔑 **Keywords:** Robotic packing, General objects, Point clouds, Hierarchical reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-shipping-box robotic packing \| General/irregular rigid objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: object point cloud/shape features plus bin height map \| Action: choose object and placement pose \| Reward: packing utilization and successful robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: point cloud \| Stability: geometric non-overlap only \| Execution: robot manipulator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: point-cloud hierarchical reinforcement learning and robot execution pipeline \| Data: simulated training sets and physical object trials \| Objective: maximize utilization and successful execution <br>

- ❤️ **Robotic Tight Packaging Using a Hybrid Gripper with Variable Stiffness** [![DOI](https://img.shields.io/badge/DOI-10.1007%2F978-3-031-72059-8_27-blue.svg)](https://doi.org/10.1007/978-3-031-72059-8_27)
  > 👨‍🔬 **Authors:** Michele Moroni; Ana Elvira Huezo Martin; Leonard Klüpfel; Ashok M. Sundaram; Werner Friedl; Francesco Braghin; Máximo A. Roa | 📅 **Year:** 2025 | 🏢 **Venue:** Lecture Notes in Computer Science <br>
  > 🔑 **Keywords:** Robotic packing, Tight packaging, Compliant manipulation, Variable-stiffness gripper <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Execution study \| Tight insertion into a known single-container arrangement \| Regular rigid items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known target poses and item geometry \| Stability: passive compliance limits error propagation \| Execution: variable-stiffness hybrid gripper on a real robot <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: compliant insertion strategy and full robotic packaging pipeline \| Data: real-robot tight-packaging trials \| Objective: improve insertion success and robustness at minimum clearance <br>

- ❤️ **The semi-online robotic pallet loading problem** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cor.2024.106889-blue.svg)](https://doi.org/10.1016/j.cor.2024.106889)
  > 👨‍🔬 **Authors:** Shaowen Yao; Tai Zhang; Hao Zhang; Jian Qiu; Jiewu Leng; Qiang Liu; Lijun Wei | 📅 **Year:** 2025 | 🏢 **Venue:** Computers & Operations Research <br>
  > 🔑 **Keywords:** Online packing, Palletization, Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Semi-online \| Multi-pallet loading with a finite buffer \| Rigid cuboid boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: robot manipulator, palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: buffer-aware greedy pallet-loading heuristics \| Data: generated semi-online instances \| Objective: minimize pallet count and improve utilization <br>

- ❤️ **Optimizing 2D+1 Packing in Constrained Environments Using Deep Reinforcement Learning** [![arXiv](https://img.shields.io/badge/arXiv-2503.17573-b31b1b.svg)](https://arxiv.org/abs/2503.17573)
  > 👨‍🔬 **Authors:** Victor Ulisses Pugliese; Oséias F. de A. Ferreira; Fabio A. Faria | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2503.17573 <br>
  > 🔑 **Keywords:** 2D packing, 2D+1 packing, Deep reinforcement learning, PPO, A2C, Autoclave packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Two-board 2D+1 packing with a height constraint (aerospace composite autoclave loading) \| Rectangles <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: occupancy matrices of two boards plus remaining piece-type counts \| Action: multidiscrete choice of placement coordinates, target board, and piece type \| Reward: spatial-variant reward combining coverage and height utilization, with penalties for invalid actions <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: PPO and A2C with a multidiscrete action space in an OpenAI Gym simulator, compared against a MaxRect-BL heuristic baseline \| Data: generated piece/board instances inspired by composite autoclave batches \| Objective: maximize board coverage under height constraints <br>

- ❤️ **A Hybrid Approach for the Container Loading Problem for Enhancing the Dynamic Stability Representation** [![DOI](https://img.shields.io/badge/DOI-10.3390%2Fmath13050869-blue.svg)](https://doi.org/10.3390/math13050869) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.3390%2Fmath13050869)](https://scholar.google.com/scholar?q=A%20Hybrid%20Approach%20for%20the%20Container%20Loading%20Problem%20for%20Enhancing%20the%20Dynamic%20Stability%20Representation)
  > 👨‍🔬 **Authors:** A. M. Montes-Franco; J. C. Martinez-Franco; A. Tabares; D. Álvarez-Martínez | 📅 **Year:** 2025 | 🏢 **Venue:** Mathematics <br>
  > 🔑 **Keywords:** Container loading, Dynamic packing, Stability, GRASP, Metaheuristic <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container loading with dynamic (transport-induced) stability requirements \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: mechanical model of forces and accelerations predicting support loss, overturning, and cargo-damaging velocities, replacing physics-engine simulation \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: GRASP metaheuristic with adaptive self-calibration of the restricted candidate list plus stability-guided local search \| Data: standard container-loading instances with a factorial experiment \| Objective: maximize occupied volume while guaranteeing a target dynamic-stability level <br>

- ❤️ **Learning Three-Dimensional Bin Packing with Adjustable-Order Semi-Online Setting** [![DOI](https://img.shields.io/badge/DOI-10.1109%2FICRA55743.2025.11127655-blue.svg)](https://doi.org/10.1109/ICRA55743.2025.11127655) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1109%2FICRA55743.2025.11127655)](https://scholar.google.com/scholar?q=Learning%20Three-Dimensional%20Bin%20Packing%20with%20Adjustable-Order%20Semi-Online%20Setting)
  > 👨‍🔬 **Authors:** Hao Yin; Chenxi Zhang; Fan Chen; Hongjie He | 📅 **Year:** 2025 | 🏢 **Venue:** 2025 IEEE International Conference on Robotics and Automation (ICRA) <br>
  > 🔑 **Keywords:** 3D bin packing, Semi-online packing, Adjustable order, Deep reinforcement learning, Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Semi-online \| Single-container 3D packing with multiple observable items and selectable packing order \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: current bin configuration plus a variable-size set of observable upcoming items \| Action: select which observed item to pack next (adjusting the packing order) and its placement \| Reward: guided bottom-up packing reward that frees space for robotic-arm motion, plus utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: paper-defined placement feasibility \| Execution: robotic arm motion-obstruction constraints explicitly modeled <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: reinforcement learning with a policy network adaptive to a variable number of observed items \| Data: generated semi-online packing instances \| Objective: maximize space utilization while keeping the packing order adjustable and robot-executable <br>

- ❤️ **Stow: Robotic Packing of Items into Fabric Pods** [![arXiv](https://img.shields.io/badge/arXiv-2505.04572-b31b1b.svg)](https://arxiv.org/abs/2505.04572)
  > 👨‍🔬 **Authors:** Nicolas Hudson; Josh Hooks; Rahul Warrier; Curt Salisbury; Ross Hartley; Kislay Kumar; Bhavana Chandrashekhar; Paul Birkmeyer; Bosch Tang; Matt Frost; Shantanu Thakar; Tony Piaskowy; Petter Nilsson; Josh Petersen; Neel Doshi; Alan Slatter; Ankit Bhatia; Cassie Meeker; Yuechuan Xue; Dylan Cox; Alex Kyriazis; Bai Lou; Nadeem Hasan; Asif Rana; Nikhil Chacko; Ruinian Xu; Siamak Faal; Esi Seraj; Mudit Agrawal; Kevin Jamieson; Alessio Bisagni; Valerie Samzun; Christine Fuller; Alex Keklak; Alex Frenkel; Lillian Ratliff; Aaron Parness | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2505.04572 <br>
  > 🔑 **Keywords:** Robotic packing, Stowing, Compliant manipulation, Dense packing, Warehouse automation, 3D perception <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Robotic stowing of diverse inventory items into partially filled fabric-pod bins \| Rigid and deformable retail items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method; learned perception with risk-aware bin-item matching and behavior selection) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: stereo-camera arrays with learned depth/segmentation invariant to occluding elastic bands, plus kinesthetic and force/torque feedback \| Stability: space estimation with in-bin reconfiguration behaviors (sweep, flip, stack) \| Execution: production robotic workcells (gantry plus 6-DoF arm with paddle-conveyor end-of-arm tool), more than 500,000 real stows <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: compliant manipulation system combining space estimation, risk- and rate-aware bin-item matching, and a discrete behavior set with force-controlled insertion \| Data: over 500,000 production stows in an operating e-commerce fulfillment center \| Objective: human-level packing density and stow rate (about 300 units/hour) at low defect rate <br>

- ❤️ **NeSyPack: A Neuro-Symbolic Framework for Bimanual Logistics Packing** [![arXiv](https://img.shields.io/badge/arXiv-2506.06567-b31b1b.svg)](https://arxiv.org/abs/2506.06567)
  > 👨‍🔬 **Authors:** Bowei Li; Peiqi Yu; Zhenran Tang; Han Zhou; Yifan Sun; Ruixuan Liu; Changliu Liu | 📅 **Year:** 2025 | 🏢 **Venue:** RSS 2025 Workshop on Benchmarking Robot Manipulation / arXiv preprint arXiv:2506.06567 <br>
  > 🔑 **Keywords:** Robotic packing, Bimanual manipulation, Neuro-symbolic, Deformable objects, Logistics packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Sequential \| Bimanual logistics packing: pick items from storage bins, pack a shipping box, and enclose it \| Rigid and deformable objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method; demonstration-learned skills organized by a symbolic skill graph) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: RGB-D vision with learned perceptive features (e.g., deformable-object edges) \| Stability: skill-level execution and failure-recovery policies \| Execution: bimanual robot; First Prize in the ICRA 2025 What Bimanuals Can Do (WBCD) competition <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: hierarchical task reasoning over a symbolic skill graph that selects learned perception models, skills, and control strategies \| Data: human demonstrations and competition packing tasks \| Objective: generalizable, data-efficient, and reliable execution of full packing workflows <br>

- ❤️ **Static stability versus packing efficiency in online three-dimensional packing problems: A new approach and a computational study** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cor.2025.107005-blue.svg)](https://doi.org/10.1016/j.cor.2025.107005) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1016%2Fj.cor.2025.107005)](https://scholar.google.com/scholar?q=Static%20stability%20versus%20packing%20efficiency%20in%20online%20three-dimensional%20packing%20problems%3A%20A%20new%20approach%20and%20a%20computational%20study)
  > 👨‍🔬 **Authors:** Sara Ali; António G. Ramos; José Fernando Oliveira | 📅 **Year:** 2025 | 🏢 **Venue:** Computers & Operations Research <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Stability, Heuristics <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Sequential 3D packing with immediate, irrevocable decisions and no lookahead \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: four embedded static-stability constraints (full-base support, partial-base support, center-of-gravity polygon support, and a novel partial-base polygon support), benchmarked against static mechanical equilibrium conditions \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: computational study embedding alternative stability constraints into online packing heuristics \| Data: real-world instances with paper-reported evaluation \| Objective: characterize the trade-off between bin count and cargo stability for real-time online packing <br>

- ❤️ **A Hierarchical Bin Packing Framework with Dual Manipulators via Heuristic Search and Deep Reinforcement Learning** [![arXiv](https://img.shields.io/badge/arXiv-2506.01628-b31b1b.svg)](https://arxiv.org/abs/2506.01628)
  > 👨‍🔬 **Authors:** Beomjoon Lee; Changjoo Nam | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2506.01628 <br>
  > 🔑 **Keywords:** 2D packing, Dual manipulators, Deep reinforcement learning, Heuristic search, Rearrangement <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online/semi-online \| Dual-manipulator packing with packing, unpacking, and repacking \| Rectangular objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: padded binary bin occupancy and the rotated dimensions of the active item \| Action: choose the precise top-left placement location \| Reward: compactness and occupancy-adjacency score for the resulting layout <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item dimensions and discretized bin occupancy \| Stability: geometric non-overlap only \| Execution: dual-manipulator simulation with motion-planning and reachability checks <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: low-level placement RL combined with high-level depth-first/selective beam search over sequence, orientation, buffering, and rearrangement \| Data: generated packing tasks and robot-simulation evaluation \| Objective: improve utilization and recover from poor online decisions while coordinating two manipulators <br>

- ❤️ **A Large Neighborhood Search Algorithm Based on Q-Learning for Multi-Container Loading Problem** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.eswa.2025.126429-blue.svg)](https://doi.org/10.1016/j.eswa.2025.126429)
  > 👨‍🔬 **Authors:** Hongbing Yang; Wei Zhou; Jian Zhang; Xinyu Zhang; Yexi Jin | 📅 **Year:** 2025 | 🏢 **Venue:** Expert Systems with Applications <br>
  > 🔑 **Keywords:** Container loading, Multi-container packing, Q-learning, Large neighborhood search <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-container loading \| Heterogeneous rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: three features describing the incumbent loading solution and search status \| Action: select a destroy-and-repair operator combination for large-neighborhood search \| Reward: objective improvement produced by the selected operator combination <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item and container geometry \| Stability: practical loading constraints handled by the underlying feasibility model \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: Q-learning-guided adaptive large-neighborhood search \| Data: benchmark and real-world multi-container-loading instances reported in the paper \| Objective: improve loaded volume and solution quality across multiple containers <br>

- ❤️ **A Novel Incremental Approach for Large-Scale Three-Dimensional Open-Dimension Rectangular Packing Problems** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cie.2025.111527-blue.svg)](https://doi.org/10.1016/j.cie.2025.111527)
  > 👨‍🔬 **Authors:** Jung-Fa Tsai; Dinh-Hieu Tran; Ming-Hua Lin | 📅 **Year:** 2025 | 🏢 **Venue:** Computers & Industrial Engineering <br>
  > 🔑 **Keywords:** 3D packing, Open-dimension packing, Mathematical programming, Large-scale optimization <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Large-scale open-dimension rectangular packing with optional pre-existing items \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (mixed-integer optimization and incremental solution method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item and container geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: mixed-integer formulation with problem reduction and incremental solution construction \| Data: generated large-scale instances including cases with 100–150 items and preallocated objects \| Objective: minimize the open container dimension while preserving feasible packing <br>

- ❤️ **An In-Depth Study of LLM Contributions to the Bin Packing Problem** [![arXiv](https://img.shields.io/badge/arXiv-2510.27353-b31b1b.svg)](https://arxiv.org/abs/2510.27353)
  > 👨‍🔬 **Authors:** Julien Herrmann; Guillaume Pallez | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2510.27353 <br>
  > 🔑 **Keywords:** Online packing, 1D bin packing, Large language models, Heuristic analysis, Generalization <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online/evaluation \| Multi-bin one-dimensional packing \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (empirical and analytical study of LLM-generated heuristics) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: scalar item sizes and current bin residual capacities \| Stability: not applicable to one-dimensional packing \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: interpretability and generalization analysis of LLM-designed online bin-packing rules, with simpler comparison algorithms \| Data: synthetic streams including uniform and Weibull item-size distributions \| Objective: assess whether LLM-generated heuristics are novel, interpretable, and robust across distributions <br>

- ❤️ **Arc-Flow Formulation and Branch-and-Price-and-Cut Algorithm for the Bin-Packing Problem with Fragile Objects** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cor.2024.106878-blue.svg)](https://doi.org/10.1016/j.cor.2024.106878)
  > 👨‍🔬 **Authors:** Sunkanghong Wang; Shaowen Yao; Hao Zhang; Qiang Liu; Lijun Wei | 📅 **Year:** 2025 | 🏢 **Venue:** Computers & Operations Research <br>
  > 🔑 **Keywords:** 1D bin packing, Fragile objects, Arc-flow formulation, Branch-and-price-and-cut <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin one-dimensional packing with fragility relations \| Scalar-sized items with stacking/compatibility restrictions <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (exact branch-and-price-and-cut method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item sizes and fragility relations \| Stability: fragility-induced compatibility and placement-order constraints \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: arc-flow formulation, label-setting pricing, and branch-and-price-and-cut \| Data: literature and generated fragile-object benchmark instances \| Objective: minimize bin count subject to fragile-object restrictions <br>

- ❤️ **Automated Pallet Loading of Irregularly Shaped Objects: A Deep Reinforcement Learning and Multi-Criteria Optimization Method** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.jmsy.2025.04.014-blue.svg)](https://doi.org/10.1016/j.jmsy.2025.04.014)
  > 👨‍🔬 **Authors:** Nikolaos Theodoropoulos; Dionisis Andronas; Emmanouil Kampourakis; Sotiris Makris | 📅 **Year:** 2025 | 🏢 **Venue:** Journal of Manufacturing Systems <br>
  > 🔑 **Keywords:** Palletization, Irregular objects, Deep reinforcement learning, Multi-criteria optimization, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Robotic pallet loading \| Irregular rigid industrial products <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: pallet-surface height grid plus the types and quantities of available objects \| Action: select the next object to palletize \| Reward: successful-placement reward augmented by inverse palletization fitness so difficult objects receive greater priority <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known or reconstructed object geometry and pallet state \| Stability: explicit stability assessment and constraint filtering \| Execution: automated palletization workflow for industrial aluminum-profile objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: PPO object-sequence policy, constraint-satisfaction candidate filtering, and multi-criteria placement/orientation selection \| Data: simulated training instances and an industrial aluminum-profile case study \| Objective: maximize pallet utilization and stable feasibility while reducing planning complexity <br>

- ❤️ **Beyond the Hype: Benchmarking LLM-Evolved Heuristics for Bin Packing** [![DOI](https://img.shields.io/badge/DOI-10.1007%2F978-3-031-90065-5_24-blue.svg)](https://doi.org/10.1007/978-3-031-90065-5_24) [![arXiv](https://img.shields.io/badge/arXiv-2501.11411-b31b1b.svg)](https://arxiv.org/abs/2501.11411)
  > 👨‍🔬 **Authors:** Kevin Sim; Quentin Renau; Emma Hart | 📅 **Year:** 2025 | 🏢 **Venue:** Applications of Evolutionary Computation (EvoApplications 2025) <br>
  > 🔑 **Keywords:** Online packing, 1D bin packing, Large language models, Heuristic benchmarking, Instance-space analysis <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online/evaluation \| Multi-bin one-dimensional packing \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (benchmarking and instance-space analysis study) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: scalar item streams and bin residual capacities \| Stability: not applicable to one-dimensional packing \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: broad benchmark comparison of LLM-evolved heuristics, evolved counter-instances, and instance-space analysis \| Data: a large suite of public and evolved online-bin-packing instances \| Objective: measure generalization, solution quality, and the cost-benefit of specialized LLM-designed heuristics <br>

- ❤️ **Developing Hybrid Metaheuristics for the Three-Dimensional Pallet Loading Considering Multiple-Size Pallet and Heterogeneous Box** [![DOI](https://img.shields.io/badge/DOI-10.1080%2F23302674.2025.2492219-blue.svg)](https://doi.org/10.1080/23302674.2025.2492219)
  > 👨‍🔬 **Authors:** Yu-Chung Tsao; Ting-Jie Chen; Thuy-Linh Vu; Lu-Wen Liao | 📅 **Year:** 2025 | 🏢 **Venue:** International Journal of Systems Science: Operations & Logistics <br>
  > 🔑 **Keywords:** 3D packing, Palletization, Heterogeneous boxes, Hybrid metaheuristics <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-pallet loading with multiple pallet sizes \| Heterogeneous rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (hybrid metaheuristic method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item and pallet geometry \| Stability: practical pallet-loading feasibility constraints \| Execution: palletization planning without a reported robot-control pipeline <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: fast loading heuristic combined with simulated annealing and differential evolution \| Data: generated and paper-reported pallet-loading instances \| Objective: reduce pallet use/cost and improve utilization under heterogeneous box and pallet choices <br>

- ❤️ **Digital Model-Driven Optimization for Robot-Assisted Palletization: Addressing Real-World Constraints in Autonomous Warehousing** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.ifacol.2025.09.338-blue.svg)](https://doi.org/10.1016/j.ifacol.2025.09.338)
  > 👨‍🔬 **Authors:** Anan Ashrabi Ananno; Marie Jonsson | 📅 **Year:** 2025 | 🏢 **Venue:** IFAC-PapersOnLine <br>
  > 🔑 **Keywords:** Palletization, Digital twin, Genetic algorithm, Robot constraints, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Robot-assisted pallet loading \| Rigid cuboid boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (genetic optimization with digital robot validation) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known box/pallet geometry and a digital robot model \| Stability: dynamic and load-stability constraints are included \| Execution: reachability, collision, and robot-motion feasibility are evaluated in the digital model <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: custom genetic algorithm integrated with a digital robot model \| Data: simulated warehouse palletization scenarios \| Objective: balance space utilization with robot reachability, collision avoidance, and load stability <br>

- ❤️ **Evaluating LLMs for Combinatorial Optimization: One-Phase and Two-Phase Heuristics for 2D Bin-Packing** [![arXiv](https://img.shields.io/badge/arXiv-2509.22255-b31b1b.svg)](https://arxiv.org/abs/2509.22255) [![Paper](https://img.shields.io/badge/Paper-Link-4682B4.svg)](https://nips.cc/virtual/2025/122441)
  > 👨‍🔬 **Authors:** Syed Mahbubul Huq; Daniel Brito-Pacheco; Daniel Sikar; Rajesh Mojumder; Chris Child; Tillman Weyde | 📅 **Year:** 2025 | 🏢 **Venue:** NeurIPS 2025 Workshop on Evaluating the Evolving LLM Lifecycle: Benchmarks, Emergent Abilities, and Scaling <br>
  > 🔑 **Keywords:** 2D packing, Large language models, Evolutionary algorithms, Heuristic generation, Workshop <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/evaluation \| Multi-bin two-dimensional packing \| Rectangles <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (LLM-guided heuristic-generation framework) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known rectangle dimensions and current bin layouts \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: iterative LLM-plus-evolution generation of one-phase and two-phase packing heuristics \| Data: paper-defined 2D bin-packing test instances and classical heuristic baselines \| Objective: reduce bin usage and increase space utilization while evaluating LLM optimization capability <br>

- ❤️ **Intelligent Optimization of E-Commerce Order Packing Using Deep Reinforcement Learning with Heuristic Strategies** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.asoc.2025.113283-blue.svg)](https://doi.org/10.1016/j.asoc.2025.113283)
  > 👨‍🔬 **Authors:** Kaibo Liang; Man Shan; Huwei Liu; Jianglong Yang; Chenxi Gu; Xiangyu Yin | 📅 **Year:** 2025 | 🏢 **Venue:** Applied Soft Computing <br>
  > 🔑 **Keywords:** E-commerce packing, Variable-sized bins, Deep reinforcement learning, Heuristic selection, Industrial data <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Multi-bin e-commerce order packing with multiple carton types \| Heterogeneous rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: order, item, available-carton, and current packing-status features \| Action: select the next item/order decision and a packing heuristic or strategy combination \| Reward: loading-efficiency and packing-cost improvement <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known product and carton dimensions \| Stability: practical packing feasibility handled by heuristic constraints \| Execution: no robotic-arm execution reported <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: order-packing-optimization DRL and packing-combination-strategy DRL integrated with constructive heuristics \| Data: JD.com order data and generated training/evaluation instances \| Objective: improve loading rate, carton selection, and computational efficiency <br>

- ❤️ **Interval-Tree Based Multi-Objective 3D Bin Packing Using Evolutionary Extreme Point Heuristic** [![DOI](https://img.shields.io/badge/DOI-10.1145%2F3712255.3726760-blue.svg)](https://doi.org/10.1145/3712255.3726760)
  > 👨‍🔬 **Authors:** Hermann Foot | 📅 **Year:** 2025 | 🏢 **Venue:** GECCO 2025 Companion <br>
  > 🔑 **Keywords:** 3D packing, Multi-objective optimization, Evolutionary algorithms, Extreme points, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container/open-height 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (evolutionary heuristic method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known box and container geometry \| Stability: support/stability quality is an explicit objective \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: evolutionary search with an extreme-point placement heuristic and interval-tree acceleration \| Data: public three-dimensional bin-packing benchmark instances \| Objective: jointly reduce packing height and improve load stability <br>

- ❤️ **LLM-Driven Instance-Specific Heuristic Generation and Selection** [![arXiv](https://img.shields.io/badge/arXiv-2506.00490-b31b1b.svg)](https://arxiv.org/abs/2506.00490)
  > 👨‍🔬 **Authors:** Shaofeng Zhang; Shengcai Liu; Ning Lu; Jiahao Wu; Ji Liu; Yew-Soon Ong; Ke Tang | 📅 **Year:** 2025 | 🏢 **Venue:** arXiv preprint arXiv:2506.00490 <br>
  > 🔑 **Keywords:** Online packing, 1D bin packing, Large language models, Hyper-heuristics, Instance-specific optimization <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online/evaluation \| Multi-bin one-dimensional packing \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (LLM-driven hyper-heuristic method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: item-stream and instance-feature representations \| Stability: not applicable to one-dimensional packing \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: instance-feature partitioning, LLM/evolution generation of subclass-specific heuristics, and heuristic selection \| Data: 4,500 online-bin-packing subclasses plus additional CVRP evaluation subclasses \| Objective: reduce optimality gap by matching specialized heuristics to heterogeneous instance regions <br>

- ❤️ **LOOP: Language Oriented Object Packing with Diffusion Models** [![Paper](https://img.shields.io/badge/Paper-Link-4682B4.svg)](https://iros-2025-ai4roboticsmanufacturing.github.io/)
  > 👨‍🔬 **Authors:** Anurag Maurya; Shashwat Gupta; Sandip Das; Shivam Vats; Ravi Prakash | 📅 **Year:** 2025 | 🏢 **Venue:** IROS 2025 Workshop on Generative AI for Robotics and Smart Manufacturing <br>
  > 🔑 **Keywords:** Irregular objects, Diffusion models, Large language models, Physics simulation, Workshop <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Single-container irregular-object packing with language preferences \| Irregular rigid objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (diffusion sampling and physics-based optimization) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known object/container geometry plus natural-language preferences \| Stability: simulator-based physics plausibility and barrier-function constraints \| Execution: no archival real-robot execution report <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: diffusion-based layout sampling, simulator physics integration, LLM preference interpretation, and barrier functions \| Data: paper-defined simulated irregular-object packing tasks \| Objective: generate physically plausible layouts satisfying customizable natural-language preferences <br>

- ❤️ **Low Resolution Next Best View for Robot Packing** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.ifacol.2025.10.228-blue.svg)](https://doi.org/10.1016/j.ifacol.2025.10.228) [![arXiv](https://img.shields.io/badge/arXiv-2505.04228-b31b1b.svg)](https://arxiv.org/abs/2505.04228)
  > 👨‍🔬 **Authors:** Giuseppe Fabio Preziosa; Chiara Castellano; Andrea Maria Zanchettin; Marco Faroni; Paolo Rocco | 📅 **Year:** 2025 | 🏢 **Venue:** IFAC-PapersOnLine <br>
  > 🔑 **Keywords:** Scope-adjacent, Active perception, Next-best view, Robot packing, 3D reconstruction <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Scope-adjacent active perception \| Not a packing policy; next-best-view selection for robot packing \| General objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (sampling-based active-perception method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: very-low-resolution 3D sensing and partial object reconstructions \| Stability: not evaluated \| Execution: sensor-view planning intended for scalable robotic packing cells <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: low-resolution next-best-view utility balancing pose redundancy and acquisition density, with RRT exploration \| Data: experimental low-resolution reconstruction trials \| Objective: obtain packing-sufficient object geometry with fewer sensor poses <br>

- ❤️ **Multi-Heuristic Robotic Bin Packing of Regular and Irregular Objects** [![DOI](https://img.shields.io/badge/DOI-10.1109%2FICRA55743.2025.11128421-blue.svg)](https://doi.org/10.1109/ICRA55743.2025.11128421)
  > 👨‍🔬 **Authors:** Tim Nickel; Richard Bormann; Kai Oliver Arras | 📅 **Year:** 2025 | 🏢 **Venue:** IEEE International Conference on Robotics and Automation (ICRA) <br>
  > 🔑 **Keywords:** Robotic packing, Irregular objects, Multi-heuristic planning, Stability, Retail objects <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Single-container robotic packing \| Regular and irregular rigid retail objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (weighted multi-heuristic planning method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known or reconstructed object geometry \| Stability: task-specific packing and support criteria are evaluated through multiple heuristics \| Execution: real robotic packing applications <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: So-Pack generalist irregular-object heuristic integrated into a weighted multi-heuristic planner \| Data: a newly introduced retail-object dataset and real-world application trials \| Objective: maximize packing quality while adapting to user- and task-specific packing rules <br>

- ❤️ **Multi-Objective 3D Bin Packing Strategies Through Meta Reinforcement Learning** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.ifacol.2025.09.422-blue.svg)](https://doi.org/10.1016/j.ifacol.2025.09.422)
  > 👨‍🔬 **Authors:** Hermann Foot; Benedikt Mättig | 📅 **Year:** 2025 | 🏢 **Venue:** IFAC-PapersOnLine <br>
  > 🔑 **Keywords:** 3D packing, Multi-objective optimization, Meta reinforcement learning, Stability, Weight distribution <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Single-container 3D packing across changing objective preferences \| Rigid cuboids with weight attributes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: current packing configuration, remaining items, and objective-preference information \| Action: select packing decisions under the current trade-off \| Reward: weighted combination of volume efficiency, stability, and weight-distribution objectives <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/container geometry and weights \| Stability: explicit stability and weight-distribution objectives \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: meta-reinforcement-learning policy for adapting across multi-objective packing preferences \| Data: simulated three-dimensional bin-packing instances \| Objective: learn transferable trade-offs among utilization, stability, and load distribution <br>

- ❤️ **Multi-Objective Dynamic Feedback Algorithm for Solving the Multi-Drop Three-Dimensional Multiple Bin-Size Bin Packing Problem** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cie.2025.111059-blue.svg)](https://doi.org/10.1016/j.cie.2025.111059)
  > 👨‍🔬 **Authors:** Yi Liu; Xiaoyun Jiang | 📅 **Year:** 2025 | 🏢 **Venue:** Computers & Industrial Engineering <br>
  > 🔑 **Keywords:** 3D packing, Multi-drop loading, Variable-sized bins, Multi-objective optimization, Logistics <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin loading with multiple bin sizes and unloading order \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (multi-stage heuristic optimization method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known box/bin geometry and destination order \| Stability: geometric and logistics feasibility constraints \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: three-stage multi-objective dynamic-feedback algorithm \| Data: generated multi-drop and multiple-bin-size instances \| Objective: improve utilization while reducing container cost and unloading obstruction <br>

- ❤️ **Multi-Objective Evolution of Heuristic Using Large Language Model** [![DOI](https://img.shields.io/badge/DOI-10.1609%2Faaai.v39i25.34922-blue.svg)](https://doi.org/10.1609/aaai.v39i25.34922)
  > 👨‍🔬 **Authors:** Shunyu Yao; Fei Liu; Xi Lin; Zhichao Lu; Zhenkun Wang; Qingfu Zhang | 📅 **Year:** 2025 | 🏢 **Venue:** AAAI Conference on Artificial Intelligence <br>
  > 🔑 **Keywords:** Online packing, 1D bin packing, Large language models, Evolution of heuristics, Multi-objective optimization <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online/evaluation \| Multi-bin one-dimensional packing within a multi-domain heuristic-design framework \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (LLM-guided evolutionary heuristic design) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: scalar item streams and current bin states \| Stability: not applicable to one-dimensional packing \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: multi-objective evolution of executable heuristics generated and revised by a large language model \| Data: online-bin-packing and additional combinatorial-optimization benchmarks \| Objective: jointly optimize solution quality, runtime efficiency, and scalability <br>

- ❤️ **Neural-Driven Constructive Heuristic for 2D Robotic Bin Packing Problem** [![DOI](https://img.shields.io/badge/DOI-10.3390%2Felectronics14101956-blue.svg)](https://doi.org/10.3390/electronics14101956)
  > 👨‍🔬 **Authors:** Mariusz Kaleta; Tomasz Śliwiński | 📅 **Year:** 2025 | 🏢 **Venue:** Electronics <br>
  > 🔑 **Keywords:** 2D packing, Robotic packing, Neural heuristic, Constructive methods, Insertability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-bin two-dimensional robotic packing \| Rectangles <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (neural scoring model trained for constructive heuristic selection) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: engineered features of the current layout and candidate placement \| Stability: geometric non-overlap only \| Execution: robot insertability/accessibility is considered in candidate feasibility <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: neural candidate scorer optimized with CMA-ES inside a constructive packing heuristic \| Data: 2DCPackGen instances and FMCG logistics data \| Objective: minimize bin count while preserving robot-packable insertion sequences <br>

- ❤️ **On the Multiple Optimal Solutions and Patterns of the Pallet Loading Problem** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cor.2025.107182-blue.svg)](https://doi.org/10.1016/j.cor.2025.107182)
  > 👨‍🔬 **Authors:** Junmin Yi; Mingming Li; Yiping Lu | 📅 **Year:** 2025 | 🏢 **Venue:** Computers & Operations Research <br>
  > 🔑 **Keywords:** Pallet loading, Exact optimization, Packing patterns, Multiple optima <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Manufacturer's pallet loading \| Identical rectangular boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (exact enumeration and pattern-analysis method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known pallet and box dimensions \| Stability: layer-based geometric feasibility \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: characterization and enumeration of multiple optimal pallet-loading solutions and patterns \| Data: standard pallet-loading benchmark instances \| Objective: maximize the number of loaded boxes and analyze diversity among equal-quality optimal patterns <br>

- ❤️ **RASP: Revisiting 3D Anamorphic Art for Shadow-Guided Packing of Irregular Objects** [![DOI](https://img.shields.io/badge/DOI-10.1109%2FCVPR52734.2025.00549-blue.svg)](https://doi.org/10.1109/CVPR52734.2025.00549) [![arXiv](https://img.shields.io/badge/arXiv-2504.02465-b31b1b.svg)](https://arxiv.org/abs/2504.02465)
  > 👨‍🔬 **Authors:** Soumyaratna Debnath; Ashish Tiwari; Kaustubh Sadekar; Shanmuganathan Raman | 📅 **Year:** 2025 | 🏢 **Venue:** IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) <br>
  > 🔑 **Keywords:** 3D packing, Irregular objects, Differentiable rendering, Signed-distance fields, Continuous pose optimization <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single-container geometric packing and part assembly \| Irregular 3D mesh objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (differentiable optimization method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known 3D meshes and rendered silhouettes \| Stability: geometric intersection and container-extrusion constraints; no physical stability model \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: shadow/silhouette-guided differentiable rendering with SDF-based intersection and boundary losses \| Data: irregular-object packing and part-assembly datasets reported in the paper \| Objective: minimize inter-object spacing and maximize occupancy while preventing overlap and extrusion <br>

- ❤️ **Robotic Manipulation Framework Based on Semantic Keypoints for Packing Shoes of Different Sizes, Shapes, and Softness** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.robot.2025.105174-blue.svg)](https://doi.org/10.1016/j.robot.2025.105174)
  > 👨‍🔬 **Authors:** Yi Dong; Yangjun Liu; Jinjun Duan; Yang Li; Zhendong Dai | 📅 **Year:** 2025 | 🏢 **Venue:** Robotics and Autonomous Systems <br>
  > 🔑 **Keywords:** Robotic packing, Deformable objects, Semantic keypoints, Contact-rich manipulation, Shoes <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Sequential \| Single-container robotic shoe packing \| Paired irregular and deformable shoes with varying sizes and softness <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (semantic-keypoint perception and task-planning framework) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: vision-derived semantic keypoints and shoe state \| Stability: object state and placement feasibility are checked during manipulation \| Execution: UR5e robot, soft gripper, and environment-assisted reorientation using table and box contacts <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: semantic-keypoint perception, state recognition, grasp inference, contact-assisted reorientation, and packing task planning \| Data: physical shoes spanning different sizes, shapes, and softness \| Objective: robustly orient and pack shoe pairs under object variation and deformation <br>

- ❤️ **Snuggle-Pack: Speeding Up Multi-Heuristic Packing Planning of Complex Objects** [![DOI](https://img.shields.io/badge/DOI-10.1109%2FIROS60139.2025.11246900-blue.svg)](https://doi.org/10.1109/IROS60139.2025.11246900)
  > 👨‍🔬 **Authors:** Tim Nickel; Richard Bormann; Kai Oliver Arras | 📅 **Year:** 2025 | 🏢 **Venue:** IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) <br>
  > 🔑 **Keywords:** Robotic packing, Irregular objects, Multi-heuristic planning, Fast 3D matching, Task constraints <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Single-container robotic packing \| Complex regular and irregular rigid objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (accelerated multi-heuristic planning method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known or reconstructed 3D object geometry \| Stability: support and task-specific criteria can be incorporated in heuristic scoring \| Execution: designed for robot-executable packing plans <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: accelerated multi-heuristic packing planner using fast volumetric/3D matching for candidate evaluation \| Data: complex-object benchmark and robot-relevant packing scenarios \| Objective: reduce planning time while retaining flexible, high-quality packing layouts <br>

- ❤️ **Deep Reinforcement Learning Method with Integrated Rotation and Placement Strategies for Solving the 2D Bin Packing Problem** [![DOI](https://img.shields.io/badge/DOI-10.1007%2F978-981-95-4045-7_21-blue.svg)](https://doi.org/10.1007/978-981-95-4045-7_21)
  > 👨‍🔬 **Authors:** Xiaoping Jiang; Gang Xiao; Xia Zhang; Mu Yuan; Zhenhui Lou; Jiangtao Ye; Fengjie Li; Zhenbo Cheng | 📅 **Year:** 2026 | 🏢 **Venue:** Lecture Notes in Electrical Engineering <br>
  > 🔑 **Keywords:** 2D packing, Deep reinforcement learning, Rotation, Placement <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Single variable-height 2D container \| Rectangles <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: item states plus depth-, empty-space-, and height-map container features \| Action: choose item with rotation, then a candidate placement \| Reward: stepwise reduction in unused container area <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: deep reinforcement learning with integrated item rotation and placement \| Data: generated rectangle instances \| Objective: minimize unused area and packing height <br>

- ❤️ **Deliberate planning of 3D bin packing on packing configuration trees** [![DOI](https://img.shields.io/badge/DOI-10.1177%2F02783649251380619-blue.svg)](https://doi.org/10.1177/02783649251380619)
  > 👨‍🔬 **Authors:** Hang Zhao; Juzhan Xu; Kexiong Yu; Ruizhen Hu; Chenyang Zhu; Bo Du; Kai Xu | 📅 **Year:** 2026 | 🏢 **Venue:** The International Journal of Robotics Research <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Offline packing, Palletization, Deep reinforcement learning, Robotic packing, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container sequential 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: packing-configuration tree and current partial packing \| Action: deliberately select/expand a placement node \| Reward: incremental compactness and terminal utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: deliberate planning/learning on packing-configuration trees \| Data: generated, industrial-distribution, and robot-relevant instances \| Objective: maximize utilization and stable feasibility <br>

- ❤️ **Effective Online 3D Bin Packing with Lookahead Parcels Using Monte Carlo Tree Search** [![arXiv](https://img.shields.io/badge/arXiv-2601.02649-b31b1b.svg)](https://arxiv.org/abs/2601.02649)
  > 👨‍🔬 **Authors:** Jiangyi Fang1,4, Bowen Zhou2, Haotian Wang3, Xin Zhu3, Leye Wang1,4∗ | 📅 **Year:** 2026 | 🏢 **Venue:** arXiv preprint arXiv:2601.02649 <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Dynamic packing, Deep reinforcement learning, Tree search, Robotic packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-bin sequential packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (Monte Carlo tree search planning, not RL) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: robot manipulator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: Monte Carlo tree search, tree search, deep reinforcement learning \| Data: real-world/industrial data with paper-reported evaluation \| Objective: maximize utilization/minimize waste <br>

- ❤️ **GENPACK: KPI-Guided Multi-Objective Genetic Algorithm for Industrial 3D Bin Packing** [![arXiv](https://img.shields.io/badge/arXiv-2601.11325-b31b1b.svg)](https://arxiv.org/abs/2601.11325)
  > 👨‍🔬 **Authors:** Dheeraj Poolavaram, Carsten Markgraf, Sebastian Dorn | 📅 **Year:** 2026 | 🏢 **Venue:** arXiv preprint arXiv:2601.11325 <br>
  > 🔑 **Keywords:** 3D bin packing, Palletization, Genetic algorithm, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Industrial pallet/3D-bin packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit stability checks \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: KPI-guided multi-objective hybrid genetic algorithm \| Data: 1,500 BED-BPP real-world orders \| Objective: jointly improve utilization, surface support, balance, and handling feasibility <br>

- ❤️ **SDT-6D: Fully Sparse Depth-Transformer for Staged End-to-End 6D Pose Estimation in Industrial Multi-View Bin Picking** [![DOI](https://img.shields.io/badge/DOI-10.1109%2Fwacv61042.2026.00811-blue.svg)](https://doi.org/10.1109/wacv61042.2026.00811)
  > 👨‍🔬 **Authors:** Nico Leuze; Maximilian Hoh; Samed Doğan; Nicolas R. Peña; Alfred Schoettl | 📅 **Year:** 2026 | 🏢 **Venue:** 2026 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) <br>
  > 🔑 **Keywords:** Dynamic packing, Transformer, Robotic packing, Vision <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Scope-adjacent bin picking/perception \| Not a packing policy \| General objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: point cloud, RGB-D/depth, signed-distance field \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: Transformer, signed-distance optimization \| Data: paper-reported datasets/benchmark instances \| Objective: estimate 6D object poses <br>

- ❤️ **The inventory routing problem with two-dimensional loading constraints** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cie.2025.111606-blue.svg)](https://doi.org/10.1016/j.cie.2025.111606)
  > 👨‍🔬 **Authors:** Pedro H.B. Hokama; Kamyla Ferreira; Pedro Munari; Reinaldo Morabito; Flavio Miyazawa | 📅 **Year:** 2026 | 🏢 **Venue:** Computers & Industrial Engineering <br>
  > 🔑 **Keywords:** Inventory routing, 2D loading, Branch-and-cut, Constraint programming, Vehicle routing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Inventory routing with 2D loading constraints across multiple vehicles \| Rectangular palletized cargo <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: mixed-integer formulation with branch-and-cut/constraint-programming components \| Data: generated inventory-routing instances \| Objective: minimize combined inventory, routing, and loading cost <br>

- ❤️ **EoH-S: Evolution of Heuristic Set using LLMs for Automated Heuristic Design** [![arXiv](https://img.shields.io/badge/arXiv-2508.03082-b31b1b.svg)](https://arxiv.org/abs/2508.03082) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/FeiLiu36/EoH-S)
  > 👨‍🔬 **Authors:** Fei Liu; Yilu Liu; Qingfu Zhang; Xialiang Tong; Mingxuan Yuan | 📅 **Year:** 2026 | 🏢 **Venue:** Proceedings of the AAAI Conference on Artificial Intelligence (AAAI-26, Oral) <br>
  > 🔑 **Keywords:** Online packing, Large language models, Automated heuristic design, Evolutionary computation, Hyper-heuristics <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| One-dimensional online bin packing as one of three AHD benchmark tasks (with TSP and CVRP) \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method; LLM-driven evolutionary heuristic search) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: automated heuristic set design (AHSD) — LLM-based evolutionary search with complementary population management and complementary-aware memetic search that outputs a small set of complementary heuristics \| Data: online bin packing instance sets of diverse sizes and distributions \| Objective: minimize bin usage / waste ratio with improved cross-distribution generalization, up to 60% improvement over prior AHD methods <br>

- ❤️ **Visual Foresight for Robotic Stow: A Diffusion-Based World Model from Sparse Snapshots** [![arXiv](https://img.shields.io/badge/arXiv-2602.13347-b31b1b.svg)](https://arxiv.org/abs/2602.13347)
  > 👨‍🔬 **Authors:** Lijun Zhang; Nikhil Chacko; Petter Nilsson; Ruinian Xu; Shantanu Thakar; Xibai Lou; Harpreet S. Sawhney; Zhebin Zhang; Mudit Agrawal; Bhavana Chandrashekhar; Aaron Parness | 📅 **Year:** 2026 | 🏢 **Venue:** arXiv preprint arXiv:2602.13347 <br>
  > 🔑 **Keywords:** Scope-adjacent, Robotic stowing, World model, Diffusion model, Visual foresight <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Scope-adjacent prediction \| Post-stow bin-layout forecasting from sparse snapshots; not a packing policy \| Fabric-bin inventory items, rigid and deformable <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (conditional generative world model, not RL) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: pre/post-stow RGB snapshots converted to item-aligned instance masks, plus item properties and stow intent \| Stability: implicitly learned interaction dynamics (pushing, sliding, toppling) \| Execution: prediction model evaluated on downstream load-quality and multi-stow reasoning for warehouse stow planning <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: stow-intent-conditioned latent diffusion transformer (FOREST) over slot-aligned bin-state masks \| Data: ARMBench production stow events from Amazon fulfillment centers \| Objective: maximize geometric agreement (instance IoU) between predicted and true post-stow layouts <br>

- ❤️ **Pack it in: Packing into Partially Filled Containers Through Contact** [![arXiv](https://img.shields.io/badge/arXiv-2602.12095-b31b1b.svg)](https://arxiv.org/abs/2602.12095)
  > 👨‍🔬 **Authors:** David Russell; Zisong Xu; Maximo A. Roa; Mehmet Dogar | 📅 **Year:** 2026 | 🏢 **Venue:** 2026 IEEE International Conference on Robotics and Automation (ICRA) / arXiv preprint arXiv:2602.12095 <br>
  > 🔑 **Keywords:** Robotic packing, Contact-rich manipulation, Trajectory optimization, Model predictive control, Rearrangement <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Sequential \| Packing a new object into an already partially filled container by exploiting purposeful contact with placed items \| General rigid objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (iLQR trajectory optimization within an MPC loop, not RL) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: marker-based object tracking with a physics-aware perception module that estimates poses under occlusion \| Stability: physics simulation of multi-object contact during insertion \| Execution: real robot manipulator performing simultaneous rearrangement and insertion (about 70% real-world success) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: contact-based multi-object trajectory optimizer inside model predictive control, plus a physics-informed placement planner that simulates candidate packing poses \| Data: real-robot and simulated container-packing trials with ablations \| Objective: enable feasible placement where no collision-free space exists while minimally disturbing the existing arrangement <br>

- ❤️ **Can machine learning help in solving the pallet loading optimization problem?** [![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs10732-026-09586-5-blue.svg)](https://doi.org/10.1007/s10732-026-09586-5) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1007%2Fs10732-026-09586-5)](https://scholar.google.com/scholar?q=Can%20machine%20learning%20help%20in%20solving%20the%20pallet%20loading%20optimization%20problem%3F) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/MatteoMagnani95/DPLP)
  > 👨‍🔬 **Authors:** Mauro Dell'Amico; Giorgia Franchini; Matteo Magnani; Luca Zanni | 📅 **Year:** 2026 | 🏢 **Venue:** Journal of Heuristics <br>
  > 🔑 **Keywords:** Palletization, 3D bin packing, Machine learning, Matheuristic, Integer programming <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Distributor's Pallet Loading Problem (DPLP) with layer decomposition and practical constraints (dimension, weight, stackability, stability, compression) \| Rigid cuboid boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method; ML-assisted matheuristic) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: layer-area-ratio stability, stackability height difference, and compression constraints \| Execution: palletization execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: ILP over pre-generated box layers accelerated by machine-learning classifiers (Random Forest, Support Vector Regression, and a hybrid) that predict layer importance to shrink the variable set \| Data: food-and-beverage logistics dataset with 50 box types on euro pallets; public code and instances \| Objective: minimize pallet count within practical computation-time limits <br>

- ❤️ **Preference-Conditioned Reinforcement Learning for Space-Time Efficient Online 3D Bin Packing** [![arXiv](https://img.shields.io/badge/arXiv-2603.07800-b31b1b.svg)](https://arxiv.org/abs/2603.07800) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://step-packing.github.io)
  > 👨‍🔬 **Authors:** Nikita Sarawgi; Omey M. Manyar; Fan Wang; Thinh H. Nguyen; Daniel Seita; Satyandra K. Gupta | 📅 **Year:** 2026 | 🏢 **Venue:** arXiv preprint arXiv:2603.07800 <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Semi-online packing, Robotic packing, Multi-objective reinforcement learning, Transformer <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Semi-online with an item buffer \| Single-bin robotic packing with grasp-face selection and item reorientation \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: EMS-based bin state, item-face buffer with geometric and temporal attributes, and a preference vector \| Action: select an item-face candidate (item plus graspable face) for placement by an external placement module \| Reward: two-dimensional vector of space-utilization gain and operational-time cost, scalarized by the sampled preference <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: static stability under gravity enforced by the placement module \| Execution: robot grasping with face-dependent reorientation and transport time costs <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: STEP — a preference-conditioned Transformer policy trained with multi-objective PPO (RDP-MORL) over a 5N item-face action space, using GOPT as the placement module \| Data: RS dataset with simulated operational-time models \| Objective: trace the space-time Pareto front, achieving a 44% reduction in operational time at comparable packing density <br>

- ❤️ **Deep Reinforcement Learning for Scalable Offline Three-Dimensional Packing** [![DOI](https://img.shields.io/badge/DOI-10.1609%2Faaai.v40i33.40009-blue.svg)](https://doi.org/10.1609/aaai.v40i33.40009) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1609%2Faaai.v40i33.40009)](https://scholar.google.com/scholar?q=Deep%20Reinforcement%20Learning%20for%20Scalable%20Offline%20Three-Dimensional%20Packing) [![Code](https://img.shields.io/badge/Code-GitHub-green.svg)](https://github.com/Ashenone511/BBMP-DCS)
  > 👨‍🔬 **Authors:** Hao Yin; Hongjie He; Fan Chen | 📅 **Year:** 2026 | 🏢 **Venue:** Proceedings of the AAAI Conference on Artificial Intelligence (AAAI-26) <br>
  > 🔑 **Keywords:** 3D bin packing, Offline packing, Deep reinforcement learning, Attention, Scalability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| 3D strip packing with a variable-height container (3D-SPP) \| Rigid cuboids, 20 to 1000+ items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: unpacked items, available spaces, and packed items encoded by an attention-based pack-Q-network (PQNet) \| Action: select item and available space; a bidding-based multi-policy (BBMP) framework explores four packing directions, and a training-free dynamic candidate selection (DCS) moves candidate items into the processing set \| Reward: Q-learning targets aligned with space utilization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: PQNet plus BBMP multi-policy exploration plus DCS for large-item-count planning \| Data: generated instances with 20–1000 items and multiple container sizes \| Objective: maximize space utilization at scale, outperforming the best baseline at each scale by 3.2%–13.1% <br>

- ❤️ **Diffusion Reinforcement Learning Based Online 3D Bin Packing Spatial Strategy Optimization** [![arXiv](https://img.shields.io/badge/arXiv-2604.10953-b31b1b.svg)](https://arxiv.org/abs/2604.10953)
  > 👨‍🔬 **Authors:** Jie Han; Tong Li; Qingyang Xu; Yong Song; Bao Pang; Xianfeng Yuan | 📅 **Year:** 2026 | 🏢 **Venue:** arXiv preprint arXiv:2604.10953 <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Diffusion model, Deep reinforcement learning <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Single-container sequential 3D packing with items arriving one by one \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: height-map-based representation of the current packing state \| Action: packing actions generated by a diffusion-model-based actor network within an actor-critic scheme \| Reward: cumulative packing reward reflecting space utilization and number of packed items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: height map \| Stability: geometric non-overlap only \| Execution: robotic-arm packing scenario <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: diffusion reinforcement learning — a diffusion-model actor that iteratively denoises action candidates to model complex multimodal action distributions, improving sample efficiency \| Data: multiple public online 3D-BPP datasets \| Objective: maximize the average number of packed items and space utilization versus state-of-the-art DRL methods <br>

- ❤️ **Optimizing 3D Bin Packing of Heterogeneous Objects Using Continuous Transformations in SE(3)** [![DOI](https://img.shields.io/badge/DOI-10.1002%2Faisy.202501228-blue.svg)](https://doi.org/10.1002/aisy.202501228) [![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1002%2Faisy.202501228)](https://scholar.google.com/scholar?q=Optimizing%203D%20Bin%20Packing%20of%20Heterogeneous%20Objects%20Using%20Continuous%20Transformations%20in%20SE%283%29)
  > 👨‍🔬 **Authors:** Michele Angelini; Marco Carricato | 📅 **Year:** 2026 | 🏢 **Venue:** Advanced Intelligent Systems <br>
  > 🔑 **Keywords:** 3D bin packing, Irregular objects, Signed-distance field, Continuous optimization, Physics simulation, E-commerce packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline and online variants \| Single-bin packing of heterogeneous primitive-shaped objects with continuous translations and rotations \| Cuboids, cylinders, prisms, and pyramidal frusta <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry via neural-network-approximated SDFs and point-cloud occupancy \| Stability: mesh-based physics simulation for static stability and geometric interference after each placement \| Execution: simulated top-down placement; online variant replaces the simulator with real manipulator contact <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: heuristic-driven continuous optimization over a constrained subset of SE(3), sampling candidate transformations that minimize an SDF-based proximity loss, followed by physics-based placement settling \| Data: simulated shape families and e-commerce order scenarios \| Objective: maximize packing efficiency and, offline, also optimize the bin size <br>

- ❤️ **RAISE: LLM-based Automated Heuristic Design with Robust Adversary Instance Search** [![arXiv](https://img.shields.io/badge/arXiv-2606.31801-b31b1b.svg)](https://arxiv.org/abs/2606.31801)
  > 👨‍🔬 **Authors:** Fei Liu; Alessio Figalli; Patrick Owen; Nicola Serra | 📅 **Year:** 2026 | 🏢 **Venue:** arXiv preprint arXiv:2606.31801 <br>
  > 🔑 **Keywords:** Online packing, Large language models, Automated heuristic design, Distribution shift, Robustness <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| One-dimensional online bin packing under distribution shift (also online job-shop scheduling and online vehicle routing) \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (non-RL method; LLM-driven evolutionary heuristic search) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: bi-level robust AHD — an LLM evolutionary outer loop for heuristic evolution coupled with an LLM-free inner loop that searches worst-case instances within an epsilon-ball of the training distribution via basis-distribution parameterization and boundary projection \| Data: 60 online bin packing datasets across five distribution families and multiple sizes/capacities \| Objective: minimize waste ratio under shifted distributions, where prior LLM-AHD methods degrade by up to 19x <br>

- ❤️ **Operationally Guided Placement-Aware Learning for Industrial Online 3D Bin Packing** [![arXiv](https://img.shields.io/badge/arXiv-2607.28257-b31b1b.svg)](https://arxiv.org/abs/2607.28257)
  > 👨‍🔬 **Authors:** Dheeraj Poolavaram; Aanchal Rajesh Chugh; Sebastian Dorn | 📅 **Year:** 2026 | 🏢 **Venue:** arXiv preprint arXiv:2607.28257 <br>
  > 🔑 **Keywords:** 3D bin packing, Online packing, Palletization, Deep reinforcement learning, xLSTM, Industrial KPIs <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online (pre-sorted order sequence) \| Industrial Euro-pallet order packing \| Rigid cuboids with weight, fragility, and handling attributes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: pallet heightmap plus up to 2K candidate actions, each a 15-dimensional anchor-orientation feature vector with a feasibility mask \| Action: rank and select one admissible candidate placement with the masked actor \| Reward: shaped reward combining density increment, bottom support, support-region centering, placement effort, stack-load risk, height terms, low placement, wall proximity, and lateral support <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item/bin geometry \| Stability: explicit bottom-support, stack-load, and fragility feasibility checks in candidate generation \| Execution: industrial palletizing with operational KPIs and inference-latency evaluation <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: OPAL — Operationally Guided EMS (OG-EMS) candidate generation plus an xLSTM Placement Encoder and LRAM masked ranking policy trained with PPO \| Data: 1500 real-world BED-BPP grocery-logistics orders \| Objective: maximize absolute density/space utilization together with support, balance, and center-of-gravity KPIs; mean space utilization 0.49, +15.1% from guided candidate generation and +6.3% from learned ranking <br>

- ❤️ **A Branch-and-Cut Algorithm for the Pallet-Loading Vehicle Routing Problem Considering Load Balance of Semi-Trailer Trucks** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cor.2025.107258-blue.svg)](https://doi.org/10.1016/j.cor.2025.107258)
  > 👨‍🔬 **Authors:** Xiangbin Xu; Haoxing Ouyang | 📅 **Year:** 2026 | 🏢 **Venue:** Computers & Operations Research <br>
  > 🔑 **Keywords:** Vehicle routing, Pallet loading, 2D packing, Load balance, Branch-and-cut <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Split-delivery vehicle routing with two-dimensional pallet loading and truck-balance constraints \| Rectangular palletized cargo <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (mixed-integer programming, adaptive large-neighborhood search, and branch-and-cut) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known orders, pallet geometry, truck layout, and axle/load information \| Stability: semi-trailer load balance and axle-related constraints \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: mixed-integer formulation, adaptive large-neighborhood upper-bound search, and branch-and-cut \| Data: modified routing and loading benchmark instances \| Objective: minimize transportation cost subject to route, pallet-loading, and vehicle-balance feasibility <br>

- ❤️ **A Combinatorial Algorithm for Three Dimensional Multi-Container Loading Problem with Different Capacity Constraints** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cie.2025.111779-blue.svg)](https://doi.org/10.1016/j.cie.2025.111779)
  > 👨‍🔬 **Authors:** Zhao-hong Jia; Zhong-jun Gao; Chuang Liu; Yun Yang; Tao Fang; Kai Li | 📅 **Year:** 2026 | 🏢 **Venue:** Computers & Industrial Engineering <br>
  > 🔑 **Keywords:** 3D packing, Multi-container loading, Capacity constraints, Combinatorial heuristics, Multi-drop loading <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Multi-container loading with heterogeneous capacities and operational constraints \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (combinatorial heuristic and metaheuristic method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known items, container dimensions, capacities, and delivery/load-bearing attributes \| Stability: load-bearing and practical loading constraints \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: two-stage combinatorial loading algorithm with greedy/refined search, space recycling, and metaheuristic improvement \| Data: RAND and OR-library-style loading instances reported in the paper \| Objective: maximize loaded value/volume while satisfying heterogeneous capacity and operational constraints <br>

- ❤️ **A Real-Time Heuristic 3D Bin Packing Algorithm for Robotic Mixed Palletizing with Kinematic and Stability Constraints** [![DOI](https://img.shields.io/badge/DOI-10.1109%2FICMTIM69588.2026.11526704-blue.svg)](https://doi.org/10.1109/ICMTIM69588.2026.11526704)
  > 👨‍🔬 **Authors:** Y. Sun; K. Sun; W. Yan; Y. Cai; Z. Liao | 📅 **Year:** 2026 | 🏢 **Venue:** 7th International Conference on Mechatronics Technology and Intelligent Manufacturing (ICMTIM) <br>
  > 🔑 **Keywords:** 3D packing, Robotic palletization, Real-time heuristics, Kinematic constraints, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online/sequential \| Robotic mixed pallet loading \| Rigid cuboid boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (real-time constructive heuristic) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known box and pallet geometry \| Stability: minimum 75% bottom-support-area rule \| Execution: top-down end-effector clearance and robot kinematic feasibility checks <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: Guillotine-Split free-space management with physical support and top-down clearance guardrails \| Data: paper-reported mixed-palletizing instances and robot implementation \| Objective: generate fast, stable, and robot-executable pallet layouts <br>

- ❤️ **AI-Enabled Digital Twin Framework for Reconfigurable Robotic Palletizing of Irregularly Shaped Products** [![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs00170-026-18109-2-blue.svg)](https://doi.org/10.1007/s00170-026-18109-2)
  > 👨‍🔬 **Authors:** Nikolaos Theodoropoulos; Andres Castro; Stella Dimitra Tragianni; Dionisis Andronas; Isiah Zaplana; Bengisu Ayan; Raul Suarez; Michael Suppa; Sotiris Makris | 📅 **Year:** 2026 | 🏢 **Venue:** International Journal of Advanced Manufacturing Technology <br>
  > 🔑 **Keywords:** Robotic palletization, Irregular objects, Digital twin, Deep learning, Reconfigurable systems <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Reconfigurable dual-arm robotic pallet loading \| Irregular industrial products <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: pallet-surface representation and available-object inventory used by the learning-based sequencing component \| Action: select the next object for palletization \| Reward: placement success and palletization-fitness signal promoting difficult-object prioritization <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: CAD-derived geometry and deep-learning-based perception \| Stability: stable-placement and product-handling constraints \| Execution: digital-twin validation and dual-arm physical demonstrator <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: CAD grasp generation, learned perception, learning-assisted sequence optimization, digital-twin validation, and robot execution \| Data: simulated/digital-twin data and an irregular aluminum-product demonstrator \| Objective: support reconfigurable, stable, and executable palletization across robot-cell configurations <br>

- ❤️ **CMDRL: A Cavity-Aware Deep Reinforcement Learning Framework with Spatiotemporal Attention for 3D Bin Packing** [![DOI](https://img.shields.io/badge/DOI-10.1177%2F09544054261427648-blue.svg)](https://doi.org/10.1177/09544054261427648)
  > 👨‍🔬 **Authors:** Sirui Wang; Yunqing Rao; Nai Li; Peng Qi; Xusheng Zhao | 📅 **Year:** 2026 | 🏢 **Venue:** Proceedings of the Institution of Mechanical Engineers, Part B: Journal of Engineering Manufacture <br>
  > 🔑 **Keywords:** 3D packing, Deep reinforcement learning, Cavity representation, Spatiotemporal attention, Online packing <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online/sequential \| Single-container 3D packing \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: cavity map encoding empty-space topology plus temporal features of arriving or remaining items \| Action: select the item and its placement/orientation \| Reward: gap-ratio reduction and space-utilization improvement <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item dimensions and cavity-aware spatial representation \| Stability: geometric feasibility; no physical dynamics model reported \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: cavity-map representation with spatiotemporal-attention deep reinforcement learning \| Data: generated three-dimensional bin-packing instances \| Objective: reduce inaccessible cavities and improve final utilization <br>

- ❤️ **Column (and Row) Generation Algorithms for the Pallet Loading Problem** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.disopt.2025.100927-blue.svg)](https://doi.org/10.1016/j.disopt.2025.100927)
  > 👨‍🔬 **Authors:** Javier Marenco | 📅 **Year:** 2026 | 🏢 **Venue:** Discrete Optimization <br>
  > 🔑 **Keywords:** Pallet loading, Column generation, Row generation, Exact optimization, Packing patterns <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Manufacturer's pallet loading \| Identical rectangular boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (exact decomposition and generation algorithms) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known box and pallet dimensions \| Stability: layer-based geometric feasibility \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: column generation and simultaneous row-and-column generation formulations \| Data: standard pallet-loading benchmark instances \| Objective: maximize the number of boxes packed on a pallet <br>

- ❤️ **Differentiable Packing of Irregular 3D Objects with Adaptive Container Estimation** [![arXiv](https://img.shields.io/badge/arXiv-2606.16333-b31b1b.svg)](https://arxiv.org/abs/2606.16333)
  > 👨‍🔬 **Authors:** Palak Gupta; Shanmuganathan Raman | 📅 **Year:** 2026 | 🏢 **Venue:** arXiv preprint arXiv:2606.16333 <br>
  > 🔑 **Keywords:** 3D packing, Irregular objects, Differentiable optimization, Adaptive containers, Continuous pose optimization <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Joint object-placement and container-dimension optimization \| Irregular 3D mesh objects <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (gradient-based differentiable optimization) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known 3D object geometry and differentiable geometric proxies \| Stability: overlap and container-boundary losses; no physical stability model \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: a single differentiable optimization loop over 6-DoF object poses and three container dimensions \| Data: paper-reported irregular-object mesh sets \| Objective: minimize overlap, boundary violation, empty space, and container volume <br>

- ❤️ **Dynamic Dense Packing of Unknown Objects Based on Perception** [![DOI](https://img.shields.io/badge/DOI-10.1109%2FTASE.2026.3691769-blue.svg)](https://doi.org/10.1109/TASE.2026.3691769)
  > 👨‍🔬 **Authors:** Shichen Cao; Jing Xiao | 📅 **Year:** 2026 | 🏢 **Venue:** IEEE Transactions on Automation Science and Engineering <br>
  > 🔑 **Keywords:** Online packing, Robotic packing, Unknown objects, Perception, Force feedback <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online/dynamic \| Single-container robotic packing of continuously arriving objects \| Unknown rigid and selected non-rigid objects, including piled scenes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (perception, volumetric optimization, and robot-control framework) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: online visual perception and rapid object modeling under sensing uncertainty \| Stability: dense volumetric placement with physical execution feedback \| Execution: real robot picking/packing with force-torque pose correction <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: concurrent perception, rapid modeling, volumetric placement optimization, motion execution, and force/torque correction \| Data: real experiments with diverse previously unknown objects \| Objective: achieve high-density and reliable online packing under perception, modeling, and motion uncertainty <br>

- ❤️ **Green Bin Packing** [![DOI](https://img.shields.io/badge/DOI-10.1145%2F3788093-blue.svg)](https://doi.org/10.1145/3788093)
  > 👨‍🔬 **Authors:** Jackson Bibbens; Cooper Sigrist; Bo Sun; Shahin Kamali; Mohammad Hajiesmaili | 📅 **Year:** 2026 | 🏢 **Venue:** Proceedings of the ACM on Measurement and Analysis of Computing Systems <br>
  > 🔑 **Keywords:** Online packing, 1D bin packing, Energy cost, Competitive analysis, Cloud systems <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online \| Multi-bin one-dimensional packing with threshold-dependent overfilling cost \| Scalar-sized items <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (online-algorithm design and competitive analysis) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: arriving scalar item sizes and current bin loads \| Stability: not applicable to one-dimensional packing \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: online algorithms and competitive analysis for a bin-opening plus green-overfill cost model \| Data: adversarial/theoretical sequences and empirical cloud-workload-inspired tests \| Objective: minimize the combined number of opened bins and excess high-utilization cost <br>

- ❤️ **Nest Smarter, Not Harder: A Hybrid Vision-Based Deep Reinforcement Learning Agent for Packing 2D Irregular Geometries by Rotational Placement** [![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs10845-025-02620-6-blue.svg)](https://doi.org/10.1007/s10845-025-02620-6)
  > 👨‍🔬 **Authors:** Kirolos Abdou; Amgad Fakhry Ibrahim; Kai Binder; Marco F. Huber | 📅 **Year:** 2026 | 🏢 **Venue:** Journal of Intelligent Manufacturing <br>
  > 🔑 **Keywords:** 2D packing, Irregular objects, Deep reinforcement learning, Rotation, Vision-based representation <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Single-sheet/open-dimension 2D irregular packing \| Irregular planar geometries <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: visual/geometric representation of the partial layout and remaining part \| Action: choose rotational placement parameters, coupled with deterministic translation/placement logic \| Reward: weighted compactness/adherence and utilization score <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: rasterized or vision-based geometry representation \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: hybrid vision-based reinforcement-learning agent with rotational placement and geometric translation logic \| Data: open irregular-nesting datasets and paper-reported instances \| Objective: improve nesting utilization while learning transferable rotation decisions <br>

- ❤️ **PackingGPT: 3D Packing Agent for Real Furniture in Last-Mile Delivery** [![arXiv](https://img.shields.io/badge/arXiv-2608.01427-b31b1b.svg)](https://arxiv.org/abs/2608.01427)
  > 👨‍🔬 **Authors:** Yi You; Hui Li | 📅 **Year:** 2026 | 🏢 **Venue:** arXiv preprint arXiv:2608.01427 <br>
  > 🔑 **Keywords:** 3D packing, Furniture logistics, Irregular containers, Learning-based planning, Center of mass <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Furniture-box packing into partially occupied vehicle cargo spaces \| Heterogeneous weighted furniture packages and irregular sedan/SUV trunks <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (learning-guided sequential placement framework; no RL formulation reported) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: vehicle cargo-space geometry, existing load, package dimensions, weights, and center-of-mass features \| Stability: weight and center-of-mass constraints \| Execution: last-mile vehicle-loading planning; no robotic execution reported <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: PackingGPT sequential Lego-style placement agent with learned packing/center-of-mass guidance \| Data: real furniture-package records and simulated sedan/SUV cargo environments \| Objective: improve vehicle-space utilization while maintaining load-balance feasibility <br>

- ❤️ **Practical Mixed Palletizing Manipulator System: Incorporating Practical Reinforcement Learning and Configuration-Space Motion Planning** [![DOI](https://img.shields.io/badge/DOI-10.1109%2FTASE.2025.3637854-blue.svg)](https://doi.org/10.1109/TASE.2025.3637854)
  > 👨‍🔬 **Authors:** Woo-Jin Ahn; Kyuwon Choi; Seong-Woo Kang; Cheol-Kyun Rho; Dong-Sung Pae; Myo-Taeg Lim | 📅 **Year:** 2026 | 🏢 **Venue:** IEEE Transactions on Automation Science and Engineering <br>
  > 🔑 **Keywords:** Online packing, Robotic palletization, Deep reinforcement learning, Motion planning, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Online/sequential \| Robotic mixed pallet loading \| Rigid cuboid boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** State: pallet configuration and available/current-box features \| Action: choose a box placement satisfying practical feasibility \| Reward: pallet-volume utilization with practical stability-enhancing terms <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: camera-based box recognition and known pallet state \| Stability: practical reward terms and placement checks promote stable layouts \| Execution: CMPNet configuration-space collision-free motion planning on a real conveyor-fed manipulator system <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: PMP-RL palletizing policy plus behavior-cloned CMPNet motion planner \| Data: simulation and real-world palletizing experiments \| Objective: maximize utilization, placement stability, and collision-free execution efficiency <br>

- ❤️ **Robot-human coordination for pallet loading in a parts-to-picker order-picking system** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cie.2026.112067-blue.svg)](https://doi.org/10.1016/j.cie.2026.112067)
  > 👨‍🔬 **Authors:** António Galrão Ramos; Andreia Correia; Frederico M. Borges | 📅 **Year:** 2026 | 🏢 **Venue:** Computers & Industrial Engineering <br>
  > 🔑 **Keywords:** Scope-adjacent, Pallet loading, Human-robot coordination, Warehouse scheduling, AMR <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Scope-adjacent warehouse coordination \| Uses predefined pallet-loading sequences, not a packing-layout policy \| Palletized retail goods <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (mixed-integer warehouse coordination model) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known orders, stock pallets, AMR availability, and predefined loading sequences \| Stability: inherited from the predefined pallet-loading plan \| Execution: coordinates AMRs and human operators in a parts-to-picker system <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: mixed-integer programming with a lexicographic multi-objective function \| Data: 81 computational warehouse instances \| Objective: minimize makespan and stock-pallet use while maximizing AMR–pallet pairing continuity <br>

- ❤️ **Solving a Large-Scale 3D Packing Problem with Robot Constraints** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.cor.2025.107373-blue.svg)](https://doi.org/10.1016/j.cor.2025.107373)
  > 👨‍🔬 **Authors:** Liang Chen; Sheng Zhang; Mengmeng Ding; Huimin Chen; Jiacheng Ren; Xiaoli Yue | 📅 **Year:** 2026 | 🏢 **Venue:** Computers & Operations Research <br>
  > 🔑 **Keywords:** 3D packing, Robotic packing, Large-scale optimization, Robot constraints, Stability <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/sequential \| Large-scale single-container/pallet packing with continuous robot loading \| Rigid cuboids <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (industrial-scale constructive and search algorithm) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known items, container/pallet geometry, order groups, weights, and robot workspace \| Stability: support, load-bearing, and center-of-gravity constraints \| Execution: robot workspace, end-effector crossover depth, placement sequence, and continuous-loading constraints <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: industrial-scale sequence-and-assignment construction with robot-feasibility filtering and improvement search \| Data: industrial and generated instances containing up to thousands of boxes \| Objective: achieve high loading rate rapidly while satisfying robot, stability, order, and balance constraints <br>

- ❤️ **The Three-Dimensional Bin Packing Problem with Variable Box Size** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.tre.2026.105038-blue.svg)](https://doi.org/10.1016/j.tre.2026.105038)
  > 👨‍🔬 **Authors:** Xiangbin Xu; Boyu Wu; Zhongqiang Ma; Yugang Yu | 📅 **Year:** 2026 | 🏢 **Venue:** Transportation Research Part E: Logistics and Transportation Review <br>
  > 🔑 **Keywords:** 3D packing, Variable box size, Mathematical programming, Beam search, Packaging optimization <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Joint package-dimension design and three-dimensional packing \| Rigid cuboids packed into a variable-dimension outer box <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (mixed-integer formulation and beam-search method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known item geometry and constraints on the outer box dimensions/volume \| Stability: geometric non-overlap only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: mixed-integer programming formulation and tailored beam search \| Data: generated and paper-reported benchmark instances \| Objective: jointly choose feasible outer-box dimensions and item layout to reduce packaging size/cost <br>

- ❤️ **Voxelization-Based Variable Neighborhood Tabu Search Strategy for Three-Dimensional Irregular Strip Packing** [![DOI](https://img.shields.io/badge/DOI-10.3390%2Fmath14091570-blue.svg)](https://doi.org/10.3390/math14091570)
  > 👨‍🔬 **Authors:** Yue He; Shishun Cheng; Zhuo Xie; Shaowen Yao; Lijun Wei | 📅 **Year:** 2026 | 🏢 **Venue:** Mathematics <br>
  > 🔑 **Keywords:** 3D packing, Irregular objects, Voxelization, Variable neighborhood search, Tabu search <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline \| Three-dimensional irregular strip packing \| Irregular rigid objects with discrete rotations <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (variable-neighborhood tabu-search method) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: voxelized object and strip geometry \| Stability: geometric non-overlap and boundary feasibility only \| Execution: no robotic execution <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: adaptive-resolution voxelization with largest-volume-first construction and variable-neighborhood tabu search \| Data: Chess, Engine, Merged, and paper-reported irregular-object benchmarks \| Objective: minimize strip height while maintaining collision-free packing <br>

- ❤️ **An integrated simulation framework enabling flexible robotic palletizing** [![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.rcim.2026.103347-blue.svg)](https://doi.org/10.1016/j.rcim.2026.103347)
  > 👨‍🔬 **Authors:** Martina Salami; Pietro Bilancia; Marcello Pellicciari | 📅 **Year:** 2027 | 🏢 **Venue:** Robotics and Computer-Integrated Manufacturing <br>
  > 🔑 **Keywords:** Robotic palletization, Simulation framework, Digital twin, Heuristics, Robot code generation <br>
  > ⚙️ **Settings & Evidence:** <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 📦 **Task:** Offline/batch \| Robotic Europallet loading and executable process generation \| Rigid cuboid boxes <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 🎯 **RL Formulation:** Not applicable (constructive heuristic and simulation-based engineering framework) <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; 👁️ **Physics & Vision:** Observation: known box/pallet data and a 3D digital model of the robotic cell \| Stability: layer mass ordering and center-of-gravity balancing \| Execution: RoboDK validation, KUKA code generation, and online instruction streaming <br>
  > &nbsp;&nbsp;&nbsp;&nbsp; ⚖️ **Algo & Data:** Method: layered Guillotine-plus-Best-Fit packing, load-balancing logic, RoboDK simulation, and automatic robot-code deployment \| Data: industrially representative KUKA palletizing scenarios and released reproduction data \| Objective: accelerate layout generation, virtual validation, programming, and deployment while preserving pallet fill and balance <br>
