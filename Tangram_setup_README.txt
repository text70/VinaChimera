//Installation of Tangram Environment for use with Chimera

install Tangram env  https://github.com/insilichem/tangram

~$conda create -n tangram -c insilichem/label/dev -c insilichem -c omnia -c rdkit -c conda-forge tangram

//activate the conda tangram environment
~$conda-env list
~$conda-env tangram

//for updates
~$conda update tangram

//should work in all shells
~$pychimera --gui



