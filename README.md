# Description

This project aims to reproduce the results in the paper “[Game of Threads](https://dl.acm.org/doi/10.1145/3373376.3378462)” published in ASPLOS’20. We followed the experimental setup documented in the paper and performed the experiment using the [artifact](https://zenodo.org/record/3628042).

## Hardware Setup
- SGX-enabled CPU: Intel(R) Core(TM) i5-6500 CPU @ 3.20GHz
- RAM: 16GB

## Software Setup
- Host OS: Ubuntu 20.04 LTS
- Software
    - [linux-sgx](https://github.com/intel/linux-sgx): Intel SGX driver for Linux
    - [Docker](https://www.docker.com/): Perform the experiments in the isolated environment
    - TBD
