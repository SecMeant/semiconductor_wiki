all: poster.pdf

poster.pdf: poster.tex refs.bib Makefile
	lualatex poster
	bibtex poster
	lualatex poster
	lualatex poster

clean:
	rm -f poster.pdf poster.log poster.aux poster.bbl poster.blg

.PHONY: clean

