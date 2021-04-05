<img src="https://deepnest.io/img/logo-large.png" alt="Deepnest" width="250">

**Deepnest**: A fast, robust nesting tool for laser cutters and other CNC tools

**Download:** https://deepnest.io

Deepnest is a desktop application based on [SVGNest](https://github.com/Jack000/SVGnest)

- new nesting engine with speed critical code written in C
- merges common lines for laser cuts
- support for DXF files (via conversion)
- new path approximation feature for highly complex parts

To rebuild the native nesting engine
- npm install --save-dev electron-rebuild
- npm install
- .\node_modules\.bin\electron-rebuild.cmd
- copy contents of build/Release to minkowski/Release
- To package app run electron-packager . deepnest --platform=win32 --arch=x64