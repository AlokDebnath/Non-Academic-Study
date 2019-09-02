.PHONY: main.pdf
Kornai.pdf: *.tex
	latexmk -pdf -shell-escape *.tex && latexmk -c

watch: *.tex
	latexmk -pdf  -shell-escape -pvc *.tex && latexmk -c
