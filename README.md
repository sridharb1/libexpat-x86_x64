# libexpat-x86_x64
Native Visual Studio project files to compile libexpat on Windows

# Background #
libexpat supports compiling on Windows. However, it uses CMake, which
does not produce good solution/projects for Visual Studio.

# Compiling #
This project provides native Visual Studio solution/project files that
can be used to compile libexpat on Windows.

# Installation #

  * git clone [libexpat, tested with v2.2.10](https://github.com/libexpat/libexpat) into a local folder
  * git clone [libexpat-x86_x64](https://github.com/sridharb1/libexpat-x86_x64)
  * Copy the build folder downloaded above to the root of the libexpat
    source tree.
  * Open the solution in Visual Studio (I used Visual Studio 2019
    Community Edition). Select the platform/configuration (like
    x64/Release) and compile.
    
## Note ##
As the original project evolves, there is a possibility that these
project files can get out of date, specifically when files are
added/deleted. Usually, this can be easily fixed by examining the
errors when compiling.
