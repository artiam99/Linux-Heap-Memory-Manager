# Linux-Heap-Memory-Manager

This is custom-designed Linux Heap Memory Manager. It manages the memory allocated or freed for a process.

calloc() and free() functions are also implemented in this project and Internal and External Fragmentation problems are also prevented.

The Memory Manager also shows its internal state by printing the memory usage for each structure.


### compilation - 

 gcc -g -c testapp.c -o testapp.o
 
 gcc -g -c mm.c -o mm.o 
 
 gcc -g -c gluethread/glthread.c -o gluethread/glthread.o
 
 gcc -g testapp.o mm.o gluethread/glthread.o -o test.exe
 
 
 For testing modify the testapp.c file by allocating and de-allocating memory using XMALLOC() and XFREE() functions.
 
 Do the above compilation and run test.exe.
 
./test.exe

## High Level Design

![hld](https://user-images.githubusercontent.com/47227715/138080342-6e2de178-134d-4770-b4d5-cb2a0a93e724.png)


## Testing Linux Heap Memory Manager

![Screenshot (82)](https://user-images.githubusercontent.com/47227715/128883011-56a6152f-f0c4-4dfb-bb8d-3ed88484b973.png)

![Screenshot (83)](https://user-images.githubusercontent.com/47227715/128883106-837cddb2-5a02-4aa1-9466-b9f02b5e99e5.png)

![Screenshot (80)](https://user-images.githubusercontent.com/47227715/128883136-5cbe2228-2aea-414f-aef6-97d2b6ad7adb.png)

![Screenshot (81)](https://user-images.githubusercontent.com/47227715/128883169-5e9f4d4c-3184-4efb-9e0a-29763f771496.png)
