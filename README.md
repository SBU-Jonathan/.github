# COLA 

The COLA code is setup at [FML](https://github.com/SBU-Jonathan/FML) repository. We made installation easier with Conda. 

## Conda Cola Environment
Setup the Cola environment with the command:

     $(base) conda create --name cola python=3.7 --quiet --yes && \
               conda install -n cola --quiet --yes  \
                 'conda-forge::libgcc-ng=10.3.0' \
                 'conda-forge::libstdcxx-ng=10.3.0' \
                 'conda-forge::libgfortran-ng=10.3.0' \
                 'conda-forge::gxx_linux-64=10.3.0' \
                 'conda-forge::gcc_linux-64=10.3.0' \
                 'conda-forge::gfortran_linux-64=10.3.0' \
                 'conda-forge::openmpi=4.1.1' \
                 'conda-forge::git=2.33.1' \
                 'conda-forge::git-lfs=3.0.2' \
                 'conda-forge::cmake=3.21.3' \
                 'conda-forge::gsl=2.7' \
                 'conda-forge::openblas=0.3.18' \
                 'conda-forge::lapack=3.9.0' \
                 'conda-forge::cython=0.29.24' \
                 'conda-forge::numpy=1.21.4' \
                 'conda-forge::scipy=1.7.2' \
                 'conda-forge::pandas=1.3.4' \
                 'conda-forge::mpi4py=3.1.3' \
                 'conda-forge::matplotlib=3.5.0' \
                 'conda-forge::astropy=4.3.1' \
                 'conda-forge::lua=5.4.4' \
                 'conda-forge::cgal=5.4' \
                 'conda-forge::fftw=3.3.8=mpi_openmpi_h50a73e0_1014'
