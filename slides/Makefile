
NAME=Kan-2013-Dissertation

ALLTEX=*.tex
SRC=$(NAME).tex

TARG=$(SRC:.tex=.pdf)

all: $(TARG)

$(TARG): $(SRC) $(BIB) $(ALLTEX)
	pdflatex $(NAME)
	pdflatex $(NAME)

clean:
	rm -f *~ *log *nav *aux $(TARG) *.out *.blg *.brf *.bbl *.bak *.dvi *.toc *.snm
 
zip:
	zip -r Proposal *.tex *.bib *.cls *.bst Makefile

