# ccVector

ccVector is a vector, quaternion and matrix math library, by [Job Talle](https://api.github.com/users/jobtalle).

Functions for `2`, `3` and `4` dimensional vectors are defined. Functions for `2x2`, `3x3` and `4x4` sized matrices are defined. Quaternions are available and interchangeable with 4 dimensional vectors.

If more types are needed, `CCV_DEFINE_VEC(n)` can be used to define `n` dimensional vectors and `CCV_DEFINE_MAT(n)` can be used to define `nxn` sized matrices.

The typedef `ccvType` is `float` by default, but can be any floating point type. All vector and matrix elements will be of the type `ccvType`. Functions for sine, cosine, tangent and square root can also be changed. By default, functions from `math.h` are used.

Function and type names can be changed if preferred. By default, a 3 dimensional vector type is defined as `vec3`, and the function to normalize it is defined as `vec3 vec3Normalize(vec3 v)`. This can be changed to `v3 v3_normalize(v3 v)` for example by altering macro definitions at the beginning of the file.


## Installation

Run:
```bash
$ npm i ccvector.c
```

And then include `ccVector.h` as follows:
```c
#include "node_modules/ccvector.c/ccVector.h"
```

<br>
<br>


[![ORG](https://img.shields.io/badge/org-nodef-green?logo=Org)](https://nodef.github.io)
![](https://ga-beacon.deno.dev/G-RC63DPBH3P:SH3Eq-NoQ9mwgYeHWxu7cw/github.com/nodef/ccvector.c)
