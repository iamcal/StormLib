# StormLib

A version of <a href="http://www.zezula.net/en/mpq/stormlib.html">StormLib</a> which can be compiled using Visual Studio 2010.

## Compiling on Windows using MINGW

    make -f makefile.w32

## Compiling on Windows using Visual Studio 2010 (v11)

Open the solution file `vc2010\StormLib.sln` in Visual Studio. The StormLib project contains debug 
and release targets for both static and dynamic libraries. All compiled binaries are output into
a folder called `bin` in the root of the checkout.

## Compiling on Linux

    make -f Makefile.linux

## Compiling on OSX using XCode

Open the XCode project in the root of the checkout.

