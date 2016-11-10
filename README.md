# university-codesprint

[University
Codesprint](https://github.com/hackerrank-dannywillems/university-codesprint).

Every code is in OCaml 4.02.3 and uses Core standard library.

## Dependencies

- If you want to use a clean switch:
```
opam switch hackerrank --alias-of 4.02.3
```

- Install Core package.
```
opam install -y core
```

## Compile

Supposing the ml file to compile is `file.ml`,

- To compile in native:
```
corebuild file.native
```

- To compile in bytecode:
```
corebuild file.byte
```
