# memory-allocator

The task was to implement a C++ program to allocate blocks of memory in a byte array. The requirements for the speed tests were logarithmic execution. In order to achieve this, the buddy system was used.

The program is also required to provide a summary of unfreed blocks (memory leaks).

The use of global variables was due to the required program interface. If I had the option to do it differently, I would use a class instance.
