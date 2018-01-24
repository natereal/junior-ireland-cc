# latex target
latexfile = cc
# set variables
TEX       = pdflatex

$(latexfile).pdf: $(latexfile).tex 
	-$(TEX) $(latexfile)
	$(TEX) $(latexfile)
	$(TEX) $(latexfile)

# phony target to get around problem of having a file called 'clean'
.PHONY: clean
clean:
	$(RM) *.aux *.log *.dvi *.blg *.bbl *.nav *.out *.snm *.toc *.vrb *.ps
distclean: clean
	$(RM) *.pdf

