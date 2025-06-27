#OpenGL Introduction

## Introduction

This project is a series of hands-on exercises for practicing modern OpenGL in C++. It includes multiple modules (GPO_01 to GPO_04 and associated "entrega" versions) that demonstrate rendering techniques, shader programming, and interactive graphics using a custom wrapper library (`GpO.h`).

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

## Installation

1. Clone or download this repository.
2. Ensure you have a C++ compiler that supports C++11 or later.
3. Install OpenGL development libraries on your system.
4. Optionally use CMake or another build system to compile.

### Example on Linux (g++)

```bash
sudo apt-get install libglfw3-dev libglew-dev libglm-dev
g++ src/GPO_01.cpp -o GPO_01 -lglfw -lGL -lGLEW
./GPO_01
