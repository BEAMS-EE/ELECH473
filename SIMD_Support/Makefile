all: labo
	echo "done"


labo: *.tex
	pdflatex -shell-escape -jobname="elech473_SIMD_Support" "\input{elech473_SIMD_Support}"
	pdflatex -shell-escape -jobname="elech473_SIMD_Support" "\input{elech473_SIMD_Support}"

clean:
	rm -f rm elech473_SIMD_Support.pdf
	rm -f *.idx *.aux *.nav *.out *.snm *.toc
