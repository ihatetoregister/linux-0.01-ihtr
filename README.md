linux-0.01 On Ubuntu 18.04 with GCC-7.3

This project contain modification to builds and run Linux verion 0.01 on a modern system. 

# Tested on
* Ubuntu 18.04, 32 and 64 bit
* Kali Linux 2022.3 (gcc (Debian 12.2.0-3) 12.2.0, as86 version: 0.16.17, QEMU emulator version 7.1.0 (Debian 1:7.1+dfsg-2))

# Dependencies
sudo apt install bin86 build-essential qemu-system
unzip hd_oldlinux.zip

# Build
make

# Run
The kernel runs in both qemu (gui or curses) and Bochs. 

    make run

    make run-curses


