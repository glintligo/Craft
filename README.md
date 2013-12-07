## Craft

A simple Minecraft clone written in C using modern OpenGL (shaders).

### Features

* World changes persisted in a sqlite3 database.
* Simple but nice looking terrain generation using perlin / simplex noise.
* Nine types of blocks, but more can be added easily.
* Supports plants (grass, flowers, etc.) and transparency (glass).
* Simple clouds in the sky (they don't move).
* Shadow mapping for nice looking shadows (on the shadow branch).

### How to Run

- Download and install [CMake](http://www.cmake.org/cmake/resources/software.html) if you don't already have it.
- All other dependencies are included in the repository.

Then, run the following commands in your terminal.

    git clone https://github.com/fogleman/Craft.git
    cmake .
    make
    ./craft

### Screenshot

![](https://raw.github.com/fogleman/Craft/master/screenshot.png)
