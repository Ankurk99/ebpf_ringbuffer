The program prints PID and the filename for all the events executed during exec() syscall.

# To compile the program and the loader
clang -O2 -target bpf -g -c program.c

gcc -g -lbpf loader.c

# To run the program
sudo ./a.out
