SHELL = /usr/bin/env bash
NAME = proj5
LOGIN = xbartk07

.PHONY: clean

all:
	latex $(NAME).tex
	latex $(NAME).tex
	dvips $(NAME).dvi
	ps2pdf $(NAME).ps

zip:
	zip $(LOGIN)-fit.zip *.tex *.eps Makefile img/

clean:
	rm -f $(NAME).{aux,dvi,log,ps,out,nav,snm,toc} $(LOGIN)-fit.zip
