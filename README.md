Apple Documentation Style - LaTeX Template
====================================

To enable syntax highlighting you need to install Pygments and use xelatex for compilation:

1. sudo easy_install Pygments
2. xelatex  -file-line-error -synctex=1 -shell-escape -interaction=nonstopmode "File.tex"

To integrate the template with TeXShop:

1. navigate to ~/Library/TeXShop/Engines
2. open XeLaTeX.engine file
3. add two additional parameters -shell-escape -interaction=nonstopmode


Table Of Contents

![Table Of Contents](https://raw.github.com/wnagrodzki/AppleDocumentationStyleLatexTemplate/master/Screen%20Shots/TOC.png "Table Of Contents")

Sections, subcection, and subsubsections style

![Sections, subsections](https://raw.github.com/wnagrodzki/AppleDocumentationStyleLatexTemplate/master/Screen%20Shots/Sections.png "Sections, subsections")

Code listing

![Code listing](https://raw.github.com/wnagrodzki/AppleDocumentationStyleLatexTemplate/master/Screen%20Shots/Codelisting.png "Code listing")

- [ ] Title page
- [x] Table of contents
- [x] Section, subcectio, and subsubsection style
- [x] Code listing
- [x] Syntax highlighting
