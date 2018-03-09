all: labo
	echo "done"


labo: *.tex
	pdflatex -shell-escape -jobname="elech473_dspic_5" "\input{dspic1.tex}"
	pdflatex -shell-escape -jobname="elech473_dspic_5" "\input{dspic1.tex}"

clean:
	rm -f rm elech473_dspic_5.pdf
	rm -f *.idx *.aux *.nav *.out *.snm *.toc
