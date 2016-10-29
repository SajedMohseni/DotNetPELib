# DotNetPELib

DotNetPELib is a library which abstracts managed information such as namespaces, classes, fields, methods, and instructions.  The information can then be used to generate assembly language source files, or PE executables or DLLs.

The library has been tested as the backend for the OCCIL compiler, and is reasonably functional.  That said this version of the library does have various limitations; not all aspects of the managed environment are enabled at this time.

A simple test program is included which generates several example executables in both IL and EXE format.

The project files are for Visual Studio 2015 community edition.   This source code does use some of the new features in C++11.
