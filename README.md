# VSD_SoC_tapeout
# Week-0
## SoC Design flow
<img width="1149" height="585" alt="image" src="https://github.com/user-attachments/assets/9da2bda6-4362-4d0d-af89-ad123c062b6a" />
Learnt about how an SoC is designed from gcc output as reference and then extrapolating that to hardware , then writing the RTL design for the SoC , during sythesis digital elements are to be synthesizable by gates and analog stuff by mosfets.
All this is then integrated to an SoC , and later floorplanning , place and route.

## Installing necesarry software
### yosys
```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make (If make is not installed please install it)
$ sudo apt-get install build-essential clang bison flex \
libreadline-dev gawk tcl-dev libffi-dev git \
graphviz xdot pkg-config python3 libboost-system-dev \
libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install
```
<img width="885" height="178" alt="image" src="https://github.com/user-attachments/assets/a8d862e4-8904-4302-8dae-f437b2df2963" />


### iverilog
Steps to install iverilog 
```bash
$ sudo apt-get update
$ sudo apt-get install iverilog
```
<img width="885" height="579" alt="image" src="https://github.com/user-attachments/assets/ecbb8602-e6f5-499e-b571-cac6a910b83e" />

###gtkwave
```bash
$ sudo apt-get update
$ sudo apt install gtkwave
```
<img width="885" height="128" alt="image" src="https://github.com/user-attachments/assets/b2ad4b27-330a-48cc-9f2f-cae0aa9f04de" />
