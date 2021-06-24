\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{graphicx}

\title{OS11}
\author{Mohammad Soroush}
\date{June 2021}

\begin{document}

\maketitle

\section{Introduction}
Mohammad Soroush.\\
At age 21.\\
Sadjad University\\
Mashhad...Iran\\

\section{Image}
\includegraphics{download.jpg}

\section{Table}

 \begin{tabular}{||c c c c||} 
 \hline
 Col1 & Col2 & Col2 & Col3 \\ [0.5ex] 
 \hline\hline
 1 & 6 & 12 & 15 \\ 
 \hline
 2 & 7 & 13 & 16 \\
 \hline
 3 & 9 & 14 & 17 \\
 \hline
 4 & 10 & 13 & 18 \\
 \hline
 5 & 11 & 14 & 19 \\ [1ex] 
 \hline
\end{tabular}

\section{math formula}


  \[ \sum_{n=1}^{\infty} 2^{-n} = 1 \]

\section{programming}

int main ()\\
{
  std::vector<int> myvector;\\

 
  for (int i=1; i<=10; i++) myvector.push_back(i);\\

  
  myvector.erase (myvector.begin()+5);\\

  
  myvector.erase (myvector.begin(),myvector.begin()+3);\\

  std::cout << "myvector contains:";\\
  
  
  for (unsigned i=0; i<myvector.size(); ++i)\\
    std::cout << ' ' << myvector[i];\\
  std::cout << '\n';\\

  return 0;\\
}//


\end{document}
