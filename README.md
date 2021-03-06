# LaTeX course : Thesis module
Module's sample files and figures:

## Goal:
To build a basic thesis template to become familiar with:
- S1 : Learn to write an abstract,
- S1 : Learn the basic structure of a thesis document,
- S1 : Learn to build a fancy header and footer,
- S1 : Learn to build the bibliography using biblatex.

## Writing an abstract:
1. The old-school [AbstractMaker.pdf](./abstract_maker/AbstractMaker.pdf),
2. The online [Abstract Generator](https://www.classgist.com/abstract-generator.aspx).

## Starting hint:
```latex
% Set Report class
\documentclass{report} % double-sided pages
\usepackage[utf8]{inputenc}
\usepackage{graphicx}
\graphicspath{ {figures/} } % Add path the figures

% Title page info
\title{
    {My Cool Research Project Name}\\
    {\large Institution Name}\\
    \vspace{1cm}
    {\includegraphics{TeXlion}}
}
\author{Manuel A. D\'iaz}
\date{\today}

% Begin thesis document
\begin{document}

    % Title page
    \maketitle

    % The abstract
    \chapter*{Abstract}
    Briefly: what have you done? and why it matters?

    % A dedication
    \chapter*{Dedication}
    To my mom, dad, dog, ...

    % Statement
    \chapter*{Declaration}
    I declare this is an original work ...

    % Acknowledgments
    \chapter*{Acknowledgements}
    I wish to thank ...

    % The Table of contents
    \tableofcontents

    % Introduction
    \chapter{Introduction}
    Let me tell you a story ...

    % Chapter 2: Methodology part I
    \chapter{Title of Chapter 2}
    Some method we used for ...

    % Chapter 3: Methodology part II
    \chapter{Title of Chapter 3}
    Another method we also used for ...

    % Chapter 4: Experiments and results
    \chapter{Experiments and Results}
    To verify our idea, we did ...

    % Chapter 5: Conclusions and Future work
    \chapter{Conclusion}
    We conclude that ...

    % Appendix
    \appendix
    \chapter{Title of Appendix Chapter}
    Here are some important details ...

% End thesis document
\end{document}
```
## Complementary material in `figures/` : 
<img src="./figures/TeXlion.jpg" alt="TeX-logo" width="200"/>
<img src="./figures/TecNM.png" alt="Uni-Logo" width="200"/>

## References
1. The Thesis tutorial by [overleaf.com](https://www.overleaf.com/learn/latex/How_to_Write_a_Thesis_in_LaTeX_(Part_1)%3A_Basic_Structure),
2. Dr. Trefor Bazett, youtube video: [My favorite LaTeX packages for writing beautiful math documents](https://youtu.be/331YxgOJUGw),
3. The Markdown [cheat sheet](https://www.markdownguide.org/cheat-sheet/).
