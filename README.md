# tetris-is-no-game
* **T**etris **i**s **n**ot a **g**ame.
* Tetris is serious matter.
* If used correctly, the ting might go like
![tetris](https://github.com/felsenhower/tetris-is-no-game/raw/master/samples/14felgenh.png)
```latex
\documentclass[12pt,a4paper]{article}

[...]

\usepackage{ting}

\begin{document}

[...]

\begin{tikzpicture}
	\begin{tetris}[bsc_informatik]
  		\drawsemester{1. Semester\\(WiSe)}
  			\drawmodule{6}{tetris_blue}{transparent}{black}{Softwareentwicklung I}
  			\drawdummy{9}
  			\drawmodule{9}{tetris_blue}{transparent}{black}{Rechnerstrukturen}
  			\drawmodule{6}{tetris_blue}{transparent}{black}{Informatik im\\{}Kontext}
  		\drawsemester{2. Semester\\(SoSe)}
  			\drawmodule{6}{tetris_blue}{transparent}{black}{Softwareentwicklung II}
  			\drawdummy{9}
  			\drawmodulemulti{2}{tetris_gray}{transparent}{black}{Mathematik für Studierende\\{}der Informatik}
  			\drawmodule{3}{white}{black}{black}{Methoden-\\{}kompetenz}
  			\drawmodule{3}{tetris_blue}{transparent}{black}{Proseminar}
  			\drawmodule{9}{tetris_blue}{transparent}{black}{Formale Grundlagen\\{}der Informatik I}
  		\drawsemester{3. Semester\\(WiSe)}
  			\drawmodule{6}{tetris_blue}{transparent}{black}{Algorithmen und\\{}Datenstrukturen}
  			\drawmodule{24}{white}{black}{black}{Wahlpflicht}
  		\drawsemester{4. Semester\\(SoSe)}
  			\drawmodule{6}{tetris_blue}{transparent}{black}{Praktikum}
  			\drawmodule{24}{white}{black}{black}{Wahlpflicht}
  		\drawsemester{5. Semester\\(WiSe)}
  			\drawmodule{9}{white}{black}{black}{Wahlpflicht}
  			\drawmodule{9}{white}{black}{black}{Freier Wahlbereich}
  			\drawmodule{9}{tetris_blue}{transparent}{black}{Projekt}
  			\drawmodule{3}{tetris_blue}{transparent}{black}{Seminar}
  		\drawsemester{6. Semester\\(SoSe)}
  			\drawmodule{9}{white}{black}{black}{Wahlpflicht}
  			\drawmodule{9}{white}{black}{black}{Freier Wahlbereich}
  			\drawmodule{12}{tetris_blue}{transparent}{black}{Abschlussmodul\\{}(Bachelorarbeit)}
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
  			\drawintegrated{2}{1}{3}{Seminar}
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
  			\drawintegrated{1}{1}{3}{Seminar}
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
* If used incorrectly, the ting might also go
  * “Skrrrrrrrrrrrahh”
  * “Pap, pap, ka-ka-ka”
  * “Skidiki-pap-pap”
  * and a “Pu-pu-pudrrrr-boom”
  * “Skya”
  * “Du-du-ku-ku-dun-dun”
  * “Poom, poom”, you dun know

## Documentation

### The tetris environment
* Place all ting macros inside a `tetris` environment
* You can append a name to the environment as an optional parameter
```latex
\documentclass[...]

[...]

\usepackage{ting}

\begin{document}

[...]

\begin{tikzpicture}
	\begin{tetris}[optional_name]
		[...]	
	\end{tetris}
\end{tikzpicture}

[...]

\end{document}
```

* If you name the environment, you can refer to its bounding box, e.g. to put a brace next to it:
```latex
	\begin{tetris}[cool_name]
		[...]	
	\end{tetris}
	\draw
		[line width=1pt,decorate,decoration={brace,amplitude=10pt,raise=10pt},yshift=0pt]
		(cool_name.north east) -- (cool_name.south east) % <-- Enter name here
		node [black,midway,xshift=20mm] {\shortstack{This is\\a tetris!}}
	;
```

### Creating semesters
* You can create a new row inside the tetris via `\drawsemester`
* This macro will break the line inside the tetris and assign all following modules to the new semester
* Arguments:
  * `#1`: Name of the semester (the text to show at the left)
