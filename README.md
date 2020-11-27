## stm32f446 hello world gnuc
Use gnuc compile stm32 lightweight bare-metal system, just include startup
assembly code.

## tool setup
sudo apt-get install st-util  
download arm-none-eabi-gdb in web `https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads`  

## usage
One terminator input `st-util`, the oter input `arm-none-eabi-gdb -ex 'target extended-remote:4242' /home/jim/stm32/fos.elf` and then input `load`

## GDB command
break function  
continue/run  
step/next  
display var  
bt: show the stack  
list: show the code  
b/c/s/n/display/bt  

## author
Jim, license MIT
