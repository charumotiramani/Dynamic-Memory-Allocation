# Dynamic Memory Allocation
Dynamic Memory Allocation can be defined as procedure in which the size of a data structure (like Array) is changed during the runtime.Under <stdlib.h> we use malloc() function.  
The “malloc” or “memory allocation” method in C is used to dynamically allocate a single large block of memory with the specified size.It returns a pointer of type void which can be cast into a pointer of any form. It doesn’t initialize memory at execution time so that it has initialized each block with the default garbage value initially.

### Syntax:  
ptr = (cast-type*) malloc(byte-size)
