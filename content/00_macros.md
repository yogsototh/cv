MACRO(markdown) = `markdown` ENDMACRO
MACRO(kramdown) = [`kramdown`](http://kramdown.rubyforge.org) ENDMACRO
MACRO(krambook) = [`krambook`](http://krambook.espozito.com) ENDMACRO

POSTMACRO(beginbox) = LATEX: \medskip\fbox{\colorbox{boxcolor}{\begin{minipage}{.80\linewidth}% HTML: &lt;div class="encadre"&gt; ENDMACRO

POSTMACRO(endbox) = LATEX: \end{minipage}}}\medskip HTML: &lt;/div&gt; ENDMACRO


POSTMACRO(xelatex) = LATEX: \XeLaTeX HTML: <span style="text-transform: uppercase">X<sub style="vertical-align: -0.5ex; margin-left: -0.1667em; margin-right: -0.125em; font-size: 1em">&#x018E;</sub>L<sup style="vertical-align: 0.15em; margin-left: -0.36em; margin-right: -0.15em; font-size: .85em">a</sup>T<sub style="vertical-align: -0.5ex; margin-left: -0.1667em; margin-right: -0.125em; font-size: 1em">e</sub>X</span> ENDMACRO

POSTMACRO(xelatex_) = LATEX: \XeLaTeX{} HTML: <span style="text-transform: uppercase">X<sub style="vertical-align: -0.5ex; margin-left: -0.1667em; margin-right: -0.125em; font-size: 1em">&#x018E;</sub>L<sup style="vertical-align: 0.15em; margin-left: -0.36em; margin-right: -0.15em; font-size: .85em">a</sup>T<sub style="vertical-align: -0.5ex; margin-left: -0.1667em; margin-right: -0.125em; font-size: 1em">e</sub>X</span>  ENDMACRO

POSTMACRO(latex) = LATEX: \LaTeX HTML: <span style="text-transform: uppercase">L<sup style="vertical-align: 0.15em; margin-left: -0.36em; margin-right: -0.15em; font-size: .85em">a</sup>T<sub style="vertical-align: -0.5ex; margin-left: -0.1667em; margin-right: -0.125em; font-size: 1em">e</sub>X</span> ENDMACRO

POSTMACRO(latex_) = LATEX: \LaTeX{} HTML:  <span style="text-transform: uppercase">L<sup style="vertical-align: 0.15em; margin-left: -0.36em; margin-right: -0.15em; font-size: .85em">a</sup>T<sub style="vertical-align: -0.5ex; margin-left: -0.1667em; margin-right: -0.125em; font-size: 1em">e</sub>X</span>  ENDMACRO

POSTMACRO(tex) = LATEX: \TeX HTML: <span style="text-transform: uppercase">T<sub style="vertical-align: -0.5ex; margin-left: -0.1667em; margin-right: -0.125em; font-size: 1em">e</sub>X</span> ENDMACRO

POSTMACRO(tex_) = LATEX: \TeX{} HTML: <span style="text-transform: uppercase">T<sub style="vertical-align: -0.5ex; margin-left: -0.1667em; margin-right: -0.125em; font-size: 1em">e</sub>X</span>  ENDMACRO

POSTMACRO(metapost) = LATEX: \MP HTML: METAPOST  ENDMACRO
POSTMACRO(metapost_) = LATEX: \MP{} HTML: METAPOST  ENDMACRO

