SOURCE = main

make:
	pdflatex $(SOURCE).tex 
	makeindex $(SOURCE).idx -s StyleInd.ist
	pdflatex $(SOURCE) x 2 -output-format=pdf
	make clean

clean:
	rm -rf $(SOURCE).aux $(SOURCE).bcf $(SOURCE).idx $(SOURCE).ilg $(SOURCE).ind $(SOURCE).toc $(SOURCE).log $(SOURCE).run.xml