Because I always have to look up these things.

Right now there's only one basic template: latex.

## To generate bibliography for latex we need to do as multi-pass
   compile

```
pdflatex latex_source_code.tex
bibtex latex_source_code.aux
pdflatex latex_source_code.tex
pdflatex latex_source_code.tex
```