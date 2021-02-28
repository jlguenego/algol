# Algol Tutorial

Tutorial for ALGOL 68. We use the Algol 68 Genie compiler.

All the examples are located in the `examples` directory.

## Getting started

1. Download an algol compiler.
   - Windows: [Algol 68 Genie](https://jmvdveer.home.xs4all.nl/en.algol-68-genie.html).
     - Rename the compiler `a68g-2.8.3.exe` to `a68g.exe`.
     - Put the compiler in a directory in your `%PATH%`.
2. Write the `hello.a68` file with following content:

```a68
printf(($14a$, "Hello World!!!"))
```

3. Run the file: on Windows open a cmd and type `a68g hello.a68`.
4. You should see

```
$> a68g hello.a68
Hello World!!!
```

## Author

Jean-Louis GUENEGO <jlguenego@gmail.com>
