SRCFILEBASE=RadiareTerms
DOCDIR=../../../doc

all: 
	#emacs --batch $(SRCFILEBASE).org -f org-latex-export-to-latex 
	latexmk -pdf $(SRCFILEBASE)
	mv $(SRCFILEBASE).pdf $(DOCDIR)
	latexmk -c $(SRCFILEBASE)
	rm $(SRCFILEBASE).tex
