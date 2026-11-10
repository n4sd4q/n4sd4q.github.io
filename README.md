<p align="center"><img src="logos/Hub_badge.svg" width="96" alt="A plaquette of four sites: hoppings along the sides, an interaction along a diagonal"></p>

<h1 align="center">Packages for theoretical physics</h1>

<p align="center"><b>Wolfram Language packages by Nazzareno Africani (SISSA)</b><br>
<a href="https://n4sd4q.github.io/"><b>n4sd4q.github.io</b></a></p>

This repository is the landing page of the packages, served by GitHub Pages at <https://n4sd4q.github.io/>, and the home
of the look they share.

| Package | |
|---|---|
| [FunctionalDiagrams](https://n4sd4q.github.io/FunctionalDiagrams/) | Feynman diagrams from functional derivatives |
| [FermiWick](https://n4sd4q.github.io/FermiWick/) | fermion operators, as symbols and as matrices |

## The common look

Every package has one hue: a gradient from a dark start to a lighter end, a solid accent (headings, links, buttons) and a
light tint (one element of its logo, its accent on dark pages); white text has at least 4.5:1 on both ends of the gradient.
The files in [`design/`](design) are copied by each package when it builds its documents, so that a change here never
breaks a package:

| File | |
|---|---|
| [`palette.json`](design/palette.json) | the colour options of each package and the chosen ones |
| [`n4sd4q.sty`](design/n4sd4q.sty), [`n4sd4q-palette.tex`](design/n4sd4q-palette.tex) | the LaTeX style of the manuals and showcases: fonts, headings, running heads, the boxes of code and output, the title band in the gradient |
| [`family.css`](design/family.css) | the stylesheet of the websites, light and dark, with the colours of a package written in as tokens |

The logos share one language: a rounded square in the gradient of the package, with its central object drawn in white
and one element in the tint ([`logos/`](logos)).

## License

The page and the design files are free software, under the [GNU General Public License, version 3 or later](LICENSE), as
the packages.
