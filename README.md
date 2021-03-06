ETrun - The W:ET timerun mod
============================

[![Build Status](https://travis-ci.org/ETrun/ETrun.png?branch=newstructure)](https://travis-ci.org/ETrun/ETrun)
[![Coverity Status](https://scan.coverity.com/projects/3689/badge.svg?flat=1)](https://scan.coverity.com/projects/3689)

ETrun is a Wolfenstein: Enemy Territory game modification based on ET-GPL.
The objective of this mod is to bring timeruns support to it.

**Visit www.timeruns.net for more information.**

Video
=====

[![Link to the video](http://img.youtube.com/vi/asMrNNIT0e0/0.jpg)](http://www.youtube.com/watch?v=asMrNNIT0e0)

Compatibility
=============

Windows
-------

Windows server module `qagame_mp_x86.dll` requires [Microsoft Visual C++ 2010 Redistributable Package](http://www.microsoft.com/en-us/download/details.aspx?id=5555) to run properly.
Works (tested) on `XP/7` with `ET 2.60b`.

Linux
-----

Requires `GLIBC >= 2.7`.
Works (tested) on `Debian 6`, `Linux Mint 12` with `ET 2.60b` and `ET: Legacy`.

OSX
---

Not compatible with `ET 2.60d`.
Works (tested) on `OSX 10.8` with `ET: Legacy`.

Building ETrun - Using CMake
============================

Get ETrun source code with its submodule:

	$ git clone --recursive git@github.com:ETrun/ETrun.git

Then run the build script:

	$ ./make.sh

Alternatively you can point the CMake GUI tool to the CMakeLists.txt file and generate platform specific build project or IDE workspace.

Testing
=======

There are test scripts for Windows and Linux / OSX located in `test` directory.
Before using them you need to setup your config file. Make a copy of the `*.config.example` file corresponding to your OS and run the following command to know all available opions:

	$ ./test/unix/test.sh -h

Credits
=======

* TJMod developpers
* Racesow project
