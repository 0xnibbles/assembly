# The Fibonacci Sequence                                                                                                                                      
This assembly program accepts user input to know the maximum number to calculate the fibonacci sequence.

To compile the source code you can use NASM with the following commands:
> **nasm -f elf64 fib.s &&  ld fib.o -o fib -lc --dynamic-linker /lib64/ld-linux-x86-64.so.2 && ./fib**
