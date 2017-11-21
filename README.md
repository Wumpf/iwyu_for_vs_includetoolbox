# iwyu_for_vs_includetoolbox

This repository is manually updated with a win32 binary of [include-what-you-use](https://include-what-you-use.org/). It is used as as download/update source by the Visual Studio extension [IncludeToolbox](https://github.com/wumpf/includetoolbox).

## Licensing

**Use of include-what-you-use.exe falls under the respective license of the version provided here.** See [iwyu_LICENSE.txt](iwyu_LICENSE.txt)
Any other files provided in this repository are under public domain.

## Current version

Official Release, 0.8
https://include-what-you-use.org/downloads/include-what-you-use-0.8-x86-win32.zip

## Mapping files

* **stl.c.headers.mp** maps C files to C++ wrappers, straight from the [iwyu repository](https://raw.githubusercontent.com/include-what-you-use/include-what-you-use/master/stl.c.headers.imp)
* **msvc.imp** maps MSVC internal files to public files
