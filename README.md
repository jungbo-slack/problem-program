# problem-program #

## Overview ##

This program asks few questions to the user, and collects the information.

## Building ##
This project uses CMake for building. You may compile using any CMake-compatiable platforms and compilers.

The following sections will explain how to clone this repo and compile using CMake for novice users.

### Building on Windows ###
1. Clone this project using either git or 'Download ZIP' button.
1. If you do not have CMake yet, download and install CMake from [here](https://cmake.org/download/).
1. Run cmake-gui.
1. Press 'Browse Source...' and locate the directory you have cloned this project.
1. Select where to build using 'Browse Build...' button.
1. Press 'Configure' and select what backend to use.
1. Now compile with chosen backend.
1. That's it!

### Building on Linux ###
1. Install C++ compilers if you haven't.
    * You are not limited into using GCC. You may use any C++11 compatiable compilers as long as it's recognized by CMake.
    * On Debian-based systems (like Debian, Ubuntu, etc.), it is `apt-get install gcc g++` as root.
	* On Arch Linux, it is `pacman -S gcc` as root.
	* For other platforms, consider googleing it.
1. Install Git if you haven't.
    * On Debian-based systems (like Debian, Ubuntu, etc.), it is `apt-get install git-core` as root.
	* On Arch Linux, it is `pacman -S git` as root.
	* For other platforms, consider googleing it.
1. Install CMake if you haven't.
    * On Debian-based systems (like Debian, Ubuntu, etc.), it is `apt-get install cmake` as root.
	* On Arch Linux, it is `pacman -S cmake` as root.
	* For other platforms, consider googleing it.
1. Clone this repo using `git clone <This repo's URL> <directory to clone into>`
1. Go into the cloned directory using `cd <directory which cloned into>`
1. Make a directory to build using `mkdir build`
1. Go into that directory using `cd build`
1. Run CMake using `cmake ..`
1. Start building using `make -j<number of CPUs+1>`
    * You may ignore `-j` if you don't know how many CPUs your computer has. If so, the command simply becomes `make`
1. That's it!

## License ##
This program is licensed under GPLv3. Please take a look at LICENSE.md for full license.

## Credit ##
Made by Team jungbo-slack (spear-root,hotmandu,minary,gunwoo7)

Note: jungbo means 'information' in Korean  
Note: The proper name for this project is not decided yet.
