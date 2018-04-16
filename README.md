# My Resume

Nothing more than my resume actually.

A live version can be found [here](www.florianperdreau.fr/cv/index.html)

## Buld a PDF version

You can convert this html version of my resume to PDF using Pandoc:

```batch
pandoc -t html5 --css stylesheet.css -V geometry:a4paper index.html -o resume.pdf
```