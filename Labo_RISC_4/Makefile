all: labo
	echo "done"


labo: *.tex
	pdflatex -shell-escape -jobname="elech473_risc_labo4" "\input{elech473_risc_labo4.tex}"
	pdflatex -shell-escape -jobname="elech473_risc_labo4" "\input{elech473_risc_labo4.tex}"

clean:
	rm -f rm elech473_risc_labo4.pdf
	rm -f *.idx *.aux *.nav *.out *.snm *.toc
