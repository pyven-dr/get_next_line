# Get_next_line

## Reading a line from a fd is way too tedious

### This project is about programming a function that returns a line read from a file descriptor.

You will understand how files are opened, read and closed in an OS,
and how they are interpreted by a programming language for further analysis.
This task is crucial to understand for a future programmer since much of the time is based
on manipulating files for data management and persistence.
This project consists of coding a function that returns one line at a time from a text file.

## How to use 
clone the repository
```bash
git clone https://github.com/pyven-dr/get_next_line.git
```
compile
```bash
make
```
include `get_next_line.h` to use it
```c
#include "get_next_line.h"
```
You can set the buffer size at compilation with the flag

```bash
-D BUFFER_SIZE=<size>
```
