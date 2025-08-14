# 4D-STEM Simulations

Code used in my bachelor project to simulate Four Dimensional Scanning Transmission Electron Microscopy (STEM) data from an MD trajectory and prepare it for downstream analysis. The workflow loads a LAMMPS dump of a Zr–Cu alloy, fixes metadata, averages the vibrating structure, and uses **abTEM** to generate a full 4D diffraction stack. Post-processing produces virtual ADF images, center-of-mass (CoM) maps, and a binned, axis-corrected dataset (`.npy`) ready for further analysis or ML.

