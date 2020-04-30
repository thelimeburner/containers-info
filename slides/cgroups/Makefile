


all: 
	pdflatex slides.tex
	pdflatex slides.tex


clean:
	rm -f *.aux *.log *.nav *.toc *.snm *.out *.vrb


cleanall: clean
	rm -f *.pdf


handout:
	pdflatex -jobname=cgroups.handout '\PassOptionsToClass{handout}{beamer} \input{slides}'
