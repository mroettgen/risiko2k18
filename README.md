# risiko2k18 [![Build Status](https://travis-ci.org/mroettgen/risiko2k18.svg?branch=master)](https://travis-ci.org/mroettgen/risiko2k18)
Hier entstand in der Vergangenheit eine wundervolle Hausarbeit.

## Konventionen
Joshs komische Dinger zitieren wir mit `m = B05` und `w = B06`

Mehrzeilige Zitate: `\begin{quote} ... \end{quote}`

Referenz für Quellen: `(B04, Z. 123)` innerhalb des Quote-Blocks, für aufgeteilte Dateien entsprechend `(B05.2, Z. 123)`

## Wichtige Befehle
Kapitel: `\section{Kapitelüberschrift}`

Unterkapitel: `\subsection{Kapitelüberschrift}`

Kapitel, die nicht im Inhaltsverzeichnis auftauchen: `\section*{Kapitelüberschrift}`

Non-breaking small space: `\,`

Grafiken einfügen:

``` TeX
\begin{figure}[htp]
    \centering
    \includegraphics[width=13cm]{die_grafik.png}
    \caption{Bildunterschrift hier einfügen}
    \label{referenz-auf-bild}
\end{figure}
```
