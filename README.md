# fachseminar-template
Dies ist eine Latex-Vorlage für die 3. International Students Conference

## Word
Eine Word Vorlage befindet sich im Unterordner "word".

## Table
Um sicherzustellen, dass der Text an der richtigen Stelle unterbrochen wird, sollte vor und nach der Tabelle je eine Leerzeile stehen.
```tex

\begin{table}[!h]
  \centering
  \label{tab:table1}
  \begin{tabular}{l|c||r}
    1 & 2 & 3\\
    \hline
    a & b & c\\
  \end{tabular}
  \caption{Caption for the table.}
\end{table}

```

## Graphics
Um sicherzustellen, dass der Text an der richtigen Stelle unterbrochen wird, sollte vor und nach der Grafik je eine Leerzeile stehen.
```tex

\begin{figure}[H]
    \centering
    \includegraphics[width=5cm]{fhbielefeld_logo.png}
    \caption{Write some caption here}\label{visina8}
    \vspace{-12pt}
\end{figure}

```

Das Attribut *vspace* sorgt für den passendeb Abstand zum nachfolgenden Absatz


## Footnotes
```tex
Tatsache\footnote{Text}
```