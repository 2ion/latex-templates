NAME=beamerslides
TEXSRCS=$(NAME).tex
PDFLATEX=/usr/bin/xelatex
USE_PDFLATEX=1
include /usr/share/latex-mk/latex.gmk

viewbg: pdf
	mupdf $(NAME).pdf &>/dev/null&

