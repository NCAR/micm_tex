TEX = pdflatex -shell-escape
BIB = bibtex

all: MICM

MICM: MICM.tex
	$(TEX) MICM
	$(TEX) MICM
	$(BIB) MICM
	$(BIB) MICM

clean:
	rm -f *.aux
	rm -f *.bbl
	rm -f *.blg
	rm -f *.log
	rm -f *.nav
	rm -f *.out
	rm -f *.snm
	rm -f *.toc
	rm -f *.pagelist
