# parallel-distributed

* see 21mnist/README.md

**Uncomment** `-mavx512f` and `-mfma` flags in [Makefile](21mnist/Makefile) to compile the source code into `OpenMP` + `x86 SIMD intrinsics` version. Otherwise it will be compiled into pure `OpenMP` version by default.
