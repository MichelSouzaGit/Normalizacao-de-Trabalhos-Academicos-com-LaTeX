# **Exemplo de uma tabela simples em LaTeX**

*Copie e cole no seu documento do overleaf e modifique da forma que precisar*

```
\begin{table}[]
\centering
\caption{Cronograma das Etapas do Projeto}
\label{tab:tabela1}
\begin{tabular}{lll}
\hline
\multicolumn{3}{c}{\textbf{Cronograma do Projeto}} \\ \hline
\multicolumn{1}{c|}{\textbf{Etapas}} & \multicolumn{1}{c|}{\textbf{Data de Início}} & \multicolumn{1}{c}{\textbf{Data de Término}} \\ \hline
\multicolumn{1}{l|}{1} & \multicolumn{1}{l|}{27/02/2024} & 29/02/2024 \\ \hline
\multicolumn{1}{l|}{2} & \multicolumn{1}{l|}{11/03/20244} & 14/03/2024 \\ \hline
\multicolumn{1}{l|}{3} & \multicolumn{1}{l|}{19/03/2024} & 23/03/2024 \\ \hline
\end{tabular}
\end{table}
```

**Obs.:** Se você não tem familiaridade em trabalhar com tabelas ![Clique aqui]{https://www.tablesgenerator.com/#} para visitar um site que gera tabelas LaTeX para você
