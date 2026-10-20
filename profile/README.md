# syntheticChemistry

**Scientific validation springs for the [ecoPrimals](https://github.com/ecoPrimals) ecosystem.**

10 springs reproduce 175+ peer-reviewed papers in Pure Rust on commodity GPUs.
No NumPy, no SciPy, no CUDA. f64 precision via WebGPU/WGSL.

**Live site:** [sporeprint.primals.eco](https://sporeprint.primals.eco) &nbsp;|&nbsp; **Lab results:** [sporeprint.primals.eco/lab](https://sporeprint.primals.eco/lab/)

---

### Springs

| Spring | Domain | What it validates |
|--------|--------|-------------------|
| [hotSpring](https://github.com/syntheticChemistry/hotSpring) | Physics | Lattice QCD, molecular dynamics, warm dense matter |
| [wetSpring](https://github.com/syntheticChemistry/wetSpring) | Biology | Metagenomics, analytical chemistry, mathematical biology |
| [neuralSpring](https://github.com/syntheticChemistry/neuralSpring) | ML & spectral | Anderson localization, protein folding, spectral analysis |
| [airSpring](https://github.com/syntheticChemistry/airSpring) | Agriculture | FAO-56 evapotranspiration, Richards equation, irrigation |
| [groundSpring](https://github.com/syntheticChemistry/groundSpring) | Geochemistry | Measurement noise, mineral dissolution, inverse problems |
| [healthSpring](https://github.com/syntheticChemistry/healthSpring) | Health | PK/PD, microbiome, biosignal, toxicology |
| [ludoSpring](https://github.com/syntheticChemistry/ludoSpring) | Game science | Flow theory, procedural generation, HCI |
| [primalSpring](https://github.com/syntheticChemistry/primalSpring) | Composition | Multi-node bonding, deploy graphs, ecosystem overwatch |
| [coralForge](https://github.com/syntheticChemistry/coralForge) | Structure | AlphaFold2/3 primitives, structure prediction |
| [rustChip](https://github.com/syntheticChemistry/rustChip) | Neuromorphic | AKD1000/1500/2500 drivers, NPU inference, echo state networks |

---

### baseCamp — Relay Points for New Frontier Travelers

Each baseCamp paper is a validated entry point into a domain. Pick any paper
that matches your field — it links directly to the spring(s) that reproduce
the science, runnable on your machine.

#### Physics & Computing

| # | Paper | Status | Springs |
|---|-------|--------|---------|
| 07 | **Sovereign Warm Dense Matter on Consumer GPU** | ✅ validated | [hotSpring](https://github.com/syntheticChemistry/hotSpring), neuralSpring, groundSpring |
| 10 | **First Dynamical QCD Production on Consumer GPU** | ✅ complete | [hotSpring](https://github.com/syntheticChemistry/hotSpring), neuralSpring, groundSpring |
| 25 | **Self-Tuning Simulation — Physics-Validated Parameter Discovery** | 🔧 phases 1-4 | [hotSpring](https://github.com/syntheticChemistry/hotSpring) |
| 15 | **Self-Routing Precision Brain for Heterogeneous GPU Compute** | ✅ validated | [hotSpring](https://github.com/syntheticChemistry/hotSpring) |
| 11 | **Nautilus Shell — Evolutionary Reservoir Computing** | ✅ validated | hotSpring, [neuralSpring](https://github.com/syntheticChemistry/neuralSpring) |

#### Biology & Ecology

| # | Paper | Status | Springs |
|---|-------|--------|---------|
| 01 | **Anderson Localization as QS Null Hypothesis** | ✅ validated | [wetSpring](https://github.com/syntheticChemistry/wetSpring), hotSpring, groundSpring, neuralSpring |
| 05 | **Cross-Species Signaling in Symbiotic Systems** | ✅ validated | [wetSpring](https://github.com/syntheticChemistry/wetSpring), neuralSpring, groundSpring |
| 06 | **Anderson Localization as No-Till Soil Health** | ✅ validated | wetSpring, [airSpring](https://github.com/syntheticChemistry/airSpring), groundSpring, neuralSpring |
| 16 | **Anaerobic-Aerobic QS Phase Transition** | ✅ comp. validated | wetSpring, healthSpring, airSpring, neuralSpring, groundSpring |
| 02 | **Extending the Frozen Fossil Record** | 📋 proposal | wetSpring, neuralSpring, groundSpring, hotSpring |

#### Health & Immunology

| # | Paper | Status | Springs |
|---|-------|--------|---------|
| 12 | **Anderson Localization in Immunological Signaling** | ✅ validated | [wetSpring](https://github.com/syntheticChemistry/wetSpring), neuralSpring, airSpring, groundSpring |
| 13 | **Sovereign Human Health Computing** (9 clinical tracks) | ✅ validated | [healthSpring](https://github.com/syntheticChemistry/healthSpring), wetSpring, groundSpring |
| 22 | **Zero-Knowledge Medical Provenance** | ✅ validated | [ludoSpring](https://github.com/syntheticChemistry/ludoSpring), healthSpring |

#### Agriculture & Edge

| # | Paper | Status | Springs |
|---|-------|--------|---------|
| 03 | **Precision Microbiome for Tree Crops** | 📋 proposal | wetSpring, [airSpring](https://github.com/syntheticChemistry/airSpring), groundSpring |
| 04 | **Microbial Sentinels** — NPU validated on live AKD1000 | ✅ live hardware | wetSpring, neuralSpring, [rustChip](https://github.com/syntheticChemistry/rustChip) |
| 08 | **Neuromorphic Edge Intelligence for Agricultural IoT** | ✅ live hardware | [airSpring](https://github.com/syntheticChemistry/airSpring), wetSpring, [rustChip](https://github.com/syntheticChemistry/rustChip) |
| 09 | **Sovereign Field Genomics — Nanopore + NPU** | 🔧 architecture | wetSpring, airSpring, neuralSpring, [rustChip](https://github.com/syntheticChemistry/rustChip) |

#### Games, Provenance & Economics

| # | Paper | Status | Springs |
|---|-------|--------|---------|
| 17 | **Game Design as Rigorous Science** | ✅ validated | [ludoSpring](https://github.com/syntheticChemistry/ludoSpring), wetSpring, hotSpring |
| 18 | **RPGPT — Sovereign RPG Engine** | 🔧 architecture | [ludoSpring](https://github.com/syntheticChemistry/ludoSpring) |
| 19 | **Games@Home — Distributed Human Computation** | ✅ validated | [ludoSpring](https://github.com/syntheticChemistry/ludoSpring) |
| 20 | **Novel Ferment Transcript Economics** | ✅ validated | [ludoSpring](https://github.com/syntheticChemistry/ludoSpring) |
| 21 | **Sovereign Sample Provenance** | ✅ validated | ludoSpring, wetSpring |

#### Composition

| # | Paper | Status | Springs |
|---|-------|--------|---------|
| 26 | **Primal Composition as Scientific Methodology** | ✅ validated | [ludoSpring](https://github.com/syntheticChemistry/ludoSpring), [primalSpring](https://github.com/syntheticChemistry/primalSpring) |

> **How to start**: Pick any ✅ paper. Clone the linked spring. Run `cargo test`.
> Every test reproduces a published result with documented provenance.
> No accounts, no API keys, no cloud. Just Rust and your hardware.

---

### How springs work

Each spring reproduces published experiments end-to-end in Rust.
Results are validated against paper-reported values within stated tolerances.
GPU compute uses [barraCuda](https://github.com/ecoPrimals/barraCuda) (WebGPU/WGSL) —
runs on any Vulkan-capable GPU (AMD, NVIDIA, Intel).

Browse reproduced results: [sporeprint.primals.eco/lab](https://sporeprint.primals.eco/lab/)

### Part of ecoPrimals

syntheticChemistry springs compose with [ecoPrimals](https://github.com/ecoPrimals) infrastructure primals.
Each spring is a standalone Rust crate that discovers and bonds with primals at runtime.

<sub>AGPL-3.0 · Pure Rust · No cloud, no vendor, no C · Kevin Mok / ecoPrimal / attsi · ORCID 0009-0004-2141-0321</sub>
