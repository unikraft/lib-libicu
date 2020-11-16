icu for Unikraft
===================

This is the port of icu as a Unikraft external library; it depends on
the following libraries that need to be added to `Makefile` in this
order:

* `pthreads`, e.g. `pthread-embedded`
* CXX standard library, e.g. `libunwind`, `compiler-rt`, `libcxxabi`, `libcxx`
* `libc`, e.g. `newlib`
