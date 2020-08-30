# os_xv6
운영체제 수업 - xv6 프로젝트. 나만의 운영체제 만들기

## xv6 Operating System
- Unix-like teaching os developed by MIT
- Based on multiprocessor x86 system

## Project Assginment
0. starting xv6 OS
1. system call
2. thread
3. syncronization
4. scheduling
5. page fault handler

## How to install and run
### Install and Build xv6
1. (Move to directory where to install xv6)
2. $wget http://csl.skku.edu/uploads/SWE3004S19/xv6-skku.tar.gz
3. $tar –xvf xv6-skku.tar.gz

### Install qemu emulator
1. $sudo apt install qemu

### Run and Terminate xv6
1. $cd xv6-public
2. $make qemu-nox
3. $halt
