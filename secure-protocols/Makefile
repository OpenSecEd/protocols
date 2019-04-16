.PHONY: all
all: secure-protocols.pdf

SRC+=		secure-protocols.tex preamble.tex secure-protocols.bib
SRC+= 		abstract.tex contents.tex

secure-protocols.pdf: ${SRC}


.PHONY: clean
clean:
	${RM} secure-protocols.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
