# Boilerplate to practice katas using C++ and GoogleTest

## Setup CMake project

```
cmake -S . -B build
```

## Build

```
cmake --build build
```

## Run tests

```
cd build && ctest -V
```

## VSCode integration

- Install CMake Tools extension.
- In the bottom bar, there is the configured "Build" and "Run" commands (`Build [all]` and `Run CTest`)
- Click the run button (arrow like a "play" button).
