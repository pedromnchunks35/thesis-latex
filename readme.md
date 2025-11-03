# TO RUN THIS
pdflatex main.tex

biber main

bibtex main

pdflatex main.tex

# With xelatex
latexmk -xelatex main.tex