.PHONY: all
all: secure-protocols.pdf

SRC+=		secure-protocols.tex preamble.tex secure-protocols.bib
SRC+= 		abstract.tex contents.tex

DEPENDS+= 	beamer-didactic.sty

secure-protocols.pdf: ${SRC} ${DEPENDS}

beamer-didactic.sty: ../beamer-didactic/beamer-didactic.sty
	${LN} $^ $@

../beamer-didactic/beamer-didactic.sty:
	${MAKE} -C $(dir $@) $(notdir $@)


.PHONY: clean
clean:
	${RM} secure-protocols.pdf
	${MAKE} -C ../beamer-didactic clean

.PHONY: distclean
distclean:
	${MAKE} -C ../beamer-didactic distclean


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
