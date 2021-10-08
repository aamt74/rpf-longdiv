# rpf-longdiv-solve
A tool to solve the generic case of Richard P. Feynmans long division puzzles. This repository is part of the blog post found [here](https://www.algorithmalley.nl/2021/04/25/rpf-longdiv/).

## requirements

- modern c++ compiler
- boost
- cmake

## build
```
$ cd ${PROJ}
$ mkdir build
$ cd build
$ cmake -DCMAKE_BUILD_TYPE=Release ..
$ make
```

## run
```
$ cd ${PROJ}
$ cp puzzle.txt build/
$ ./build/feynman
```
