MAIN = proj1

LOGIN = xhatal02

TEX_SOURCES = $(MAIN).tex

projekt01.pfg: $(TEX_SOURCES)
	latex $(MAIN)
	latex $(MAIN)
	dvips -t a4 $(MAIN).dvi
	ps2pdf -sPAPERSIZE=a4 $(MAIN).ps	
	
clean:
	rm -f $(MAIN).{aux,dvi,log,out,ps,pdf}
