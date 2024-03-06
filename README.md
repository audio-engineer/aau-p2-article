# AAU P2 Article

## Prerequisites

- [TeX Live](https://www.tug.org/texlive/)
- [TeXtidote](https://sylvainhalle.github.io/textidote/)

## Local Development

### Linting

#### ChkTeX

```shell
chktex -q -l .chktexrc src/main.tex
```

#### TeXtidote

```shell
textidote src/main.tex
```

### Compilation

#### JetBrains IDEs

Run the `main` run configuration.

#### Command Line

First, change the current directory to the [`src/`](src) directory

```shell
cd src/
```

and then run

```shell
latexmk
```
