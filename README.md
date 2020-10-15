# 50000025_NAMD_HPCAI
 // Authored by: Solomon Haw Wei Wern
 // For APAC HPC-AI Competition 2020 
 // Team Curtin

## Build Guideline

## Getting the necessary files
    $ export WORK_DIR=path/to/work/dir<path to your working directory>

Refer to Get_Essential_Files.txt

To get access to apacsc11 NAMD working directory:

    $ setfacl -m u:pengzhi:xr /home/users/industry/ai-hpc/apacsc11/scratch/apacsNAMD
 
    $ setfacl -R -m u:pengzhi:xr /home/users/industry/ai-hpc/apacsc11/scratch/apacsNAMD

To export GCC 8.4.0 in apacsc11 NAMD working directory to PATH:
   
    $ export PATH=$HOME/scratch/apacsNAMD/cluster/gcc840-build/bin:$PATH

    $ export LD_LIBRARY_PATH="$HOME/scratch/apacsNAMD/cluster/gcc840-build/lib:$HOME/scratch/apacsNAMD/cluster/gcc840-build/lib64:$LD_LIBRARY_PATH"

    $ export CC=$HOME/scratch/apacsNAMD/cluster/gcc840-build/bin/gcc
    $ export CXX=$HOME/scratch/apacsNAMD/cluster/gcc840-build/bin/g++
    $ export FC=$HOME/scratch/apacsNAMD/cluster/gcc840-build/bin/gfortran

## Building FFTW3 
Refer to Build_FFTW.txt

## Building Charm++
Refer to Build_Charm.txt

