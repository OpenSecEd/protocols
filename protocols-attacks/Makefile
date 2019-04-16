.PHONY: all
all: protocols-attacks.pdf

SRC=		protocols-attacks.tex preamble.tex abstract.tex contents.tex protocols-attacks.bib

protocols-attacks.pdf: ${SRC}


.PHONY: clean
clean:
	${RM} protocols-attacks.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
