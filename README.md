# Beamer_presentation
##Files
`Beamer_presentation_example_plain.tex` simple example of a beamer presentation with corresponding pdf 
`Beamer_presentation_example.tex` example of a beamer presentation with a number of modifications and the corresponding pdf



##Settings for sublime

Install LatexTools from "Install Package"

Reconfigure and migrate settings
http://tex.stackexchange.com/questions/165339/latextools-you-need-to-migrate-your-preferences-see-the-readme-file-for-instru

Once you've built a .tex file, open the pdf in skim
"Skim" -> "preferences" -> "Sync" -> "Preset: Sublime Text 2"
Check box for "Check for file changes"

###LatexTools in sublime
https://github.com/SublimeText/LaTeXTools  
`cmd-b` (i.e. hit the `cmd` and `b` key) to build  
`cmd-l` then `v` to view pdf in skim  
`cmd-shift-click` where `click` is a mouse click to inverse search from pdf in skim to line in sublime  
`cmd-l` then `e` to create an environment around an argument (similar to autocomplete) e.g. type `itemize` followed by `cmd-l` `e` gives   
```
\begin{itemize}

\end{itemize}
```
`cmd-l`then `c` for commands e.g. 

`\frametitle{}`
