 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Deedy - One Page Two Column Resume
% LaTeX Template
% Version 1.2 (16/9/2014)
%
% Original author:
% Debarghya Das (http://debarghyadas.com)
%
% Original repository:
% https://github.com/deedydas/Deedy-Resume
%
% IMPORTANT: THIS TEMPLATE NEEDS TO BE COMPILED WITH XeLaTeX
%
% This template uses several fonts not included with Windows/Linux by
% default. If you get compilation errors saying a font is missing, find the line
% on which the font is used and either change it to a font included with your
% operating system or comment the line out to use the default font.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% 
% TODO:
% 1. Integrate biber/bibtex for article citation under publications.
% 2. Figure out a smoother way for the document to flow onto the next page.
% 3. Add styling information for a "Projects/Hacks" section.
% 4. Add location/address information
% 5. Merge OpenFont and MacFonts as a single sty with options.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% CHANGELOG:
% v1.1:
% 1. Fixed several compilation bugs with \renewcommand
% 2. Got Open-source fonts (Windows/Linux support)
% 3. Added Last Updated
% 4. Move Title styling into .sty
% 5. Commented .sty file.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% Known Issues:
% 1. Overflows onto second page if any column's contents are more than the
% vertical limit
% 2. Hacky space on the first bullet point on the second column.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\documentclass[]{deedy-resume-openfont}
\usepackage{fancyhdr}
 
\pagestyle{fancy}
\fancyhf{}
 
\begin{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     LAST UPDATED DATE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     TITLE NAME
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\namesection{Minhaj}{Ahmed}{ \urlstyle{same}\href{https://www.facebook.com/umiddaaaa/}{\bf Facebook}   |   \href{https://www.linkedin.com/in/minhajumid}{\bf LinkedIn}\\
\href{mailto:minhajumid987@gmail.com}{minhajumid987@gmail.com} | +880.1705.239294
}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN ONE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{minipage}[t]{0.33\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EDUCATION
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Education} 

\subsection{Metropolitan University}
\descript{B.S.C Eng in Computer Science}
\location{Jan 2022 | Sylhet, Bangladesh}
\sectionsep

\subsection{J.C.P.S college}
\descript{Higher secondary certificate}
\location{July 2017 | Sylhet, Bangladesh}
\location{  GPA: 5.00 / 5.00 }
\sectionsep

\subsection{Sylhet Govt Pilot School}
\location{Jan 2015 | Sylhet, Bangladesh}
\location{  GPA: 5.00 / 5.00 }
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     LINKS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Links} 
Facebook:// \href{https://www.facebook.com/umiddaaaa/}{\bf Minhaj Ahmed} \\
Github:// \href{https://github.com/Minhaj10}{\bf Minhaj10} \\
LinkedIn://  \href{https://www.linkedin.com/in/minhajumid}{\bf Minhaj ahmed} \\
Telegram://  \href{https://t.me/Minhaj_10}{\bf Minhaj} \\
Twitter://  \href{https://twitter.com/Minhaj_umid_10}{\bf @minhaj\_umid\_10} \\

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     COURSEWORK
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Coursework}

\subsection{Undergraduate}
Computer Technology \\
Structured Programming \\
Data structure \\
Algorithm \\
Object oriented programming \\
Operating Systems \\
Microprocessor \& assembly language \\
Artificial Intelligence \\
Telecommunication Principles \\
Database management System \\
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SKILLS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Skills}
\subsection{Programming}
\location{Solved 1000+ Problems}
\location{Participated in 100+ online contest}
C++ \textbullet{}   C \textbullet{}   Html \textbullet{} Css \textbullet{} \\
\location{Familiar:}
Javescript \textbullet{} React \textbullet{} Redux \textbullet{} MySQL \textbullet{} Nodejs \textbullet{} Express \textbullet{} PHP \\

\location{50+ database problem solved in Hackerrank}
\sectionsep
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN TWO
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\end{minipage} 
\hfill
\begin{minipage}[t]{0.66\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXPERIENCE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{PROJECT}

\sectionsep
\runsubsection{Travel Freak}
\descript{| Social media React app }
\href{https://github.com/Minhaj10/Travelfreak}{\bf Githib Link} 
\sectionsep
\begin{tightemize}
\item Travel freak is a full stack application where people can sign in with their email id’s or sign up for an account. After log in they can share their experience by making a post and they can view other post as well. 
\item Javascript,react,redux is used as front-end.
\item Nodejs,express,mongodb is used as back-end.
\end{tightemize}
\sectionsep

\runsubsection{Tict-Tac-Toe AI Bot}
\descript{| Processed by minmax AI algorithm}
\href{https://github.com/Minhaj10/AIproject}{\bf Github Link} 
\sectionsep
\begin{tightemize}
\item This is a tic-tac-toe game built with AI feature. There are two main files in this project: runner.py and tictactoe.py. tictactoe.py contains all of the logic for playing the game, and for making optimal moves. runner.py has been implemented for you, and contains all of the code to run the graphical interface for the game. 
\item Once you’ve completed all the required functions in tictactoe.py, you should be able to run python runner.py to play against your AI!
\end{tightemize}
\sectionsep
\runsubsection{QuickShare}
\descript{| A web platfrom using semantic UI}
\href{https://github.com/Minhaj10/Finsta}{\bf Github Link} 
\begin{tightemize}
\item Finstagram is a social media site where people can share their stories by posting texts. 
\item For database management system GraphQl & MongoDB combinedly used.
\item React \& Redux used in frontend for making frontend UI more beautiful 

\end{tightemize}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     RESEARCH
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{achievement}

\runsubsection{4 star Coder on Codechef}
\descript{| \href{https://www.codechef.com/users/minhaj_100}{\bf Codechef Handle} }
\location{Highest contest Rank- January Challenge-2021 : 212/40000}
20+ Contest participation  
\sectionsep


\runsubsection{60+ Rated contest in Codeforces}
\descript{| \href{https://codeforces.com/profile/Minhajumid}{\bf Codeforces Handle} }
\location{Highest contest Rank- Codeforces global round-13-Rank :3854/25000}

\sectionsep

\runsubsection{Participated in ICPC \& NCPC}
\location{| 2018,2019}
\sectionsep

\runsubsection{ACM problem solving history}
\location{|  \href{https://www.stopstalk.com/user/profile/Minhaj_10}{\bf Stopstalk Handle}}
\sectionsep
\runsubsection{Other coding platform performance}
\location{|  \href{https://atcoder.jp/users/Minhaj_10}{\bf Atcoder Handle}}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     AWARDS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Experience} 
\begin{tabular}{rll}
2018-2019	     & Intern  & Triangle It Hub\\
     2018	     & Trainer  & Workshop of 70+ students about competitive programming
\end{tabular}

\section{extra curricular activities} 
\begin{tabular}{rll}
2019-2021	     & Sports co-ordinator  & Cse Socitey,Metropolitan University\\
 \\
\end{tabular}
\sectionsep
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     PUBLICATIONS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\end{minipage} 
\end{document}  \documentclass[]{article}
