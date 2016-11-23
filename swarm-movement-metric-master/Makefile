stability: stability.tex stability.bib IEEEtran.cls figures
	latex stability
	bibtex stability
	latex stability
	latex stability
	dvips -Ppdf stability
	ps2pdf -dCompatibility=1.5 -dPDFSETTINGS=/prepress -dEmbedAllFonts=true stability.ps
clean:
	rm -f *~ *.{aux,log,out,toc,lof,lot,bbl,blg}
