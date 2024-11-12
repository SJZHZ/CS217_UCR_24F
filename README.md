# CS217_UCR_24F
A Collection
## GPGPU-sim
1. Install [Docker Link](https://socal-ucr.github.io/GPGPU-sim-container/)

    1. Download
        ```bash
        docker run -w /root -it socalucr/gpgpu-sim /bin/bash
        ```
    2. Compile
        ```bash
        cd ~/gpgpu-sim_distributionsource setup_environment
        make clean
        make
        ```
2. Usage
    ```bash
    cd ~/gpgpu-sim_distribution/ && source ~/gpgpu-sim_distribution/setup_environment
    cd $DIR && mkdir sim && cd sim && cp -a ~/gpgpu-sim_distribution/configs/GTX480/* .
    cp ../$FILE . && ./$FILE &> outfile
    ```
