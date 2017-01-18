# cogbuild
cogbuild - the amazing one step C/C++ multiplatform build system

## Syntax

```
cogbuild HelloWorld.cpp [win|mac|ios|android] [debug|release] [clean] [build] [run]
```

`[win|mac|ios|android]` - Which platform to build. Defaults to the host OS (Windows or Mac).

`[debug|release]` - Which config to build. Defaults to debug.

`[clean] [build] [run]` - What actions to perform, can use any combination. Defaults to build run.

## Example



## Tags

```
// cog name TestSprock
// cog title Test Sprock
// cog identifier com.stingergames.testsprock
// cog versionName 1.0.1
// cog versionCode 10001

// cog package SDL pthread OpenAL

// cog data test.dat 
// cog data *.txt *.lua
```

Tags are an optional way to configure the way your program is built.

```
// cog package SDL pthread OpenAL
```
Adds the SDL, pthread, and openAL packages to the build.

```
// cog source util.cpp
```
Adds util.cpp as a source dependency. Used mainly in headers (ex. util.hpp will add util.cpp).
