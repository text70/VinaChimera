# VinaChimera
An extensible pipeline for molecular modeling and ligand docking.

Requirements:

Conda environment: ( [Miniconda](https://docs.conda.io/en/latest/miniconda.html#) is recomended)


[UCSF Chimera](https://www.cgl.ucsf.edu/chimera/download.html): Dowload the installer of your choice and follow the directions.

[Tangram](https://github.com/insilichem/tangram): a python environment for interactive extensions with other molecular modeling suites. Also see the Tangram_setup document for help activating the conda-env.

[AutoDock Vina](http://vina.scripps.edu/index.html): faster than Autodock and can be run locally on most modern multicore CPUs.

Open Babel: (make sure [wxWidgets](https://wiki.wxwidgets.org/Installing_and_configuring_under_Ubuntu) is up to date)```sudo snap install openbabel``` or ```sudo apt-get install openbabel```
then run ```obgui``` for the [GUI](https://open-babel.readthedocs.io/en/latest/GUI/GUI.html)


For further batch processing, files generated with this pipeline can be implemented in a parallel implementation of Autodock Vina, see [MPI-Vina](https://github.com/mokarrom/mpi-vina).


