# **Exemplos de lista em LaTeX**

## **Preparações para se trabalhar com listas enumeradas no LaTeX**
## **Coloque no preâmbulo do seu documento**

```
\usepackage{enumerate} % permite trabalhar com listas enumeradas
```

**Exemplo de Lista de pontos**

```
\begin{itemize}
    \item A;
    \item B;
    \item C;
    \item D.
\end{itemize}
```

**Exemplo de Lista enumerada**

```
\begin{enumerate}
    \item E;
    \item F;
    \item K;
    \item G;
    \item H.
\end{enumerate}

```

**Exemplo de Lista enumerada com algorismos romanos**

```
\begin{enumerate}
    \item[I).] E;
    \item[II).] F;
    \item[III.] G;
    \item[IV.] H.
\end{enumerate}

```

**Obs.:** Em trabalhos acadêmicos, sempre separe os itens de uma lista por ";" e 
sempre termine com "." no último item. 
