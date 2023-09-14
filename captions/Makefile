all	:	pdfs/about.pdf pdfs/cpc6128.pdf pdfs/oric_atmos.pdf pdfs/zx.pdf

pdfs/about.pdf:	about.md
	pandoc -s -V fontsize=8pt --template=default.latex -V papersize:a5   about.md -o pdfs/about.pdf
	open pdfs/about.pdf

pdfs/cpc6128.pdf:	cpc6128.md
	pandoc -s -V fontsize=8pt --template=default.latex -V papersize:a5   cpc6128.md -o pdfs/cpc6128.pdf
	open pdfs/cpc6128.pdf

pdfs/oric_atmos.pdf:	oric_atmos.md
	pandoc -s -V fontsize=8pt --template=default.latex -V papersize:a5   oric_atmos.md -o pdfs/oric_atmos.pdf
	open pdfs/oric_atmos.pdf

pdfs/zx.pdf:	zx.md
	pandoc -s -V fontsize=8pt --template=default.latex -V papersize:a5   zx.md -o pdfs/zx.pdf
	open pdfs/zx.pdf

clean:
	rm -rf pdfs/*.pdf

