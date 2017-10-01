# A Sample Mathematics Paper

This repository contains a sample mathematics paper to illustrate
basic ideas in LaTeX.  I suggest comparing the source file `paper.tex`
(and the associated bibliography file `paper.bib`) with the output
file `paper.pdf`. The file `doodle.pdf` is a graphic image that's
included in the paper.

It's probably necessary to read a LaTeX tutorial before getting
started. But then I hope you'll find it useful to have this paper as
an example of how certain things are done in LaTeX.

To typeset the paper on your own, you'll need to give the following sequence of
commands:
```
pdflatex paper
pdflatex paper
bibtext paper
pdflatex paper
```

## Multichoose

See also the enclosed file `multichoose.tex` (and its output) to see how
to typeset the multichoose notation.
