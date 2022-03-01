# memalloc

[Source](https://arjunsreedharan.org/post/148675821737/write-a-simple-memory-allocator) | [Github](https://github.com/arjun024/memalloc)

A memory allocator in C.
Requires a Unix-based system.

## Compile and Run

```Bash
gcc -o memalloc.so -fPIC -shared memalloc.c
```

System: WSL on Windows 10
Currently running into segmentation fault after adding printf() statements.
Otherwise, it works fine.
