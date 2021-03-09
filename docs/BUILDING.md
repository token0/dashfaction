--------------------------
Building DashFaction
--------------------------
   On Windows:

use CMake GUI to generate project files for your favorite IDE.

--------------------------
   On Linux:

To cross-compile on Linux you need to specify toolchain file.
This repository contains such a file for MinGW on Ubuntu.


	git clone dashfaction
	cd dashfaction
	mkdir build
	cd build
	cmake .. -DCMAKE_TOOLCHAIN_FILE=../cmake/mingw-ubuntu.cmake -DCMAKE_BUILD_TYPE=Debug
