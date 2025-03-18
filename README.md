# rpf-longdiv-solve

A tool to solve the generic case of Richard P. Feynmans long division puzzles.

## requirements

- modern c++ compiler
- vcpkg
- ninja
- cmake

## build
```
$ cd ${PROJ}
$ cmake --preset default
$ cmake --build --preset default
```

## run
```
$ cd ${PROJ}
$ cp puzzle.txt build/
$ ./build/feynman
```
