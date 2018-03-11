all: labo
	echo "done"


labo: *.tex
	pdflatex -shell-escape -jobname="elech473_tis-100_6" "\input{elech473_tis-100_6.tex}"
	pdflatex -shell-escape -jobname="elech473_tis-100_6" "\input{elech473_tis-100_6.tex}"

clean:
	rm -f rm elech473_tis-100_6.pdf
	rm -f *.idx *.aux *.nav *.out *.snm *.toc
