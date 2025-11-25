\usepackage{polynom}

  

# Mathemtaik

## Infos

- Martin Bicher

- http://atkmath.tuwien.ac.at

- Gruppenanmeldung im Tuwel

- [Skriptum](https://www.bookandpaper.store/item/Angleichungskurs_Mathematik_-_Akmath_PLU/72579098?back=2a1829ee3186e8d2a0df52c50a566e1c)

- [Anmeldung](https://tiss.tuwien.ac.at/course/educationDetails.xhtml?dswid=1792&dsrid=255&semester=2025W&courseNr=101A27) => Tuwel => Gruppeneinteilung => INF&WINF

- Keine Anwesenheitspflicht

- Kontakt [organisatorisch](akmath@asc.tuwien.ac.at), Martin Bicher [inhaltlich]()

  
  

### Inhalt

- Funktionen

- Vektoren

- Komplexe Zahlen

- Differenzial

- Integral

  
  

### Tests

- 60 Min

- Möbius

- Anmeldung für Prüfung im algemeinen Kurs

- Zwischentests und Abschlusstest mehrmals möglich

- Zwischentests jederzeit online

  
  

## Funktion

  

### Definition

Jede Funktion benötigt:

- D ... Definitionsmenge

- Z ... Zielmenge / W... Wertemenge/Wertebereich

- Vorschrift ... wie hängen die Elemente aus D mit Z zusammen

- jeder Element aus D braucht ein Element in Z, aber nicht umgekehrt

- $f:D \to W:x \mapsto f(x)=y$

  

### Begriffe

- wohldefiniert => eindeutige Zuweisung, jedes D hat ein Z

- injektiv => kein Element wird doppelt zugewiesen

- sujektivität => Jedes Element in Z hat eine zuweisung

- injetiv und sujektiv => 1 zu 1 Zuweisung

- bijektiv ... Umkehfunktion möglich bei 1 zu 1

- Quadranten:

1. Oben rechts

2. Oben links

3. unten links

4. unten rechts

- NICHT WEITER VEREINFACHEN, sind nur unnötige Fehler

- 1 Mediane ... Einheitsgerade ... f(x) = x

  
  

### Darstellung

![image](pref_math_funktion_definition.png)

  

- $f:\mathbb{R} \to \mathbb{R}:x \mapsto 0 ... f(x)=0 $

  

- $\mathbb{N}$ +, * => Mathemtatik bei 1, Informatik bei 0, falls nichts dabei steht

- $\mathbb{N}\setminus{\lbrace 0 \rbrace} : \lbrace 1,2,3,..\rbrace$

- $\mathbb{N}⁰:\lbrace 0, 1, 2, ...\rbrace $

  

- $\mathbb{Z}$ +, -, *

- $\mathbb{N}: \lbrace..., -2,-1-0,1,2,3,.. \rbrace $

  

- $\mathbb{Q}$ +, -, *, /

- $\mathbb{N}: \lbrace \frac{x}{y} x \in \mathbb{Z}, y \in N \setminus{\lbrace 0 \rbrace} \rbrace$

  
  

### Reelle Funktionen

- $f:DA \to B,A,B \subseteq \mathbb{R}$

  
  
  

### Relevante Informationen

- Graph

- Extremwerte

- Wendepunkte

- Nullstellen $\lbrace x:f(x)=0 \rbrace$

- Monotonieverhalten (steigend/fallend),

- streng monoton (= nur diese Richtung) steigend / fallend

- monoton (= kann auch Waagrecht gehen, aber nicht in andere Richtung) steigend / fallend

- Asymtoten

- Grenzverhalten

- Grad (bei Polynomfuktionen)

  

### Konstante Funktion

- $f:\mathbb{R} \to \mathbb{R}:x \mapsto 0 $ ... $f(x)=0$

- schwer umkehrbar, außer D muss eingeschränkt werden:

- $\lbrace 3 \rbrace \to \lbrace 0 \rbrace: x \mapsto 0 $

- 3 => 0 und umkehrfunktion 0 => 3

- immer monoton steigend/fallend, aber nicht streng

  

### Lineare Funktion

- $f:\mathbb{R} \to \mathbb{R}:x \mapsto kx+d $

- Beispiel: 2x+3

  

Wertetabelle:

|x | 2x+3

|----|---

| 0 | 3

| 1 | 2*1 + 3

|0.5 | 2*0.5 + 3

  

![image](linear_equation_definition.png)

  

Umkehrfunktion möglich außer k = 0

  

#### Nullstellen

  

$f(x)=x + 1$

  

$Ns:x:f(x)=0$

  

$x+1=0$

  

$x=-1$

  

$NS:\lbrace (1,0) \rbrace$

  

Nullstellen sind eine Menge, die aus Punkten besteht

  

### Quadratische Funktion

- $f:\mathbb{R} \to \mathbb{R}:x \mapsto a*x^2+b*x+c $

  

- Beispiel $g:\mathbb{R} \to \mathbb{R}: x \mapsto x^2$

  

|x | 2x+3

|---|---

| 0 | 0

| 1 | 1

| 2 | 4

| 3 | 9

| 0.5 | 0.25

  

![image](quadratic_function_definition.png)

  

- Quadratische Funktionen sind immer Parablen

- Scheitelpunkt ... Extremwert

- Verschieben:

- a ... Faktor => skaliert

- c ... verschiebt auf y-Achse

- bei $(x-a)^2$:

- verschiebt auf x-Achse Richtung a

  

=> alle möglichen Parabeln $\in A*(x+B)^2 + C $

- Scheitelpunkt $SP(-B, C)$

  

=> von der Form in die andere Form geben

  

- $A*(x+B)^2+C $

- $A*(x^2 + 2Bx + b^2) + C $

- $Ax^2+2ABx+AB^2+C$

- => $ a=A; b=2AB; c=AB^2 + C$

- => $ax^2+bx+c$

  

=> umgekehrt:

  

$A=a$

  

$B=\frac{b}{2a}$

  

$C=c-AB^2$

  

=> $SP(-\frac{b}{2a},c-\frac{b}{2})$

  

#### Nullstellen

  

Ns ... Nullstellen:

  

$g(x)=2*(x-2)^2-3$

  

$2*(x-2)^2-3 = 0$

  

$(x-2)^2=\frac{3}{2}$

  

$x_{1,2} = 2 \pm\sqrt{\frac{3}{2}}$

  

Allgemeine:da z.B.Umkehrfunktion

  

$x_{1,2} = -B \pm\sqrt{\frac{-C}{A}}$

  

$x_{1,2} = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$

  
  

#### Funktion aus Linearfaktoren schreiben

  

$ax^2 + bx + c = a * (x - {NS}_1) * (x - {NS}_2)$

  

- Wenn Wurzel bei großer Lösungsformel <0 ist:

- im reelen Bereich nicht möglich (komplex schon)

  
  
  

### Polynom Funktion

  
  

#### Nullstellen

  

$a_nx^n+a_{n-1}x^{n-1}+...+ a_1x+a_0 $

- ungerade haben immer mind. 1 Ns

  

$=a_n*(x-x_1)*(x-x_2)+...(x-x_n) $

- geht im reelen bereich nur, wenn ALLE NS reele Zahlen sind

- mit komplexen Zahlen geht es immer

- $=x^n+...+x_1*x_2*x_3*...=>x_1 * x_2 * ... = a_0$

- => alle NS multipliziert sind $a_0$

- => hilft bei ganzzahligen $a_0$ => alle Teiler von $a_0$ probieren

- Polynom mit $a^n$ => max. n NS

  

Beispiel:

$f(x)=x^3+x^2+x+1=0$

  

Taktik: ausprobieren, eine zu finden, dann die gefunde von den Linearfaktoren wegdividieren => ein Faktor weniger

  

| x |f(x)|

|--|--|

| 0 | 1 |

| 1 | 4 |

| -1 | 0 |

  

$fx^3+x^2+x+1=(x-(-1))*(x^2...)$

  

=> Polynomdivision

  

//\polylongdiv{x^3+x^2+x+1}{x+1}$

  

$=>x^2+1$

  

$=> x^2=-1 =>$ schaut schlecht aus mit reelen Zahlen

  
  
  

### Monom Funktion

$f(x)=x^n n \in \mathbb{N}$

  

- gehen immer durch (0,0) und (1,1)

- einzige Ns => (0, 0)

  

Beispiel:

$f:\mathbb{R} \to\mathbb{R}:x \mapsto x^2$

  

=> nicht umkehrbar, weder sujektiv noch injektiv

=> $f:\mathbb{R}^+ \to\mathbb{R}^+:x \mapsto x^2$

=> Umkehr: $f^{-1}:\mathbb{R}^+ \to\mathbb{R}^+:x \mapsto x^\frac12$

  

$f:\mathbb{R} \to\mathbb{R}:x \mapsto x^3$ => umkehrbar

  

ABER:

- man definiert generell nur für $\mathbb{R}^+$, da

- z.B.Umkehrfunktion $x^{\frac23} = x^{(\frac13)^2}$

- => Vorzeichen von x abhängig

  

Umkehrfunktion gespiegelt um

  
  

### Exponential Funktion

  

### Winkelfunktionen

$sin(x)^2+cos(x)^2=1$ ... trigonometrischer Pythagoras

$sin (x+k*2\pi) = sin(x) k \in \mathbb{G}$

$cos (x+k*2\pi) = cos(x) k \in \mathbb{G}$

$sin (x+\pi/2) = cos(x) $

$cos(x)=cos(-x)$ ... gerade Funktion (y Achse gespiegelt)

$sin(x)=-sin(-x)$ ... ungerade Funktion (punkt gespiegelt)

  
  

=> Formelsammlung Trigonometrie Wikipedia

  
  

## Vektoren

  

##begin{pmatrix} x & y & z \end{pmatrix}

$\mathbb{R}^2 = \lbrace (x,y): x,y \in \mathbb{R} \rbrace$

  

$v ... Vector => v^T =>$ transponiert (90° gedreht)

  

### Analytische Geometrie

  

Punkte ... A,B,C ..

Vektoren ... a,b,c .. keinen festen Platz im Raum

  

$A + \vec{a} = B$

$A-B = \vec{BA} = \vec{a} $

  

#### Geraden

_Alles für_ $\mathbb{R^2}$

$X ... (x,y)^T = \vec{a}$

  

- Parameterdarstellung ... $X=A+t\vec{a}$

- Normalvektordarstellung $\vec{n} * X = c ... c\in \mathbb{R}$ ... Skalarprodukt

- lineare Funktion kx+d

- ist am schlechtesten, da geraden die Parallel zur y Achse sind nicht dargestellt werden können

  
  

_Alles für_ $\mathbb{R^3}$

  

$X ... (x,y,z)^T = \vec{a}$

- Parameterdarstellung

- KEINE Normalvektordarstellung

  

Ebene:

- Parameterdarstellung $X=A+t\vec{a}+s*\vec{b}$

- Normalvektordarstellung $\vec{n} * X = c ... c\in \mathbb{R}$ ... Skalarprodukt

  
  

## Komplexe Zahlen

  

- $z=a+bi$

- a... Realteil

- b... Imaginärteil (ohne i !!!!)

- z... meiste verwendet um komplexe Zahlen darzustellen (statt x/a,b bei Reelen)

  
  

- $ z = a+bi

- => \overline{z} = a-bi$ ... konjugiert komplex

  
  
  

andere ergebnisse im möbius

  

Frage 6:

  

4*(x+7)^(2)+193 - (56*56)/16

  

4*(x+7)^(2)+193 - 56*56/16

  

Frage 8 arctan(5)-arctan(-1), warum stimmt das nicht

  

## Differenzieren/=Ableiten

  
  

### Extras:

$(f^{-1}(x))'=\frac{1}{f'(x)*f^{-1}(x)}$

- praktisch für tangens

  

### Kurvendiskussion

Beispiel:

- NS von $sin(x)$:

$\lbrace (k*\pi,0), k \in \mathbb{Z} \rbrace$