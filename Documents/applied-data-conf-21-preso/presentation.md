---
title: "RAPping in the public sector: binding your legacy code into a pipeline with Python"
author: |
        | Ministry of Transport (MOT)
        | _Presented by_ Shrividya Ravi (Shriv)
output:  beamer_presentation
highlight: espresso
theme: metropolis
header-includes: |
  \usepackage{caption}
  \captionsetup{labelformat=empty,labelsep=none}
  \setbeamercolor{background canvas}{bg=white}
  \definecolor{teal}{rgb}{0.0, 0.576, 0.549}
  \setbeamercolor{frametitle}{bg=teal}
  \definecolor{alertmot}{rgb}{0.965, 0.62, 0.0}
  \setbeamercolor{alerted text}{fg=alertmot}
  \usepackage{tcolorbox}
  \definecolor{quotebg}{rgb}{0, 0.663, 0.937}
  \newtcolorbox{myquote}{colback=teal!10}
  \renewenvironment{quote}{\begin{myquote}}{\end{myquote}}
  \definecolor{links}{HTML}{2A1B81}
  \hypersetup{colorlinks,linkcolor=,urlcolor=links}
---

## Bind straggling scripts into pipelines
\centering
![](images/clean_pipeline.png){ width=65% }


## RAP your way to success - obtain and process

:::::: {.columns}
::: {.column}
\alert{exchangelib} obtain email data
\
\

![](images/exchangelib_annotated.png){ width=100% }
:::
::: {.column}
\alert{saspy} run sas code from python
\
\

![](images/saspy_annotated.png){ width=100% }
:::
::::::


## RAP your way to success - document

\alert{jupyter notebooks} create and document pipelines
\
\

![](images/figs_pipeline.png){ width=50% }


## RAPping with others is fun - get in touch!
- \alert{whoami} - Shrividya Ravi (Shriv)
- \alert{contact} - s.ravi@transport.govt.nz
- \alert{code} - [github.com/shriv](https://github.com/shriv/)
- \alert{ramblings} - [shriv-portfolio.netlify.app](https://shriv-portfolio.netlify.app)