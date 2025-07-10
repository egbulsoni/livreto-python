# Python para todos: um guia acessível

Este repositório contém o código-fonte em LaTeX do livro **Python para todos: um guia acessível**, voltado para iniciantes e autodidatas que queiram aprender programação com a linguagem Python de forma clara, prática e direta.

## 📦 Como compilar

Para compilar o PDF do livro localmente, é necessário ter um sistema LaTeX instalado (como TeX Live, MiKTeX ou equivalente). Você pode usar ferramentas como TeXstudio ou compilar manualmente via terminal:


```bash
pdflatex -output-directory=. -shell-escape -synctex=1 -interaction=nonstopmode %.tex
