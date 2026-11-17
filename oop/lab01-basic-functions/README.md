# Lab 01 - Basic Functions

Five small functions: `isMultiple`, `max3`, `triangleArea`, `fahrenheitToC`
and `isValidTriangle`. The test cases were given in the lab and all 18 pass.

Most of the work was in the edge cases, like `b = 0` in `isMultiple`,
negative sides, and triangles like (1, 2, 3) that are basically a line.

For the double results the tests compare with `eps = 1e-9` instead of `==`.
I explained why in a comment in the code (floating point values like 98.6
can't be stored exactly in binary).
