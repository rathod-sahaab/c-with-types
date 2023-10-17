# c-with-types

Fixing the biggest mistake of C++, biting more than it could have chewed. Just gimme strong user defined types and real macros. "C with types" is to C, what Typescript is to Javascript but better.

## Inpiration

### Negative

- Golang
- Javascript
- C++
- Everything I use at work

### Positive

- Rust
- Zig
- Typescript
- Ocaml
- Mathematics(Methamatics lol)
- C (ofc.)

# Constitution

1. No hidden behaviour
2. No locked in behaviour
3. No special privileges for compiler designer (compiler).
4. Only use `c-with-types` for anything (no special macros language/syntax)
5. Transpile to C code not binary.

## Explanations

1. Runtime, Garbage Collector, etc. etc.
2. No locked in behaviour
   1. Generic name mangling should be customizable
3. Anything used internally should be added to the language.

# Features

1. Generics
   1. customizable name mangling
2. Ownership & Borrowing for memory management
3. Closures
4. Code generation (macros written in `c-with-types` like zig comptime)
5. Types
   1. Basics
   2. Structs
   3. Traits (Rust like traits) interface

## Tooling

1. Package Managers
2. Language Server

# Libraries

1. Async Runtime
   1. Green Threads backed (channels)
   2. Closures backed (async-await)
2. Stdlib (written in `c-with-types`)
   1. Map, set, etc.
   2. Algorithms.
