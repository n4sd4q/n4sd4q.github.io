<p align="center">
  <img src="logos/Hub_badge.svg" width="110" alt="The mark of the packages: a plaquette of four sites, hoppings along the sides and an interaction along a diagonal">
</p>

<h1 align="center">Packages for theoretical physics</h1>

<p align="center">
  <b>Wolfram Language packages for quantum field theory and many-body physics</b><br>
  by Nazzareno Africani (SISSA, Trieste)
</p>

<p align="center">
  <a href="https://n4sd4q.github.io/"><b>Website</b></a>&nbsp;·
  <a href="https://github.com/n4sd4q/FunctionalDiagrams"><b>FunctionalDiagrams</b></a>&nbsp;·
  <a href="https://github.com/n4sd4q/FermiWick"><b>FermiWick</b></a>
</p>

Calculations as one does them on paper, done by the computer: Feynman diagrams derived by functional derivatives, and
fermion operators brought to normal order, contracted in the state you assume and solved exactly on a cluster. Every
package is a paclet installed with one line, with a showcase, a manual, a guided tour and its tests, and is free software.

## The packages

<table>
  <tr>
    <td width="96" align="center"><a href="https://n4sd4q.github.io/FunctionalDiagrams/"><img src="logos/FunctionalDiagrams_badge.svg" width="72" alt="The logo of FunctionalDiagrams: the exchange vacuum diagram"></a></td>
    <td>
      <a href="https://n4sd4q.github.io/FunctionalDiagrams/"><b>FunctionalDiagrams</b></a> — Feynman diagrams from functional derivatives<br>
      Perturbation theory and effective actions as one does them on paper: Luttinger–Ward, parquet, Hedin, Matsubara sums,
      dimensional regularization and one-loop QED, every diagram drawn.<br>
      <a href="https://n4sd4q.github.io/FunctionalDiagrams/">Website</a> ·
      <a href="https://n4sd4q.github.io/FunctionalDiagrams/Showcase/FunctionalDiagrams_Showcase.pdf">Showcase</a> ·
      <a href="https://n4sd4q.github.io/FunctionalDiagrams/Documentation/FunctionalDiagrams_Manual.pdf">Manual</a> ·
      <a href="https://github.com/n4sd4q/FunctionalDiagrams">Repository</a>
      <a href="https://github.com/n4sd4q/FunctionalDiagrams/releases/latest"><img src="https://img.shields.io/github/v/release/n4sd4q/FunctionalDiagrams?label=release&color=18587E" alt="latest release" align="right"></a>
    </td>
  </tr>
  <tr>
    <td width="96" align="center"><a href="https://n4sd4q.github.io/FermiWick/"><img src="logos/FermiWick_badge.svg" width="72" alt="The logo of FermiWick: two Wick contractions drawn as brackets with arrows"></a></td>
    <td>
      <a href="https://n4sd4q.github.io/FermiWick/"><b>FermiWick</b></a> — fermion operators, as symbols and as matrices<br>
      Normal ordering with compact local operators, Wick's theorem in Gaussian states declared by their symmetries, mean
      field of any order, Gutzwiller projectors, and exact diagonalisation on symmetry sectors.<br>
      <a href="https://n4sd4q.github.io/FermiWick/">Website</a> ·
      <a href="https://n4sd4q.github.io/FermiWick/Showcase/FermiWick_Showcase.pdf">Showcase</a> ·
      <a href="https://n4sd4q.github.io/FermiWick/Documentation/FermiWick_Manual.pdf">Manual</a> ·
      <a href="https://github.com/n4sd4q/FermiWick">Repository</a>
      <a href="https://github.com/n4sd4q/FermiWick/releases/latest"><img src="https://img.shields.io/github/v/release/n4sd4q/FermiWick?label=release&color=8A2880" alt="latest release" align="right"></a>
    </td>
  </tr>
</table>

The mark of the family is the smallest Hubbard cluster that both packages treat, one by diagrams and the other by
operators: a plaquette of four sites, with hoppings along its sides and an interaction along a diagonal.

## This repository

It holds the website, served by GitHub Pages at <https://n4sd4q.github.io/>, and the look that the packages share.

<details>
<summary>The common look</summary>

Every package has one hue: a gradient from a dark start to a lighter end, a solid accent (headings, links, buttons) and a
light tint (one element of its logo, its accent on dark pages); white text has a contrast of at least 4.5:1 on both ends
of the gradient. The logos share one language: a rounded square in the gradient, its central object in white and one
element in the tint ([`logos/`](logos)). Each package copies the files of [`design/`](design) when it builds its
documents, so that a change here never breaks a package:

| File | |
|---|---|
| [`palette.json`](design/palette.json) | the colours of each package |
| [`n4sd4q.sty`](design/n4sd4q.sty), [`n4sd4q-palette.tex`](design/n4sd4q-palette.tex) | the LaTeX style of the manuals and showcases: fonts, headings, the boxes of code and output, the title band in the gradient |
| [`family.css`](design/family.css) | the stylesheet of the websites, light and dark |

</details>

## License

The website and the design files are free software, under the [GNU General Public License, version 3 or
later](LICENSE), as the packages. To cite a package, see its `CITATION.cff`.
