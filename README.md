# Inverse-Matrix-ARM-Assembly-Project-2019

### Inverse Matrix

Code to obtain N x N (3 <= N <= 20) inverse matrix implemented using Gaussian Elimination method.

To obtain inverse matrices, floating point multiplication and division needed.

### Performance

To optimize performance
- Loop Unrolling
- Cared about pipelining
- used Stack Register, Program Counter Properly
- minimize LDR, STR instrunctions which takes longer than primitive ops.

When N = 20,

it took about 3M states

### Stack

Used ARM Assembly language.


