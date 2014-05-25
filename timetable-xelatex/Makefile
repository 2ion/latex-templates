NAME=timetable
TEXSRCS=$(NAME).tex
#LATEX=/usr/bin/uplatex
#DVIPDFM=/usr/bin/dvipdfmx
#USE_DVIPDFM=1
USE_PDFLATEX=1
PDFLATEX=/usr/bin/xelatex
include /usr/share/latex-mk/latex.gmk

viewbg: pdf
	mupdf $(NAME).pdf &>/dev/null&

.PHONY: timetable-git
timetable-git:
	git submodule update
	ln -s timetable/timetable.sty
