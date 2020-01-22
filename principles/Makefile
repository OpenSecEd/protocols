.PHONY: all
all: principles.pdf

SRC+=		principles.tex preamble.tex principles.bib
SRC+= 		abstract.tex contents.tex

DEPENDS+= 	beamer-didactic.sty

principles.pdf: ${SRC} ${DEPENDS}

beamer-didactic.sty: ../beamer-didactic/beamer-didactic.sty
	${LN} $^ $@

../beamer-didactic/beamer-didactic.sty:
	${MAKE} -C $(dir $@) $(notdir $@)


.PHONY: clean
clean:
	${RM} principles.pdf
	${MAKE} -C ../beamer-didactic clean

.PHONY: distclean
distclean:
	${MAKE} -C ../beamer-didactic distclean


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
