Modified Effective Bandwidth (b_eff) Benchmark (version 3.6 + bugfix 3.6.0.1)
Original website: https://fs.hlrs.de/projects/par/mpi//b_eff/

Author: Xiaolong Huang (2021)

Major changes:
1) Random pattern uses MPI_COMM_WORLD instead of random_comm
2) Skip data verification so that SimGrid can use shared malloc
