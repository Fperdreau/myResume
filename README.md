# My Resume

Nothing more than my resume actually.

A live version can be found [here](https://www.florianperdreau.fr/myResume/)

## Build a PDF version

You can convert this html version of my resume to PDF using Pandoc:

```batch
pandoc -t html5 --css stylesheet.css -V margin-top=3 -V margin-left=3 -V margin-right=3 -V margin-bottom=3 -V title="" -o resume.pdf index.html
```
