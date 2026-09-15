# syntheticChemistry

**Scientific validation springs for the [ecoPrimals](https://github.com/ecoPrimals) ecosystem.**

9 springs reproduce 175+ peer-reviewed papers in Pure Rust on commodity GPUs.
No NumPy, no SciPy, no CUDA. f64 precision via WebGPU/WGSL.

**Live site:** [sporeprint.primals.eco](https://sporeprint.primals.eco) &nbsp;|&nbsp; **Lab results:** [sporeprint.primals.eco/lab](https://sporeprint.primals.eco/lab/)

---

### Springs

| Spring | Domain | What it validates |
|--------|--------|-------------------|
| [hotSpring](https://github.com/syntheticChemistry/hotSpring) | Physics | Lattice QCD, molecular dynamics, fluid mechanics |
| [wetSpring](https://github.com/syntheticChemistry/wetSpring) | Biology | Metagenomics, analytical chemistry, mathematical biology |
| [neuralSpring](https://github.com/syntheticChemistry/neuralSpring) | ML & spectral | Anderson localization, protein folding, spectral analysis |
| [airSpring](https://github.com/syntheticChemistry/airSpring) | Agriculture | FAO-56 evapotranspiration, Richards equation, irrigation |
| [groundSpring](https://github.com/syntheticChemistry/groundSpring) | Geochemistry | Measurement noise, mineral dissolution, inverse problems |
| [healthSpring](https://github.com/syntheticChemistry/healthSpring) | Health | PK/PD, microbiome, biosignal, toxicology |
| [ludoSpring](https://github.com/syntheticChemistry/ludoSpring) | Game science | Flow theory, procedural generation, HCI |
| [primalSpring](https://github.com/syntheticChemistry/primalSpring) | Composition | Multi-node bonding, deploy graphs, ecosystem overwatch |
| [rustChip](https://github.com/syntheticChemistry/rustChip) | Neuromorphic | AKD1000 characterization, NPU drivers, echo state networks |

### How springs work

Each spring reproduces published experiments end-to-end in Rust.
Results are validated against paper-reported values within stated tolerances.
GPU compute uses [barraCuda](https://github.com/ecoPrimals/barraCuda) (WebGPU/WGSL) —
runs on any Vulkan-capable GPU (AMD, NVIDIA, Intel).

Browse reproduced results: [sporeprint.primals.eco/lab](https://sporeprint.primals.eco/lab/)

### Part of ecoPrimals

syntheticChemistry springs compose with [ecoPrimals](https://github.com/ecoPrimals) infrastructure primals.
Each spring is a standalone Rust crate that discovers and bonds with primals at runtime.

<sub>AGPL-3.0 · Pure Rust · No cloud, no vendor, no C.</sub>
