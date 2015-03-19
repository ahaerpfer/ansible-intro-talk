
presentation:
	pdflatex presentation.tex

fullpresentation:
	pdflatex presentation.tex
	bibtex presentation.aux
	pdflatex presentation.tex
	pdflatex presentation.tex

handout:
	pdflatex handout.tex

fullhandout:
	pdflatex handout.tex
	bibtex handout.aux
	pdflatex handout.tex
	pdflatex handout.tex

clean:
	rm -f *.aux *.log *.nav *.out *.snm *.toc *.vrb
	rm -f *.bbl *.blg rfc.tex

all: clean fullpresentation fullhandout
