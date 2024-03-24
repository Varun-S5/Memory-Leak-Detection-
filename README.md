# Memory-Leak-Detection-

The Memory Leak Detection Tool is implemented as a library (mld.h)

Inorder to run the code, first compile the mld library using the command
gcc -g -c mld.c -o mld.o

then to compile the application (here libr or library),
gcc -g -c <file_name.c> -o <file_name.o>

to run the application,
gcc -g -o 'file_name' mld.o <file_name.o>
./'file_name'
