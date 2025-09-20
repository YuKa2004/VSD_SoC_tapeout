# VSD_SoC_tapeout
# Week-0
## SoC Design flow
<img width="1149" height="585" alt="image" src="https://github.com/user-attachments/assets/9da2bda6-4362-4d0d-af89-ad123c062b6a" />

Key learnings:
- Gained insight into how a **System-on-Chip (SoC)** is designed, beginning with understanding the **GCC compiler output** as a reference for expected hardware behavior.
- Learned how to **translate software-level operations** into **hardware-level RTL design** (Register Transfer Level).
- Understood that:
  - During **synthesis**, **digital logic elements** are mapped to standard gates.
  - **Analog components**, if any, are mapped at the **transistor level** (MOSFETs).
- Realized the importance of how all these building blocks are **integrated into a complete SoC**, setting the stage for:
  - **Floorplanning**
  - **Placement**
  - **Routing**
  - And eventually generating the **GDSII** layout used for fabrication.



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

