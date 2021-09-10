---
fontsize: 
- 12pt
papersize: 
- a4
linestretch: 
- 1.15
geometry: 
- "left=4cm,right=3cm,top=3cm,bottom=3cm"
mainfont: Arial.TTF
lang: id
header-includes : |
    \usepackage{float}
    \let\origfigure\figure
    \let\endorigfigure\endfigure
    \renewenvironment{figure}[1][2]{
    \expandafter\origfigure\expandafter[H]
    } {
      \endorigfigure
    }

---

\pagenumbering{gobble}
