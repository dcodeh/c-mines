# c-mines
A C implementation of Minesweeper using ncurses. 

```
Usage: ~$ ./mines len num
```

| Parameter | Meaning |
| --------- | ------- |
| len       | the integer dimension of one side of the square board |
| num       | the number of mines on the board |

## Compilation with GCC
Don't forget to compile with -lncurses, otherwise the linker will split
in your face.

### Compilation Options
Make makes life easier.
#### Vanilla Make
Just go in the directory and type ```make```

#### A La Mode
Compiles with extra compiler flags on the side.
Just go in the directory and type ```make dev```

### Cleanup Options
Because storage space is so hard to come by these days...

#### Clean
Removes files created during the compile process, leaves source files, and
executables untouched.
```
make clean
```

#### *Real* Clean
Torches all files created in the process of compiling, including executables.
Will leave source files untouched.

```
make real_clean
```
