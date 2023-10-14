# CacheStitcher

_CacheStitcher_ is a tool that supports forensic analysts in reconstructing useful images out of RDP cache bitmaps. Using raw RDP cache tile bitmaps extracted by tools like e.g. ANSSI's _BMC-Tools_ (https://github.com/ANSSI-FR/bmc-tools) as input, it provides a graphical user interface and several placement heuristics for stitching tiles together so that meaningful images or even full screenshots can be reconstructed.

![CacheStitcher GUI](screenshot.jpg)

## Features

* Show hints where a selected tile might fit best visually
* Provide an ordered list of tiles that could best be placed visually for a selected empty cell
* When hovering over a tile, preview how it might look when placed 
* Work with multiple screens per case
* Options to exclude already used, non-square or duplicate tiles
* Crop and export all reconstructed images belonging to a case as PNG
* The sub-window with all available tiles is dockable, i.e. it can be its own window and move to a different display
* Keep individual notes per screen

## Manual

A complete manual with a description of all features and the workflow for a typical use case can be found in the document [CacheStitcher_manual.pdf](CacheStitcher_manual.pdf).

## Installing prerequisites and starting CacheStitcher

You can download prebuilt binaries of _CacheStitcher_ for 64bit Linux and Windows at https://github.com/BSI-Bund/CacheStitcher/releases/. For each system you have to install one necessary prerequisite first.

### Ubuntu

* Install the package _libqt5widgets5_: ```sudo apt install libqt5widgets5```
* Run ```CacheStitcher```

### Windows

* Install the Microsoft Visual C++ 2017 Redistributable (64 bit) package on your Windows machine (https://aka.ms/vs/16/release/vc_redist.x64.exe)
* Unzip the _CacheStitcher_ archive anywhere on your system
* Run ```CacheStitcher.exe```

---

