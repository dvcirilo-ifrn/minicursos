all: beamer handouts

beamer:
	pdflatex main.tex
	pdflatex main.tex
	pdflatex main.tex

handouts:
	pdflatex main.handouts.tex
	pdflatex main.handouts.tex
	pdflatex main.handouts.tex

clean:
	rm -f *.aux
	rm -f *.snm
	rm -f *.toc
	rm -f *.nav
	rm -f *.out
	rm -f *.log

realclean: clean
	rm -f main.pdf main.handouts.pdf
