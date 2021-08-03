# linux_system_processing

## User mode and kernel mode 
User mode is mode for user use, if thay want access in hardware of system, system while change the user mode to kernel mode

## Library 
The library contains several functions together and they form a package or library. The library help to reuse the code by avoiding writing same code again and again 

## System call

Have 2 way to system calls can be invoked
- Directly calling the system call
- User call the library function, and inturn call system calls when want to use

The way to the user call run: is go from the user mode go to library and go to hardwareand return.
