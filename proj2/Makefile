SHELL = /usr/bin/env bash
NAME = proj2
LOGIN = xbartk07

all:
	pdflatex $(NAME)
	pdflatex $(NAME)

zip:
	zip $(LOGIN)-fit.zip *.tex Makefile

clean:
	rm -f $(NAME).{aux,dvi,log,pdf,ps,out} $(LOGIN)-fit.zip
