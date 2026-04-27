# README

This is my personal resume written in `latex`. Latex is a 

## Font

- Title: [Tinos](https://fonts.google.com/specimen/Tinos)
- Body: [Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3)


## Run/Installation

See [https://notes.abgup.com/software/languages/latex/](https://notes.abgup.com/software/languages/latex/)

```bash
$ latexmk -lualatex -pvc -view=pdf -outdir=build document.tex
```

Local Environment:

```bash
$ export TEXINPUTS=.:texmf:
```

## Package Manager

There is no virtual environment developed for latex. There is a newer markup langauage made to replace latex developed in `Rust` called [typst](https://github.com/typst/typst), which probably has it...

Anyways, you create a folder with packages you've installed witin folder `./texmf` and then update the latex path, `TEXINPUTS`, to point to this folder

There is no good documentation again... But some documtation is in the texlive manual in `texdoc texlive section 7.1.1` and following