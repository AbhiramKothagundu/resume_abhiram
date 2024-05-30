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
\lastupdated

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     TITLE NAME
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\namesection{Abhiram}{Kothagundu}{ \urlstyle{same}\href{mailto:abhikothagundu@gmail.com}{abhikothagundu@gmail.com} | +91 8919288807 | Gudivada, Andhra Pradesh}

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

\subsection{IIIT Sri City}
\descript{B.Tech in Computer Science}
\location{2022 - Present | Chittoor, India}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     LINKS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Links} 
Github:// \href{https://github.com/AbhiramKothagundu}{\bf AbhiramKothagundu} \\
LinkedIn://  \href{https://www.linkedin.com/in/abhiram-kothagundu}{\bf abhiram-kothagundu} \\
CodeForces://  \href{https://codeforces.com/profile/abhiramkothagundu}{\bf abhiramkothagundu} \\
LeetCode://  \href{https://leetcode.com/u/abhikothagundu}{\bf abhikothagundu} \\

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     COURSEWORK
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Coursework}
\subsection{Undergraduate}
Artificial Intelligence \\
Computer Networks \\
Full Stack Web Development \\
Computer Architecture \\
Data Structures and Algorithms \\
Theory of Computation \\
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SKILLS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Skills}
\sectionsep
\subsection{Programming}
C \textbullet{} C++ STL \textbullet{} Java \textbullet{} Assembly (basics) \textbullet{} p5.js \textbullet{} C\# \textbullet{} JavaScript \textbullet{} Python \textbullet{} Rust (learning) \\
\sectionsep
\subsection{Web Development}
Express.js \textbullet{} Node.js \\
\sectionsep
\subsection{Database Management}
MongoDB \\
\sectionsep
\subsection{Game Development}
Unity \textbullet{} Blender \textbullet{} Unreal Engine \textbullet{} 3D Modelling and Animation\\
\sectionsep
\subsection{Cybersecurity}
Security Information and Event Management (SIEM) \\
Security Frameworks and Controls \\
Incident Response \\
Threat \& Vulnerability Management \\
\sectionsep
\subsection{Other Skills}
Linux \textbullet{} Git and Github \textbullet{} SQL \textbullet{} OpenGL \\
\sectionsep



%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     Hobbies
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Hobbies}
Gaming \textbullet{}
Art \textbullet{}
Fiction Books \\
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
%     ABOUT ME
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{About Me}
I am Abhiram, a dedicated and tech-passionate Computer Science enthusiast. My passion lies in exploring low-level computer systems, driven by a profound interest in how systems operate.

As an enthusiastic Developer, I have experience in JavaScript, NodeJS and React.js, along with a strong foundation in cybersecurity and game development. I actively seek opportunities to engage in innovative projects and research the complexities of technology. Committed to continuous learning and hands-on approaches, I aim to contribute meaningfully to the evolving field of computer science.
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXPERIENCE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Experience}
\runsubsection{IOTA Cybersecurity Club}
\descript{| Core Member }
\location{IIIT Sri City, Chittoor, India}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     CERTIFICATIONS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Certifications} 
\begin{itemize}
    \item \textbf{Google Cybersecurity Professional Certificate} \\
    \textit{Coursera, 2023}
    \item \textbf{Machine Learning Specialization by Andrew Ng} \\
    \textit{Coursera, 2023}
\end{itemize}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     PROJECTS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Projects}
\runsubsection{CodeRealms}
\descript{| Full Stack Development | \href{https://github.com/AbhiramKothagundu/CodeRealms}{GitHub} }
\begin{itemize}
    \item Developed an online coding contest hosting platform.
    \item Users can join realms to participate in coding contests.
    \item Enabled profile showcasing on social media.
\end{itemize}
\sectionsep

\runsubsection{Nightmare Labyrinth}
\descript{| Game Development | \href{https://github.com/AbhiramKothagundu/GlobalGameJam2024}{GitHub} }
\begin{itemize}
    \item Participated in GLOBALGAMEJAM2024 with the theme "MAKE ME LAUGH."
    \item Developed a game with unexpected surprises behind each door.
\item Designed to entertain and amuse players.
\end{itemize}
\sectionsep

\runsubsection{OWASP Testing Tool}
\descript{| Security Testing | \href{https://github.com/AkshatM1707/OWASPTool/tree/testBranch}{GitHub} }
\begin{itemize}
\item Utilizing the OWASP ZAP API to perform security scanning on web applications.
\item Conducting spidering, passive scanning, and active scanning to identify potential vulnerabilities.
\item Aimed at making the tool fast and providing understandable results.
\item Technologies used: Python, OWASP ZAP (Zed Attack Proxy).
\end{itemize}
\sectionsep

\end{minipage}
\end{document}
