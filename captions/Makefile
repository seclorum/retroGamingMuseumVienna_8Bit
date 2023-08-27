all	:	about.pdf cpc6128.pdf oric_atmos.pdf zx.pdf

about.pdf:	about.md
	pandoc -s -V fontsize=8pt --template=default.latex -V papersize:a5   about.md -o about.pdf
	open about.pdf

cpc6128.pdf:	cpc6128.md
	pandoc -s -V fontsize=8pt --template=default.latex -V papersize:a5   cpc6128.md -o cpc6128.pdf
	open cpc6128.pdf

oric_atmos.pdf:	oric_atmos.md
	pandoc -s -V fontsize=8pt --template=default.latex -V papersize:a5   oric_atmos.md -o oric_atmos.pdf
	open oric_atmos.pdf

zx.pdf:	zx.md
	pandoc -s -V fontsize=8pt --template=default.latex -V papersize:a5   zx.md -o zx.pdf
	open zx.pdf

clean:
	rm -rf *.pdf

