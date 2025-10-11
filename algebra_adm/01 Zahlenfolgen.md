$\mathbb{N} = \{0,0',0'',...\}$

Quantoren:
$\forall$ ... für alle, Allquantor
$\exists$ ... existiert, Existenzquantor

### Peano Axiome

P1: 0 ist nat. Zahl
P2. Jede nat. Zahl besitzt genau einen Nachfolger $n'$
P3: 0 tritt nicht als Nachfolger auf
- sonst kann es zu loops kommen
P4: Verscheidene nat. Zahlen besitzen versch Nachfolger ( $\forall n,m \in \mathbb{N}:   n \neq m \Rightarrow n'\neq m'$ )
P5: Alle Eigenschaften, die 0 besitzt und sich von jeder nat. Zahl n auf den Nachfolger überträgt haben bereits allen nat. Zahlen.
- schließt alle anderen Zahlen aus, zB 
	- $0,1,2,3,4,... \in \mathbb{N}$, 
	- aber $a\to b\to c\to a$ dadurch ausgeschlossen (externe Zahlen die nicht auf der "Hauptkette")
- Induktionsaxiom


### Beweismethode: "Vollständige Induktion"

Bsp. Summenformel
$1+3+5+7+...+(2x-1) =n^2$
$P(n): \sum\limits_{k=1}^n{2k-1} = n^{2}$  ... z.z. (zu zeigen): $\forall n \in \mathbb{N}: P(n)$
$(P(0) \cap \forall n \in \mathbb{N}: P(n)\implies P(n+1))\implies\forall n \in \mathbb{N}:P(n)$
- wenn es für 0 gilt, und P(n) P(n+1) impliziert, gilt es für alle n
Begriffe:
- $P(n): \sum\limits_{k=1}^n{2k-1} = n^{2}$  ... Induktionsvorraussetzung
- $\forall n \in \mathbb{N}: P(n)$ ... Induktionsbehauptung
- P(0) ... Induktionsanfang
- $\forall n \in \mathbb{N}: P(n)\implies P(n+1)$ ... Induktionsschritt

Anfang und Induktionsschritt jeweils beweisen
- Induktionsanfang: 
	$\sum\limits_{k=1}^0{2k-1}=0   ;\dots 0^{2}=0$;        w. A
- Induktionsschritt: 
	$\sum\limits_{k=1}^n{2k-1};\ \ \ n^{2}$
	
	$\sum\limits_{k=1}^{n+1}{2k-1}; \ \ \ (n+1)^{2}$  
	$(2n+1)+\sum\limits_{k=1}^{n}{2k-1}$
	Induktionsvermutung anwenden:
	$(2n+1)+n^2 = (n+1)^2$           w.A 


Bsp. Verschieben des Induktionsanfangs:

Ungleichung:
$(n+1)*2^n\leq 3^n$

| n   | P(n)   |     |
| --- | ------ | --- |
| 0   | 1<=1   | w   |
| 1   | 4<=3   | f   |
| 2   | 12<=9  | f   |
| 3   | 32<=27 | f   |
| 4   | 80<=81 | w   |
Vermutung: $\forall\ n\geq{4}:P(n)$

$(P(n_{0}) \cap (\forall n\geq n_{0}:P(n)\implies P(n+1)))\implies\forall n\geq n_{0}:P(n)$
Induktionsanfang: $P(n_{0})$
Induktionsschritt:
- I.V: $(n+1)*2^n\leq{3}^n$
- I.B. $(n+2*2^{n+1}\leq{3}^{n+1})$ ... zu zeigen

$3^{n+1}=3*3^n$
I.V. anwenden
$3*(n+1)*2^n$          / 3 auf 2+1 aufteilen
$=2*(n+1)*2^n+(n+1)*2^n$ 
$=(n+1)*2^{n+1}+2*2^n\leq3$      ... linke hälfte gleich wie oben I.B.

$\forall\ \mathbb{N} \setminus \{1,2,3\}:P(n)$

Vollst. Induktion: Grundlage von rekursiven Dev.!
$n \in \mathbb{N}: x^n$
$x^0:=1$
rek. Def $x^{n+1}:=x*x^n, \ n\geq 0$

rek Def. $n!:= {1,n=0\choose n*n(n-1)!, n\geq 1}$

Rekursiv def. Folge:

Bsp. Tower von Hanoi:
$a_{n}, n\geq_{0}=(a_{0},a_{1},a_{2},\dots)$
$a_{n}\dots$ min. Anzahl an Zügen, um Turm mit n Schreiben zulässig von A nach B zu bewegen

$a_{0}=0,a_{1}=1,a_{2}=3$
$a_{n}=2*a_{n-1}+1; n\geq {1}$, ... ist wohldefiniert
$(a_{n})_{n\geq_{0}}=(0,1,3,7,15,31,63,127,\dots)$
Verm.: $P(n): a_{n}=2^n-1$
Vollständige Induktion:
$(P(0)\cap P(n)\implies P(n+1))\implies\forall\ n \in \mathbb{N}: P(n)$
- I.A.  P(0)
- I.S.: $P(n)\implies P(n+1)$
- I.V: P(n)
- I.B.: P(n+1)

bei Ind. auf alle vorangeg. El. ????übergreifen:

Bsp. Binärbäume:
![[Pasted image 20251007092812.png]]

Rund: internte Knoten (2 "Kinder")
Eckig externe Knoten/Blatt (0 "Kinder")

I(S): 5
E(S): 6

P(n): Jeder Binärbaum mit n int. Knoten besitzt n+1 ext. Knoten


I.A.: 
- P(0): 
  - I(0):0
  - E(0):1
  - =>w.A

t mit I(t)=n+1
![[Pasted image 20251007093337.png]]

$I(t_{1})=K$
$I(t_{2})=n-K-1$
$0\leq K\leq n$

I.S.: $P(0)\cap P(1) \cap P(2) \cap \dots \cap P(n)\implies P(n+1)$
=> $P(0) \cap (\forall n \in \mathbb{N}: ((\forall K\leq n:P(k))\implies P(n+1)))\implies \forall n \in \mathbb{N}:P(n)$

I.B.:Jeder interne Baum mit n+1 internent Knoten besitzt n+2 externe 
I.S.: $\forall K\leq n:P(k)$      Knoten
I.V: jeder Binärbaum mit k<=n internen Knoten gilt E(t) = I(t)+1

$I(t_{1})=k$
$I(t_{2})=n-k$
$I(t)=1+I(t_{1}+I(t_{2}))$
$=1+k+n-k=n+1$

$E(t)=E(t_{1})+E(t_{2})$
I.V. anwenden
$=k+1+n-k+1$
$=n+2$

andere Möglichkeit:

1 Externe Knoten mit internem Ersetzten
=>$1*E => 2*E+1*I$



#### Beweise
 Induktionsbeweis S. 2
 direkter indirekter Beweise S. 30
Kontraposition: $\neg {} a \implies \neg b$

Ordnung der Zahlen

$\mathbb{N}=\{ 0, 0', 0'',\dots\}$
$m<n => m$ kommt in Liste vor n 

Addition S.4
Multiplikation S. 4
rekursive Definition

Gesetze S.5
Kommutativ, Assoziativ, Distributiv, Existenz eines neutralen Elements

Subtraktion Division Probleme S.5

### Ganze Zahlen

S. 5+6

Nachteil $\mathbb{Z}$: kein Induktionsanfang mehr / keine Kette mehr

Rationale Zahlen
 S. 5 +7
in Q add, sub, mult, div

Nachteil $\mathbb{Q}$: keinen Nachfolger, unendlich viel dazwischen

S. 7
$2*m^2 \implies m \dots gerate$ warum??
#### Kontraposition
$m \nmid 2 \implies 2 \nmid m^2$
$m=2*j+1$
$m^2=4j^2+4j+1$ ... Division mit Rest

Division mit Rest:
- n,m in Z, m>0
- n=m*q+r$, 0<=r<m$

$2 \mid m d.h. \exists k \in \mathbb{N}: m=2k$

$2 \mid n \implies n\ gerade$

=> beides gerade=> erfüllt nicht anfangsbedinung => wiederspruch => sqrt(2) ist nicht rational=>irrational


jede Reele Zahl kann mit ihrem Ganzteil und Bruchteil dargestellt werden
floor ...  comma weglassen
{} ... bruchteil


### Quadratisch ergänzen
$x^2+px+q=0$
$(x+\frac{p}{2})^2-(\frac{p}{2})^2+q$
$\implies x+\frac{p}{2}=\sqrt{(\frac{p}{2})^2-q  }$
$\implies x_{1,2}=-\frac{p}{2}\pm\sqrt{(\frac{p}{2})^2-q  }$

### Komplexe Zahlen S. 10


kartesische Darstellung:
z=a+b\*i
