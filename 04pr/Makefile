MAIN = proj4

TEX_SOURCES = $(MAIN).tex

proj2.pfg: $(TEX_SOURCES)
	latex $^
	bibtex proj4.aux
	latex $^
	latex $^
	dvips -t a4 $(MAIN).dvi
	ps2pdf -sPAPERSIZE=a4 $(MAIN).ps
	
clean:
	rm -rf $(MAIN).{aux,dvi,bbl,blg,log,out,ps,pdf}
