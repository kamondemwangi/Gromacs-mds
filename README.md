# Gromacs-molecular dynamics simulations(mds)
MDS scripts for in silico vaccine project

Molecular dynamics(MD) simulations are done to evaluate vaccine stability using GROMACS 2018.2,
simulation is done in a cubic box defined under periodic boundary conditions (PBC) with the protein
complexes having 1.0nm distance between the complex and the wall of the simulation box. The vaccine receptor
complexes are solvated with SPC216 water molecules.The system is then neutralized by addition of
either NA+/CL- ions , the Amber99sb force field is used to determine the intermolecular and intramolecular
interactions during the MD simulation process (Hornak et al., 2006). Particle Mesh Ewald(PME) for long-range
electrostatics method are used to evaluate the long range electrostatic interactions, in addition The LINCS algorithm is used to constrain all bonds. Energy minimization of the system is then done using the steepest descents algorithm, this is done to relax the system.
