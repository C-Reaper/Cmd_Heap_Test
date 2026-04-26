# Project README

## Overview
This project is a simple implementation of a memory allocator (heap) in C. It includes functionality to allocate and free memory blocks within a predefined memory region.

## Features
- Allocates memory blocks of specified sizes.
- Frees allocated memory blocks.
- Prints the current state of the heap, showing available and used blocks.
- Works on Linux, Windows, Wine, and WebAssembly platforms.

## Project Structure
### Prerequisites
- C/C++ Compiler (GCC for Linux, Clang or GCC for web, x86_64-w64-mingw32-gcc for Windows)
- Make utility
- Standard development tools

## Build & Run
To build and run the project on different platforms:

**Linux:**
```sh
cd <Project>
make -f Makefile.linux all
make -f Makefile.linux exe
```

**Windows:**
```sh
cd <Project>
make -f Makefile.windows all
make -f Makefile.windows exe
```

**Wine:**
```sh
cd <Project>
make -f Makefile.wine all
make -f Makefile.wine exe
```

**WebAssembly (Emscripten):**
```sh
cd <Project>
make -f Makefile.web all
make -f Makefile.web exe
```

These commands will build the project and run the executable. The `all` target builds the project, while the `exe` target runs it after building.