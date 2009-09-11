SOURCE=gmdh

view: compile
	xpdf $(SOURCE).pdf

compile: all
	pdflatex $(SOURCE).tex

all: 
	R CMD Sweave $(SOURCE).Rnw
