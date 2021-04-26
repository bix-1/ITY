SHELL = /usr/bin/env bash
NAME = proj5
LOGIN = xbartk07

.PHONY: clean

all:
	pdflatex $(NAME).tex
	pdflatex $(NAME).tex

zip:
	zip -r $(LOGIN)-fit.zip *.tex *.eps Makefile img

clean:
	rm -f $(NAME).{aux,dvi,log,ps,out,nav,snm,toc} $(LOGIN)-fit.zip
