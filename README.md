# LaTeX Templates

Simple LaTeX templates to quicky get up and running. Spend more time writing,
and less time debugging LaTeX.


## Structure of the repository

* `bin`: Simple automation scripts
  - `fixdiacritics`: replace old TeX accent commands with proper UTF-8 characters, e.g. \'a -> á
    (works for Spanish and German).
  - `newtex`: copy templates to create a new project
    (the environment variable `TEXDIR` should be point to this repo).

* Templates
  - `article`
  - `beamer`: Uses a modified Metropolis theme with the colors of the UNAL.

* `unal.sty`: List of common packages, with support for
  - Mathematics
  - Internationalization (for Spanish writing)
  - Tables
  - Code listings


## Ancízar typeface

The templates in this repo use the Ancízar typeface when compiled with XeLaTeX,
unfortunately this typeface is not open source.
If you're a student at the _Universidad Nacional de Colombia_, you can download it from
[here](http://identidad.unal.edu.co/guia-de-identidad-visual/c-procedimientos/c1-descarga-e-instalacion-tipografia-ancizar/)
when connected to the Campus' network.
