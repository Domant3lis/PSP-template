# PSP template
This is a PSP template, see `PSP.md`

## Document generation
### PDF
`pandoc PSP.md -f markdown -t pdf -s -o PSP.pdf -V geometry:"margin=1.5cm" --columns 100 --wrap=auto"`

or

<https://cloudconvert.com/md-to-pdf>

### HTML
`pandoc 'PSP.md' -f markdown -t html -s -o PSP.html`

## Dependancies
`texlive` ir `pandoc` 

## Other options
https://jdhao.github.io/2019/05/30/markdown2pdf_pandoc/
