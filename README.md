# Maligi chetan
This repo is intended to document the weekly progress
# A 4-week Research Internship on RISC-V using VSDSquadron Mini RISC-V Dev Board
<details>
  
<summary><b>Task 1:</b></summary>

1. install RISC-V GNU Toolchain

2. install Yosys

3. install iverilog

4. install gtkwave

# CLONING RISC-V GNU TOOLCHAIN

sudo apt install git-all # To install git

sudo apt-get install autoconf automake autotools-dev curl python3 libmpc-dev libmpfr-dev libgmp-dev gawk build-essential bison flex texinfo gperf libtool patchutils bc zlib1g-dev libexpat-dev make sure to install the dependencies
![gnv tool chain](https://github.com/Chetanmaligi/maligichetan/assets/154491089/4d74bdbe-e908-4537-8c74-e5bcef9d6641)


# Create a opt dir
mkdir /opt/riscv try sudo incase of permission denial

In my case I created a driectory mkdir riscv 


# INSTALLING IVERILOG GTKWAVE & YOSYS

# YOSYS

git clone https://github.com/YosysHQ/yosys.git
cd yosys 
sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev\libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
make 
sudo make install

![yosys2](https://github.com/Chetanmaligi/maligichetan/assets/154491089/c2d74cd6-b90b-4a64-be01-6f1b2d47e6f4)

![yosys3](https://github.com/Chetanmaligi/maligichetan/assets/154491089/2d8a804a-6d1b-41d8-948f-b5e504a3e32c)



# iVerilog

sudo apt-get install iverilog
![iverilog](https://github.com/Chetanmaligi/maligichetan/assets/154491089/6ce10088-0291-4df6-9d34-fceedd251035)


# GTkWave

sudo apt-get install gtkwave

![gtk install](https://github.com/Chetanmaligi/maligichetan/assets/154491089/7bec8222-f4c6-43fe-8643-3ab1c75920e4)
![gtk wave](https://github.com/Chetanmaligi/maligichetan/assets/154491089/e4a75a0f-e672-4a38-b9f4-fd21c0440f38)


