.PHONY: all
all: formal-verification.pdf

SRC=		formal-verification.tex preamble.tex abstract.tex contents.tex formal-verification.bib

formal-verification.pdf: ${SRC}


.PHONY: clean
clean:
	${RM} formal-verification.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
