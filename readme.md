#Thesis Template

This repository provides a basic thesis template created from my own PhD thesis. The design uses colors similar to those used in Técnico visual Identity rules (available [here](https://tecnico.ulisboa.pt/en/about-tecnico/institutional/logo-identity-standards)).

## Compilation

To compile the source code, I used Texstudio with PDFLatex (and also rubber, under linux). The sequence of commands used where:

	pdflatex.exe -synctex=1 -interaction=nonstopmode "thesis".tex
	pdflatex.exe -synctex=1 -interaction=nonstopmode "thesis".tex
	bibtex.exe "thesis"
	makeglossaries.exe "thesis"
	pdflatex.exe -synctex=1 -interaction=nonstopmode "thesis".tex
	pdflatex.exe -synctex=1 -interaction=nonstopmode "thesis".tex

### Disclaimer

This code is provided "as is", without warranty of any kind, expressed or implied. 

### License

![Creative Commons License logo](https://i.creativecommons.org/l/by/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution 4.0 International License](
http://creativecommons.org/licenses/by/4.0).
