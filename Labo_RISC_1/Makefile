all: labo
	echo "done"


labo: *.tex
	pdflatex -shell-escape -jobname="elech473_risc_labo1" "\input{elech473_risc_labo1.tex}"
	pdflatex -shell-escape -jobname="elech473_risc_labo1" "\input{elech473_risc_labo1.tex}"

clean:
	rm -f rm elech473_risc_labo1.pdf
	rm -f *.idx *.aux *.nav *.out *.snm *.toc
