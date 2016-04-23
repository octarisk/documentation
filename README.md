# Octarisk documentation

This repository contains the documentation of Octarisk. The documentation is divided into two parts:

* **user manual** - gives the user of Octarisk all the background he needs to set up the market risk measurement framework and to analyse and interpret the results.
* **developer manual** - sums up the basic structure of the scripts, gives information about the used classes and the file format of all input and output files. Moreover, the texinfo of the Octave functions is compiled into the Octarisk documentation.

## Compile the documentation
For both the PDF and the HTML format of the documentation run the following commands:

* PDF format: use texi2pdf `texi2pdf doc_octarisk.texi`
* HTML format: use makeinfo `makeinfo --html doc_octarisk.texi`

## Prerequisites

You need a installation of the TeX Live package.
On Debian based distributions, install the package with `sudo apt-get install psutils ps2eps texlive-generic-recommended texlive-latex-extra`
