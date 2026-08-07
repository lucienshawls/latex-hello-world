# latex-hello-world

A XeLaTeX "hello world" template for quickly validating a local LaTeX setup with:

- Chinese/English fonts and heading styles
- Cover page and front-matter pagination
- Odd-page section starts for book-style printing
- Main-body headers/footers, equations, figure, table, citations
- GB/T 7714-2015 bibliography formatting

## Build

```bash
mkdir build
xelatex -output-directory=build main.tex
biber build/main
xelatex -output-directory=build main.tex
xelatex -output-directory=build main.tex
```
