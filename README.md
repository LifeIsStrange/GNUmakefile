# GNUmakefile

This aim of this project is to enjoy the powerful of plain [GNU Makefile](https://www.gnu.org/software/make/).
It is a personal attempt to satisfy every needs when compiling a project.

This project is intended to better understand the limits of [GNU Makefile](https://www.gnu.org/software/make/) and the needs to have tools like [CMake]([GNUmakefile](https://www.cmake.org/) or [GNU autotools](https://www.gnu.org/software/automake/).

The goal is to write GNUmakefile file for any project with the tools provided.


## List of needs

This is a list of every things the project have to do:

- [ ] Use CLI variables (‘make CC="gcc"’)
- [ ] Use built-in rules to compile
- [ ] Track dependencies to header files
- [ ] Every generated file have to be in a separate folder
- [ ] Detect missing folders and creating them
- [ ] Object instrumentation is preserved (‘make CFLAGS="-g"’)
- [ ] Build static libraries / shared libraries based on binary’s name
- [ ] Any librairies dependencies is automatically detected to must be up-to-date
- [ ] Parallel execution is preserved (‘make -j JOBS’)
- [ ] Do not use shell, nor wildcard
- [ ] Better printing (without colors)


The GNUmakefile file for developers-side have to do:

- [ ] It must be simple to write
- [ ] Units tests must be easy to implemement
- [ ] Custom rules (like ‘docs’ for generate documentation)


The utopic goal:

- [ ] Modular project: Each functionnality can be added as wish


## How to use this project?

A wiki will be added if many goals is achieved.
