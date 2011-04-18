all: ECML2011.pdf

ECML2011.pdf: ECML2011.tex #images/*
	pdflatex ECML2011.tex
	bibtex -min-crossrefs=999 ECML2011
	pdflatex ECML2011.tex
	pdflatex ECML2011.tex
	pdflatex ECML2011.tex

