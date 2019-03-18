all: labo
	echo "done"


labo: *.tex
	pdflatex -shell-escape -jobname="elech473_multithreading_9" "\input{elech473_multithreading_9.tex}"
	pdflatex -shell-escape -jobname="elech473_multithreading_9" "\input{elech473_multithreading_9.tex}"

clean:
	rm -f rm elech473_multithreading_9.pdf
	rm -f *.idx *.aux *.nav *.out *.snm *.toc
