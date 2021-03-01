# Algol Tutorial

Tutorial for ALGOL 68 (ALGOrithmic Language). We use the Algol 68 Genie compiler.

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

## Impressive things

Algol is not very in used today, but do you know a language that can do easier?

### Pi decimal calculation

You want to calculate pi with a lot of precision? Just do:

```
a68g -p "long long pi" --precision=1000
```

Just replace 1000 with 10000 or more!

## Other examples

To continue, [go to see all the examples](./examples).

## Bibliography

- https://jmvdveer.home.xs4all.nl/learning-algol-68-genie.pdf

## Participating

- Feel free to participate. Correct any errors. Make suggestions. Create more examples.

## Author

Jean-Louis GUENEGO <jlguenego@gmail.com>
