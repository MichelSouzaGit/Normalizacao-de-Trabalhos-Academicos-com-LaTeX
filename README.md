# Normalização de Trabalhos Acadêmicos com LaTeX
Repositório destinado a disponibilizar o material do curso de Normalização de Trabalhos Acadêmicos com LaTeX.

## Passos Iniciais em um documento ABNT no LaTeX: Pacotes Essenciais

**Coloque no Preâmbulo do seu documento**

```
\documentclass [a4paper, 12pt]{article} % define o documento como artigo de papel tamanho A4 e tamanho de fonte 12

\usepackage[utf8]{inputenc} % permite o uso de acentuação

\usepackage[brazil]{babel} % deixa o documento em pt-br

\usepackage[t1]{fontenc} % para copiar e colar de outras fontes sem maiores problemas

\usepackage{amsmath, amsthm, amsfonts, amssymb, dsfont, mathtools} % pacotes matemáticos

\usepackage{graphicx, xcolor, multirow, multicol} % para trabalhar com imagens e tabelas
```

## Formatações Inicias de Página, Parágrafo e Texto

### Margens em ABNT

**Coloque no Preâmbulo do seu documento**

```
\usepackage[lmargin=3cm, rmargin=2cm, tmargin=3cm, bmargin=2cm]{geometry} % define as margens do documento de acordo com a ABNT
```

### Parágrafo em ABNT

**Coloque no Preâmbulo do seu documento**

```
\usepackage{indentfirst} % faz com que todos os parágrafos sejam devidamente identados
```
**Obs.: **Naturalmente, um documento LaTeX tem formatações de parágrafo com espaçamento de 1,5 cm entre linhas e de identação

### Formatação de texto: Negrito, Itálico e Sublinhado


**Coloque o texto que deseja formatar em Negrito, Itálico ou Sublinhado dentro das chaves { }**
```
\textbf{texto em negrito vem aqui} % negrito em LaTeX

\underline{texto sublinhado vem aqui} % sublinhado em LaTeX

\textit{texto em itálico vem aqui} % itálico em LaTeX
```

### Seções e Subseções

**Coloque aonde deseja iniciar uma nova seção ou subseção no seu documento**
```
\section{nome da seção} % indica uma seção do seu documento

\subsection{nome da subseção} % indica uma subseção de uma seção maior
```
