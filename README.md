# Joystream Whitepaper

See `paper.pdf` in repo, or click this [LINK](https://github.com/Joystream/whitepaper/blob/master/paper.pdf)

## Build

The `algorithm` style is required by the paper. On Ubuntu based distributions, it's part of the `texlive-science` package.

```bash
$ pdflatex paper.tex && bibtex paper.aux && pdflatex paper.tex && pdflatex paper.tex`
```

Or, more simply, install the `latexmk` package and run:

```bash
$ latexmk
```

## Contributing

Open a PR. Always include the compiled PDF in the PR, as it should be kept up-to-date with the source file(s).

## View

OS X:

```bash
$ open paper.pdf`
```

Linux (most distributions):

```bash
$ xdg-open paper.pdf`
```

## License

See LICENSE file.
