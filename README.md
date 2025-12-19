## Development

```sh
cargo xtask --help
```

The idea of implementing the auxiliary tasks of a software project using the
main programming language (as opposed to e.g. Bash scripts) was inspired by:

- [`nob.h` by `tsoding`](https://github.com/tsoding/nob.h)

  > The idea is that you should not need anything but a C compiler to build
  > a C project. No make, no cmake, no shell, no cmd, no PowerShell etc. Only
  > C compiler.

  (accessed 2025-11-03)

- [`cargo-xtask` by `matklad`](https://github.com/matklad/cargo-xtask)

  > cargo-xtask is way to add free-form automation to a Rust project ...
  > distinguishing features of xtask are: It doesn't require any other binaries
  > besides cargo and rustc ...

  (accessed 2025-11-03)
