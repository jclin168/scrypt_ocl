scrypt_ocl
==========
A custom optimized OpenCL scrypt algorithm.

This is no guarantee that you can get higher hashrate. There are many variants of OpenCL implementation of nVidia and AMD, and different GPU chips to tune the best sweet spot. Please use with your own risk and there is no warranty if your software/hardware has errors or damages.

Scrypt algorithm performance heavily depends on memory access perofmrance. When the access pattern is linear and has no memory bank/channel conflicts, otherwise, it might result in poor performance. This is just one of my manual optimized scrypt code for myself.

