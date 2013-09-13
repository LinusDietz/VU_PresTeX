PresTeX VU
=======

A LaTeX Beamer template for presentations at Vilnius Universiy

Setup
-----

Furthermore, edit the <code>config/metainfo.tex</code> file to include
* your name,
* the title and subtitle of your presentation and 
* the presentation date.

Compiling the Source Code
-------------------------

Use `pdflatex` and `bibtex` to generate a presentation.
If you use texmaker, you can include the following command to automatically compile the sources: 
<code>pdflatex -synctex=1 -interaction=nonstopmode %.tex | bibtex % | pdflatex -synctex=1 -interaction=nonstopmode %.tex 
| pdflatex -synctex=1 -interaction=nonstopmode %.tex</code>

If you prefer the command line you can comfortably run the <code>make</code> script.

Dependencies
-------------------------

Your favourite and updated LaTeX compiler

Thanks to
-------------------------
Marcel Grossmann who initially created the PresTeX template for the Univerity of Bamberg. https://github.com/uniba-ktr/PresTeX
