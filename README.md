# all_gaff_chloroform

This is a signac projects used to simulate bulk solutions of acetonitrile, chloroform, and LiTFSI.

## Simulation Details
- GAFF Force field for acetonitrile, chloroform, and TFSI- anion
- Amber Force field for Li+ ion
- Acetonitrile, chloroform, and TFSI- partial charges calculated through RESP using Gaussian09 and the R.E.D Server
- Li+ and TFSI- partial charges scaled by 0.8
- Simulations run with GROMACS 2018.5

## Usage
The signac project can be initialized by running `python src/init.py` on the command line.  This command initializes the project and creates all of the necessary signac `jobs`.  Various commands can be executed by running `python src/project.py [command]`.

Requirements
- signac
- mBuild
- foyer
- MDTraj
- antefoyer
- gafffoyer
