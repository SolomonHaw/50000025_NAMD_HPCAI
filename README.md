# 50000025_NAMD_HPCAI
 // Authored by: Solomon Haw Wei Wern
 // For APAC HPC-AI Competition 2020 
 // Team Curtin

## Build Guideline

## Getting the necessary files
export WORK_DIR=path/to/work/dir<path to your working directory>

### Charm git :

  $ git clone --bare https://github.com/UIUC-PPL/charm.git \
  $HOME/$WORK_DIR/github/charm.git

### NAMD git:

  $ git clone --bare https://charm.cs.illinois.edu/gerrit/namd.git \
  $HOME/$WORK_DIR/github/namd.git

### FFTW3 tar file:

  $ wget http://www.fftw.org/fftw-3.3.8.tar.gz \
  $ -O $HOME/$WORK_DIR/code/fftw-3.3.8.tar.gz

### HPC-X v2.6 tar file:

  $ wget http://content.mellanox.com/hpc/hpc-x/v2.6/hpcx-v2.6.0-gccMLNX_OFED_LINUX-4.7-1.0.0.1-redhat7.7-x86_64.tbz \
  $ -O $HOME/$WORK_DIR/code/hpcx-v2.6.0-gcc-MLNX_OFED_LINUX-4.7-1.0.0.1-redhat7.7-
x86_64.tbz

### UCX git
This is an alternate method of getting UCX, not neccessary if 
UCX in the HPC-X package works.

  $ git clone --bare https://github.com/openucx/ucx.git \
  $HOME/$WORK_DIR/github/ucx.git
  
### OpenMPI git
This is an alternate method of getting OpenMPI, not neccessary if 
OpenMPI in the HPC-X package works. 

  $ git clone --bare https://github.com/open-mpi/ompi.git \
  $HOME/$WORK_DIR/github/ompi.git
