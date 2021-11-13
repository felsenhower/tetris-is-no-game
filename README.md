# tetris-is-no-game

* **T**etris **i**s **n**ot a **g**ame.
* Tetris is serious matter.

## Example

![tetris](https://github.com/felsenhower/tetris-is-no-game/raw/master/samples/sample.png)

```latex
\documentclass[12pt,a4paper]{article}

[...]

\usepackage{ting}

\begin{document}

[...]

\begin{tikzpicture}
	\begin{tetris}[bsc_cis_physik]
		\drawsemester{1. Semester\\(WiSe)}
			\drawmodule{6}{tetris_blue}{transparent}{black}{Softwareentwicklung I}
			\drawmodule{3}{tetris_yellow}{transparent}{black}{CiS-\\Proseminar}
			\drawmodule{12}{tetris_red}{transparent}{black}{Physik I}
			\drawmodule{9}{tetris_gray}{transparent}{black}{Mathematik I für Physiker}
		\drawsemester{2. Semester\\(SoSe)}
			\drawmodule{9}{tetris_blue}{transparent}{black}{Formale Grundlagen\\der Informatik I}
			\drawmodule{12}{tetris_red}{transparent}{black}{Physik II}
			\drawmodule{9}{tetris_gray}{transparent}{black}{Mathematik II für Physiker}
		\drawsemester{3. Semester\\(WiSe)}
			\drawmodule{6}{tetris_blue}{transparent}{black}{Algorithmen und\\Datenstrukturen}
			\drawmodule{6}{tetris_blue}{transparent}{black}{Grundlagen von\\Datenbanken}
			\drawmodule{8}{tetris_red}{transparent}{black}{Physikalisches Praktikum I}
			\drawmodule{9}{tetris_gray}{transparent}{black}{Numerische Mathematik}
		\drawsemester{4. Semester\\(SoSe)}
			\drawmodule{6}{tetris_blue}{transparent}{black}{Softwareentwicklung II}
			\drawmodule{9}{tetris_blue}{transparent}{black}{Programmierung für\\Naturwissenschaften}
			\drawmodule{9}{tetris_red}{transparent}{black}{Theoretische Physik II}
			\drawmodule{6}{tetris_gray}{transparent}{black}{Stochastik}
		\drawsemester{5. Semester\\(WiSe)}
			\drawmodule{9}{white}{black}{black}{Wahlpflicht 2\\Mathematik / Informatik / Physik}
			\drawmodule{6}{tetris_yellow}{transparent}{black}{Computational\\Physics}
			\drawmodule{6}{tetris_yellow}{transparent}{black}{Projekt\\CiS Physik}
			\drawmodule{9}{white}{black}{black}{Wahlpflicht 1\\Mathematik III für Physiker /\\Formale Grundl. d. Informatik II}
		\drawsemester{6. Semester\\(SoSe)}
			\drawmodule{9}{white}{black}{black}{Wahlpflicht 2\\Mathematik / Informatik / Physik}
			\drawmodule{7}{tetris_red}{transparent}{black}{Wahlpflicht 3\\Physik}
			\drawmodule{3}{tetris_yellow}{transparent}{black}{CiS-\\Seminar}
			\drawmodule{12}{tetris_yellow}{transparent}{black}{Abschlussmodul\\(Bachelorarbeit)}
	\end{tetris}
	\draw
		[line width=1pt,decorate,decoration={brace,amplitude=10pt,raise=10pt},yshift=0pt]
		(bsc_cis_physik.north east) -- (bsc_cis_physik.south east)
		node [black,midway,xshift=30mm] {\shortstack{B. Sc.\\Computing in Science\\(SP Physik)}}
	;
	%
  	\begin{tetris}[msc_informatik]
  		\drawsemester{1. Semester\\(WiSe)}
  			\drawmodule{9}{tetris_blue}{transparent}{black}{Wahlpflicht Theorie}
  			\drawmodule{9}{tetris_blue}{transparent}{black}{Wahlpflicht}
  			\drawmodule{6}{tetris_blue}{transparent}{black}{Vertiefung\\Informatik}
  			\drawmodule{6}{white}{black}{black}{Freier\\Wahlbereich}
  		\drawsemester{2. Semester\\(SoSe)}
  			\drawdummy{6}
  			\drawmodule{9}{tetris_blue}{transparent}{black}{Wahlpflicht}
  			\drawmodule{6}{tetris_blue}{transparent}{black}{Vertiefung\\Informatik}
	  		\drawmodule{9}{white}{black}{black}{Freier\\Wahlbereich}
	  	\drawsemester{3. Semester\\(WiSe)}
  			\drawdummy{6}
  			\drawmodulemulti{2}{tetris_blue}{transparent}{black}{Projekt}
  			\drawintegrated{2}{1}{3}{0}{Seminar}
  			\drawmodule{9}{tetris_blue}{transparent}{black}{Wahlpflicht}
  			\drawmodule{6}{tetris_blue}{transparent}{black}{Vertiefung\\Informatik}
  			\drawmodule{9}{white}{black}{black}{Freier\\Wahlbereich}
  		\drawsemester{4. Semester\\(SoSe)}
  			\drawmodule{30}{tetris_blue}{transparent}{black}{Abschlussmodul (Masterarbeit)}
  	\end{tetris}
	\draw
		[line width=1pt,decorate,decoration={brace,amplitude=10pt,raise=10pt},yshift=0pt]
		(msc_informatik.north east) -- (msc_informatik.south east)
		node [black,midway,xshift=20mm] {\shortstack{M. Sc.\\Informatik}}
	;
	%
  	\begin{tetris}[msc_physik]
  		\drawsemester{1. Semester\\(WiSe)}
  			\drawmodule{24}{tetris_red}{transparent}{black}{Vertiefung Physik}
  			\drawmodule{6}{white}{black}{black}{Freier Wahlbereich}		
  		\drawsemester{2. Semester\\(SoSe)}
  			\drawmodule{24}{tetris_red}{transparent}{black}{Vertiefung Physik}
  			\drawmodule{6}{white}{black}{black}{Freier Wahlbereich}		
  		\drawsemester{3. Semester\\(WiSe)}
  			\drawmodule{15}{tetris_red}{transparent}{black}{Einarbeitungsprojekt}
  			\drawmodule{15}{tetris_red}{transparent}{black}{Vorbereitungsprojekt}
  			\drawintegrated{1}{1}{3}{0}{Seminar}
  		\drawsemester{4. Semester\\(SoSe)}
  			\drawmodule{30}{tetris_red}{transparent}{black}{Abschlussmodul (Masterarbeit)}
  	\end{tetris}
	\draw
		[line width=1pt,decorate,decoration={brace,amplitude=10pt,raise=10pt},yshift=0pt]
		(msc_physik.north east) -- (msc_physik.south east)
		node [black,midway,xshift=20mm] {\shortstack{M. Sc.\\Physik}}
	;
	%
	\legend{tetris_blue}{Informatik}
	\legend{tetris_red}{Physik}
	\legend{tetris_gray}{Mathematik}
	\legend{tetris_yellow}{Naturwissenschaftliche Informatik}
\end{tikzpicture}

[...]

\end{document}
```