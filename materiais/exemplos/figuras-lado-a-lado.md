# **Exemplo de como colocar Figuras lado a lado no LaTeX**

**Obs.:** Em cada um dos "includegraphics" dentro do "minipage" vai o nome 
das figuras que você quer colocar lado a lado.

```
 \begin{figure}[H]
        \begin{minipage}[!]{0.45\linewidth}
            \caption{Lanternas Chinesas 1}
            \includegraphics[width=1\linewidth]{lanternas (1).jpg} \\
            \legend{Fonte: Elaborada pelo autor}
            \label{fig:lanterna1}
        \end{minipage} 
        \begin{minipage}[!]{0.45\linewidth}
            \caption{Lanternas Chinesas 2}
            \includegraphics[width=1\linewidth]{lanternas (1).jpg} \\
            \legend{Fonte: Elaborada pelo autor}
            \label{fig:lanterna2}
        \end{minipage}       
    \end{figure}
```

**Obs.:** Colocar nomes intuitivos no "label" sempre é uma boa prática!
