all: labo
	echo "done"


labo: *.tex
	pdflatex -shell-escape -jobname="elech473_simd_7" "\input{elech473_simd_7.tex}"
	pdflatex -shell-escape -jobname="elech473_simd_7" "\input{elech473_simd_7.tex}"

clean:
	rm -f rm elech473_simd_7.pdf
	rm -f *.idx *.aux *.nav *.out *.snm *.toc
