NAME=beamerslides
TEXSRCS=$(NAME).tex
LATEX=/usr/bin/platex
DVIPDFM=/usr/bin/dvipdfmx
USE_DVIPDFM=1
include /usr/share/latex-mk/latex.gmk

viewbg: pdf
	mupdf $(NAME).pdf &>/dev/null&

