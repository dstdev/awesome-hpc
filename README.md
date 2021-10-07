# Awesome HPC
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[High Performance Computing (HPC)](https://en.wikipedia.org/wiki/Supercomputer) most generally refers to the practice of aggregating computing power in a way that delivers much higher performance than one could get out of a typical desktop computer or workstation in order to solve large problems in science, engineering, or business.

This is a repository of [Free](https://en.wikipedia.org/wiki/Free_software) and Non-Free tools for use in HPC.



## Provisioning
* [Grendel](https://grendel.readthedocs.io/) | [Repo](https://github.com/ubccr/grendel) - Bare Metal Provisioning system for HPC Linux clusters `GPL-3`
* [XCat](https://xcat.org/) | [Repo](https://github.com/xcat2/xcat-core) - xCAT is a toolkit for deployment and administration of clusters of all sizes `EPL-1.0`
* [Warewulf](https://warewulf.hpcng.org/) | [Repo](https://github.com/hpcng/warewulf) - Warewulf is a stateless and diskless container operating system provisioning system for large clusters of bare metal and/or virtual systems. `BSD-3`
* [Rocks](http://www.rocksclusters.org/) - A Linux distribution for developing Linux clusters `other`
* [Cobbler](https://cobbler.github.io/) | [Repo](https://github.com/cobbler/cobbler) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments. `GPL-2.0`

## Workload Managers
* [Slurm](https://slurm.schedmd.com/documentation.html) | [Repo](https://github.com/SchedMD/slurm) - A free and open source job scheduler `OSS`
* [LSF/Spectrum Scale](https://www.ibm.com/products/hpc-workload-management) - A job scheduler and workload management software developed by IBM `Proprietary`
* [Moab](https://adaptivecomputing.com/moab-hpc-suite/) - Moab is a workload management and job scheduler `other`
* [Torque](https://en.wikipedia.org/wiki/TORQUE) - Torque is a workload management and job scheduler `other`
* [OpenLava](https://en.wikipedia.org/wiki/OpenLava) - OpenLava is a workload management and job scheduler `other`
* [UGE/SGE](https://en.wikipedia.org/wiki/Univa_Grid_Engine) - Univa Grid Engine is a workload management engine for HPC. `Proprietary`
* [Volcano](https://volcano.sh/) - Volcano is a batch system built on Kubernetes. `Apache-2.0`
* [Maui](https://www.mhpcc.hpc.mil/) - Maui is a workload management and job scheduler. `other`
* [Kube Batch](https://github.com/kubernetes-sigs/kube-batch) - A batch scheduler of kubernetes for high performance workload, e.g. AI/ML, BigData, HPC `Apache-2.0`

## Resource Manager
* [OpenPBS](https://www.openpbs.org/) | [Repo](https://github.com/openpbs/openpbs)- OpenPBS® software optimizes job scheduling and workload management in high-performance computing (HPC) environments `other`

## Pipelines
* [Nextflow](nextflow.io) - Data drive computational pipelines. `Apache-2.0`
* [Cromwell](https://cromwell.readthedocs.io/en/stable/) | [Repo](https://github.com/broadinstitute/cromwell)- Scientific workflow engine designed for simplicity & scalability.  `BSD-3`

## Applications
* [Spack](spack.io) | [Repo](https://github.com/spack/spack) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers. `other`
* [EasyBuild](https://easybuild.io/) | [Repo](https://github.com/easybuilders/easybuild) -  EasyBuild - building software with ease. `GPL-2` 

## Compilers
* [Nvidia](https://developer.nvidia.com/hpc-compilers) - NVIDIA HPC compiler suite for Fortran, C/C++ with OpenACC. `Proprietary`
* [Portland Group](https://www.pgroup.com/index.htm) - The Portland Group compilers were Fortran, C/C++ compilers now integrated into NVIDIA HPC SDK. `Proprietary`
* [Intel](https://software.intel.com/content/www/us/en/develop/tools/oneapi/all-toolkits.html#hpc-kit) - The Intel compiler suite offers many language compilers for use in the HPC space. `Proprietary`
* [Cray](https://bluewaters.ncsa.illinois.edu/cray-compiler) - A suite of compilers designed and optimized to target the AMD interlagos instruction set. `Proprietary`
* [GNU](https://gcc.gnu.org/) | [Repo](https://gcc.gnu.org/git.html) - The GNU Compiler Collection is a suite of compilers targeting many languages. `GPL-3`
* [LLVM](https://llvm.org/) | [Repo](https://github.com/llvm/llvm-project) - The LLVM project is a collection of modular compilers and toolchains. `OSS`

## MPI
* [OpenMPI](https://www.open-mpi.org/) | [Repo](https://github.com/open-mpi/ompi) - OpenMPI is an open source implementation of the MPI-3.1 standard. `BSD`
* [MPICH](mpich.org) | [Repo](https://github.com/pmodels/mpich) - MPICH is a high-performance and widely portable implementation of the MPI-3.1 standard. `other`
* [MVAPICH](https://mvapich.cse.ohio-state.edu/) - MVAPICH is an open source implementation of the MPI-3.1 standard developed by Ohio State University. `BSD`
* [Intel-MPI](https://mvapich.cse.ohio-state.edu/) - Intel-MPI is Intel's MPI-3.1 implementation included in their compiler suite. `other`

## Parallel Computing
* [ArrayFire](https://arrayfire.org/docs/index.htm) - A general purpose tensor library that simplifies the process of software development for parallel architectures. `other`
* [OpenMP](https://www.openmp.org/) | OpenMP is an application programming interface that supports multi-platform shared-memory multiprocessing programming. `other`

## Benchmark
* [OSU Benchmarks](https://mvapich.cse.ohio-state.edu/benchmarks/) - A collection of benchmarking tools for MPI developed by Ohio State University. `other`
* [Intel MPI Benchmarks](https://software.intel.com/content/www/us/en/develop/articles/intel-mpi-benchmarks.html) - A set of benchmarks developed by Intel for use with their Intel MPI. `other`
* [HPCC Systems](https://hpccsystems.com/) | [Repo](https://github.com/hpcc-systems/HPCC-Platform) - HPCC Systems (High Performance Computing Cluster) is an open source, massive parallel-processing computing platform for big data processing and analytics. `other`
* [LINPACK](https://www.netlib.org/linpack/) LINPACK is a set of efficient fortran subroutines for solving linear systems which benchmarks are useful for HPC. `other`
* [IOzone](https://www.iozone.org/) - IOzone is a filesystem benchmark tool. `OSS`
* [IOR](https://www.vi4io.org/tools/benchmarks/ior) - Interleaved or Random is a useful benchmarking tool for testing parallel filesystems. `other`
* [MDtest](https://www.vi4io.org/tools/benchmarks/mdtest) - MDtest is an MPI-based application for evaluating the metadata performance of a file system `other`

## Miscellaneous
* [OpenOnDemand](https://openondemand.org/) | [Repo](https://github.com/OSC/openondemand.org) - Open OnDemand helps computational researchers and students efficiently utilize remote computing resources by making them easy to access from any device. `MIT`
* [Open XDMod](https://open.xdmod.org) | [Repo](https://github.com/ubccr/xdmod/) - Open XDMoD is an open source tool to facilitate the management of high performance computing resources. `LGPL-3`

## Performance
* [TotalView](https://totalview.io/products/totalview) - TotalView is a debugging tool for HPC applications. `Proprietary`
* [Tau](https://www.cs.uoregon.edu/research/tau/home.php) - TAU Performance System® is a portable profiling and tracing toolkit for performance analysis of parallel programs written in Fortran, C, C++, UPC, Java, Python. `other`
* [Valgrind](https://www.valgrind.org/) | [Repo](https://sourceware.org/git/?p=valgrind.git) - Valgrind is a tool designed to profile programs to determine memory leaks. `GPL-2`
* [Paraver](https://tools.bsc.es/paraver) - Paraver is a very flexible data browser that is part of the CEPBA-Tools toolkit. ``
* Performance Application Programming Interface. `LGPL`
* [PAPI](http://icl.cs.utk.edu/papi) | [Repo](https://bitbucket.org/icl/papi/src/master/) - PAPI is a performance analysis tool. `other`

## Parallel Shells
* [pdsh](https://linux.die.net/man/1/pdsh) | [Repo](https://github.com/chaos/pdsh) - pdsh runs terminal commands across multiple hosts in parallel. `GPL-2`
* [ClusterShell](https://clustershell.readthedocs.io/en/latest/intro.html) | [Repo](https://github.com/cea-hpc/clustershell) - Scalable cluster administration Python framework. `LGPL-2.1` 

## Containers
* [Singularity](https://sylabs.io/singularity/) | [Repo](https://github.com/hpcng/singularity) - Singularity is an open source container system. `BSD`
* [Charliecloud](https://hpc.github.io/charliecloud/) | [Repo](https://github.com/hpc/charliecloud) - Charliecloud provides user-defined software stacks (UDSS) for high-performance computing (HPC) centers. `Apache-2.0`
* [Docker](https://www.docker.com/) - Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. `other`
* [uDocker](https://indigo-dc.github.io/udocker/) | [Repo](https://github.com/indigo-dc/udocker) - A basic user tool to execute simple docker containers in batch or interactive systems without root privileges. `Apache-2.0`
* [Shifter](https://www.nersc.gov/research-and-development/user-defined-images/) | [Repo](https://github.com/NERSC/shifter) -  Shifter - Linux Containers for HPC `other`
* [HPC Container Maker](https://github.com/NVIDIA/hpc-container-maker) - HPC Container Maker is an open source tool to make it easier to generate container specification files. `Apache-2.0`

## Environment Management
* [Lmod](https://lmod.readthedocs.io/en/latest/) | [Repo](https://github.com/TACC/Lmod) - Lmod: An Environment Module System based on Lua, Reads TCL Modules, Supports a Software Hierarchy `other`
* [Environment Modules](https://modules.readthedocs.io/en/latest/) | [Repo](https://github.com/cea-hpc/modules) - Environment Modules: provides dynamic modification of a user's environment  `GPL-2`
* [Anaconda](https://www.anaconda.com/) - Anaconda is a Python and R distribution for use in computational science. `other`
* [Mamba](https://mamba.readthedocs.io/en/latest/) | [Repo](https://github.com/mamba-org/mamba) - Mamba is a reimplementation of the conda package manager in C++. `BSD`

## Visualization
* [Visit](https://visit-dav.github.io/visit-website/) | [Repo](https://github.com/visit-dav/visit) - VisIt - Visualization and Data Analysis for Mesh-based Scientific Data. `BSD-3`

## Parallel Filesystems
* [GPFS](https://www.ibm.com/docs/en/gpfs/4.1.0.4?topic=guide-introducing-general-parallel-file-system) - GPFS is a high-performance clustered file system software developed by IBM. `Proprietary`
* [Quobyte](https://www.quobyte.com/storage-for/high-performance-computing-hpc?gclid=EAIaIQobChMI-fv1pfKG8wIV5x6tBh367Q5CEAAYASABEgJTgPD_BwE) - A high performance filesystem. `Proprietary`
* [Ceph](https://ceph.io/en/) | [Repo](https://github.com/ceph/ceph) - Ceph is a distributed object, block, and file storage platform. `other`
* [Weka](https://www.weka.io/) - A file system designed for HPC. `Proprietary` 
* [Lustre/Exascaler](https://www.lustre.org/) | [Repo](https://git.whamcloud.com/fs/lustre-release.git) - Lustre is an open-source, distributed parallel file system software platform designed for scalability, high-performance, and high-availability. `other`
* [BeeGFS](https://www.beegfs.io/c/) - BeeGFS is a hardware-independent POSIX parallel file system developed with a strong focus on performance and designed for ease of use, simple installation, and management. `Proprietary`
* [OrangeFS](http://www.orangefs.org/) | [Repo](https://github.com/waltligon/orangefs) - OrangeFS is a next generation parallel file system for Linux clusters. `other`

## Programming Languages
* [Julia](https://julialang.org/) - Julia is a high-level, high-performance dynamic language for technical computing. `MIT`
* [Futhark](futhark-lang.org) - Futhark is a purely functional data-parallel programming language in the ML family. `isc`
* [Chapel](https://chapel-lang.org/) - Chapel is a programming language designed for productive parallel computing at scale. `Apache-2.0`

## Journals
* [Journal of Super Computing](https://www.springer.com/journal/11227)

## Podcasts
* [This week in HPC](http://www.intersect360.com/industry/podcasts.php)
* [Exascaler Project](https://www.exascaleproject.org/podcast/)


## Blogs
* [HPCWire](hpcwire.com)
* [InsideHPC](insidehpc.com)
* [The Next Platform](nextplatform.com)
* [The Register HPC](http://www.theregister.co.uk/data_centre/hpc/)
* [Cray Computing Blog](blog.cray.com)
* [HPC at Dell](hpcatdell.com)
* [Scientific Computing World](http://www.scientific-computing.com/)
* [This week in HPC]()

## Conferences

* [Pearc](https://pearc.acm.org/) - Practice & Experience in Advanced Research Computing
* [Supercomputing (SC)](supercomputing.org) - The International Conference for High Performance Computing, Networking, Storage, and Analysis
* [Supercomputing International (ISC)](isc-hpc.com) - The International Conference for High Performance Computing, Networking, Storage, and Analysis
* [CCGrid](https://dl.acm.org/conference/ccgrid) - IEEE/ACM International Symposium on Cluster, Cloud and Internet Computing

## Training
* [Exascale Computing Project Training](https://www.exascaleproject.org/training-events/)

## References
* file:///tmp/Install_guide-Centos8-Warewulf-SLURM-2.3-aarch64.pdf
* [awesome self-hosted](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/README.md)
* [koallen/awesome-hpc][https://github.com/koallen/awesome-hpc] 
* [Awesome opensource HPC](https://awesomeopensource.com/projects/hpc)
