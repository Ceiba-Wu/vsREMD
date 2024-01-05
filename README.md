# vsREMD
GROMACS-2022.5

1) Downloads the source code of GROMACS 2022.5

https://manual.gromacs.org/2022.5/download.html

2) Replace replicaexchange.cpp

PATH: gromacs-2022.5/src/gromacs/mdrun/replicaexchange.cpp

3) Compile

https://manual.gromacs.org/2022.5/install-guide/index.html

4) Test

unzip vsremd-test-gmx2022.5-model.zip

cd vsremd-test-gmx2022.5-model

mpirun -np 40 gmx_mpi mdrun -v -deffnm md -multidir md0 md1 md2 md3 md4 -replex 10
