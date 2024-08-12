# Dread

## Overview

This package contains all dependencies required to work with the Dread Engine. For now, these are contained within this repository as submodules, eventually this will change, those packages will be published to [crates.io](https://crates.io).

## Prerequisites

These will be scriptified in the future, but for now, these must be manually installed.

1. Cargo -
    1. Install [cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html) if it is not already installed. `cargo -V` to check if it is installed.
    1. `cargo -V` to validate installation. This should print the version you have installed, if installation was successful.
1. CMake - A C/C++ Build System. This is used to build OpenGL (and other C/C++) dependencies.
    1. Install [CMake](https://cmake.org/download/) if it is not already installed. `cmake --version` to check if it is installed.
    1. `cmake --version` to validate installation. This should print the version you have installed, if installation was successful.
1. The Vulkan SDK, download and install via the [LunarG](https://vulkan.lunarg.com/) page.
    1. Validate your install (and hardware) by navigating to and running the `{install_directory}/bin/vkcube` application, which should open a window rendering a 3d cube.
1. Clone this repository recursively to get all submodules. `git clone --recurse-submodules https://github.com/ArtOfSettling/dread.git`

## How to build

1. `cargo build` / `cargo build --release` {depending on the profile you want to build}
