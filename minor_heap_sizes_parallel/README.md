This directory contains a notebook, various reports and benchmarking effort toward understanding
and improving the cost of allocating and working with large minor heaps in OCaml. (specifically, Multicore OCaml.)

All benchmarks were executed with sandmark, parallel bench suite, running on bremusa.

`4.10.0+multicore+default` is with the inclusion of the minor heap allocation refactor and default minor heap size (roughly 256k)
`4.10.0+multicore+n` is the same branch, with `OCAMLRUNPARAM=s=n`.
