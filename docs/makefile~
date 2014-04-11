all:
	latex practica10.tex
	latex practica10.tex
	bibtex practica10
	latex practica10.tex
	latex practica10.tex
	dvips -o practica10.ps practica10.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true práctica10.ps práctica10.pdf

clean:
	rm -f *.*~ *.toc *.ps *.log *.lof *.lot *.dvi *.aux *.blg *.bbl
