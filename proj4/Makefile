SHELL = /usr/bin/env bash
NAME = proj4
LOGIN = xbartk07

all:
	pdflatex $(NAME)
	bibtex $(NAME)
	pdflatex $(NAME)
	pdflatex $(NAME)

zip:
	zip $(LOGIN)-fit.zip *.tex *.bib *.bst Makefile

clean:
	rm -f *.{bbl,blg,aux,dvi,log,pdf,ps,out} $(LOGIN)-fit.zip
