


all: 
	pdflatex containers.tex
	pdflatex containers.tex


clean:
	rm -f *.aux *.log *.nav *.toc *.snm *.out *.vrb


cleanall: clean
	rm -f *.pdf


handout:
	pdflatex -jobname=containers-handout '\PassOptionsToClass{handout}{beamer} \input{containers}'

