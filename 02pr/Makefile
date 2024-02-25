MAIN = proj2

TEX_SOURCES = $(MAIN).tex

proj2.pfg: $(TEX_SOURCES)
	latex $(MAIN)
	latex $(MAIN)
	dvips -t a4 $(MAIN).dvi
	ps2pdf -sPAPERSIZE=a4 $(MAIN).ps
	
clean:
	rm -f $(MAIN).{aux,dvi,log,out,ps,pdf}
