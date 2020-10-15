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

## Building FFTW3  
Refer to Build_FFTW.txt  
