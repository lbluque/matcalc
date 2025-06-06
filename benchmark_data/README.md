### [wbm-random-pbe52-equilibrium-2025.1.json.gz](wbm-random-pbe52-equilibrium-2025.1.json.gz)
- Relaxed structure, un-/corrected energy and un-/corrected formation energy per atom of random sampled structures in [WBM] downloaded in Jan 2025.
- Excludes deprecated structures, see [Materials Project Documentation] and [pymatgen#2968] for details.
- Corrects energy using MaterialsProject2020Compatibility.
- Uses PBE PAW datasets version 52.
- 972 materials.

### [mp-binary-pbe-elasticity-2025.1.json.gz](mp-binary-pbe-elasticity-2025.1.json.gz)
- Elastic moduli of binaries in [Materials Project] downloaded in Jan 2025.
- Excludes K > 500 and G > 500 structures as well as a few bad structures.
- 3953 materials.

### [mp-pbe-elasticity-2025.3.json.gz](mp-pbe-elasticity-2025.3.json.gz)
- All available elastic moduli in [Materials Project] downloaded in Mar 2025.
- Excludes K <= 0, K > 500 and G <= 0, G > 500 structures.
- Excludes H2, N2, O2, F2, Cl2, He, Xe, Ne, Kr, Ar
- Excludes materials with density < 0.5 (less dense than Li, the least density solid element)
- 12122 materials.

### [alexandria-binary-pbe-phonon-2025.1.json.gz](alexandria-binary-pbe-phonon-2025.1.json.gz)
- Heat capacity at 300 K of binaries in [Alexandria Materials Database] downloaded in Jan 2025.
- Excludes deprecated structures.
- 1170 materials.

### [alexandria-pbe-phonon-2025.3.json.gz](alexandria-pbe-phonon-2025.3.json.gz)
- All available heat capacity at 300 K in [Alexandria Materials Database] downloaded in Mar 2025.
- Excludes deprecated structures.
- 9865 materials.

### [wbm-high-energy-states.json.gz](wbm-high-energy-states.json.gz)
- All available forces in [WBM high energy states] downloaded in Jan 2025.
- Uses PBE PAW datasets version 52.
- 972 materials, 9308 structures.

### [mvl-batt-sub-pbe-diffusion-2025.5.json.gz](mvl-batt-sub-pbe-diffusion-2025.5.json.gz)
- Mean square displacement, diffusion coefficient and ionic conductivity at various temperatures of well-known battery materials studied by [Materials Virtul Lab] over the past decade, collated in May 2025.
- Li3ClO, Li10Ge(PS6)2, Li3PS4, Li6PS5Cl, Li3YBr6, Li3YCl6, Na2ZrCl6, Na3PS4, Na3Zr2Si2PO12, Na5YZrCl12.
- 101 calculations.

[WBM]: https://figshare.com/articles/dataset/Matbench_Discovery_v1_0_0/22715158
[Materials Project]: http://materialsproject.org
[Alexandria Materials Database]: https://alexandria.icams.rub.de
[WBM high energy states]: https://figshare.com/articles/dataset/WBM_high_energy_states/27307776?file=50005317
[Materials Virtul Lab]: http://www.mavrl.org
[Materials Project Documentation]: https://docs.materialsproject.org/methodology/materials-methodology/calculation-details/gga+u-calculations/pseudopotentials
[pymatgen#2968]: https://github.com/materialsproject/pymatgen/issues/2968
