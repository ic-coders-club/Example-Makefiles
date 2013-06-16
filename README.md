Example-Makefiles
=============

Two makefiles that build either an executable, or an executable and a library from c++ code, using gcc.

Assumes that every header file is contained in a directory called ```include``` and use ```.h``` as the file extension.
All implementation files must be in ```src``` and have a file extension of ```.cxx```

This can be customised by changing the variables at the top of the file

Usage
----
Type ```make``` and all executables will be built, otherwise type ```make <your executable name>``` and that executable alone will be created.
