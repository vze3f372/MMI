This Repo is used for Sustainable Electronics Laboratory repot. 

Some example usage for forced float and multiple figures: 

\begin{figure}[H]
	\centering
	\includegraphics[width=0.75\linewidth]{NA.png}
	\caption{\small{Battery revenue trend for North America in billions of dollars\cite{noauthor_battery_nodate}}}
	\label{fig:NA}
\end{figure}




\begin{figure}[H]
  \centering
  \begin{subfigure}[b]{0.45\linewidth}
    \includegraphics[width=\linewidth]{Acid.png}
    \caption{Effect of acid concentration}
    \label{fig:acid}
  \end{subfigure}
  \begin{subfigure}[b]{0.45\linewidth}
    \includegraphics[width=\linewidth]{Heat.png}
    \caption{Heat effects}
    \label{fig:heat}
  \end{subfigure}
  \caption{\small{Heat and acid effects on REE recovery\cite{yang_rare_2014}}}
  \label{fig:effects}
\end{figure}


