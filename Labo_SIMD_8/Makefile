all: labo
	echo "done"


labo: *.tex
	pdflatex -shell-escape -jobname="elech473_simd_8" "\input{elech473_simd_8.tex}"
	pdflatex -shell-escape -jobname="elech473_simd_8" "\input{elech473_simd_8.tex}"

clean:
	rm -f rm elech473_simd_8.pdf
	rm -f *.idx *.aux *.nav *.out *.snm *.toc
