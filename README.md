
This Repository
--------
This is a version of Blend2D that can be compiled with Emscripten when the proper options are set.

Assuming you are in a MinGW command prompt and have the `EMSCRIPTEN` environment variable set to the folder you cloned the Emscripten SDK into, you can use these commands to build:
```
cmake -DCMAKE_TOOLCHAIN_FILE=%EMSCRIPTEN%/cmake/Modules/Platform/Emscripten.cmake -DBLEND2D_NO_JIT=1 -DBLEND2D_NO_TLS=1 -DBLEND2D_NO_SIMD=1 -DBLEND2D_STATIC=1 -G "MinGW Makefiles" ..
mingw32-make
```

Blend2D
-------

2D Vector Graphics Powered by a JIT Compiler.

  * [Official Home Page (blend2d.com)](https://blend2d.com)
  * [Official Repository (blend2d/blend2d)](https://github.com/blend2d/blend2d)
  * [Public Chat Channel](https://gitter.im/blend2d/blend2d)
  * [Zlib License](./LICENSE.md)

See [blend2d.com](https://blend2d.com) page for more details.

Documentation
-------------

  * [Documentation Index](https://blend2d.com/doc/index.html)

Bindings
--------

  * [Download Page](https://blend2d.com/download.html#Bindings) provides a list of Blend2D bindings

Beta Version
------------

Blend2D is currently in a beta testing mode, which means that you can download and use the library, but a certain functionality may be limited or not working as expected. Use at your own risk!
