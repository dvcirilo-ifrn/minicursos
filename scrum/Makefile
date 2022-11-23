all: beamer

beamer:
	pdflatex main.tex
	pdflatex main.tex
	pdflatex main.tex

clean:
	rm -f *.aux
	rm -f *.snm
	rm -f *.toc
	rm -f *.nav
	rm -f *.out
	rm -f *.log

realclean: clean
	rm -f main.pdf main.handouts.pdf
