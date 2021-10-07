### Output files
The code performs output through the library 2DECOMP, which dumps one binary file for each field. The results can be then visualized through the files available in the folder `src/data/`. In order to do so, the file `param.f90` needs to be modified coherently with the simulation setup. Afterwards, the visualization file `viewfield.xdmf` can be generated by running the command `sh genview.sh`.