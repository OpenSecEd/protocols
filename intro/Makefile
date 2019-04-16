.PHONY: all
all: intro.pdf

SRC=		intro.tex preamble.tex abstract.tex contents.tex intro.bib

intro.pdf: ${SRC}


.PHONY: clean
clean:
	${RM} intro.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
