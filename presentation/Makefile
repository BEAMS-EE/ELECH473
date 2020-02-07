all: labo
	echo "done"


labo: *.tex
	pdflatex -shell-escape -jobname="presentation" "\input{presentation.tex}"
	pdflatex -shell-escape -jobname="presentation" "\input{presentation.tex}"

clean:
	rm -f rm presentation.pdf
	rm -f *.idx *.aux *.nav *.out *.snm *.toc
