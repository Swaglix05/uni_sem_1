
Peanoaxiome:
1. "0" ist eine nat. Zahl
2. Jede nat. Zahl genau einen Nachfolger
3. "0" ist kein Nachfolger
4. Kein Nachfolger ist doppelt
5. Jede Eigenschaft, die "0" besitzt und sich von jeder nat. Zahl auf den Nachfolger überträgt, gilt für alle nat. Zahlen (Induktionsaxiom)

Induktionsanfang $P(x_0)$
Induktionsbehauptung $P(x+1)$
Induktionsvorraussetzung $P(x)$
Induktionsschritt $P(x)=>P(x+1)$

Kommutativgesetz $n circle t = t circle n$
Assoziativgesetz $(a circle b) circle c = a circle (b circle c)$
Distributivgesetz  $a * (b circle c) = a circle b * a circle c$
Existenz des neutralen Elements  $n circle e =n$

irrational: nicht durch einen Bruch von 2 ganzen Zahlen darstellbar

Dezimalentwicklung $63.5=6*10^1+3*10^0+5*10^(-1)$   endlich + unendlich(+periodisch)
Intervallschachtelung $sqrt(2) <=> I_0=[1,2], I_1=[1.4,1.5]$ 
Betrag von $RR |x|=max(x,-x)$
Betrag von $CC |a+b i|=sqrt(a^2+b^2)=r$
Argument von $CC "   " phi$
Wurzel von $CC "   " ^n sqrt(c)={["" ^n sqrt(r),(phi + 2 pi k)/n] | k in 0 ... n - 1}$

Fundamentalsatz der Algebra: $forall$ Polynom mit $P(z)=a_n z^n+...+a_0 "  " exists k_1...k_n: P(z)=a_n*(z-k_1)*(z-k_2),...(z-k_n) => k_j$ sind alles Nullstellen (und eindeutig bis auf Reihenfolge)
$b | a <=> exists c in ZZ: a = b*c$

$"ggT"(a,b)=d <=> d|a and d|b and (t|a and t|b => t|d)$, Euklid vorletzte Zeile "Rest"

Euklidischer Algorythmus $a=b*q+r, r in 0 ... b-1$
$PP ... "Primzahlen  " p in PP:= forall z in 1 ... p-1: "ggT"(z,p)=1$
Fundamentalsatz der Zahlentheorie: $forall n in NN: exists p_0 ... p_k in PP: n=p_0*...*p_n$
$v_p (a)=k "falls" p^k | a and not " " p^(k+1) | a$

Restklasse $a = a + ZZ m | m in ZZ$
muliplikativ inverse Restklasse: $a*n + b*m = 1$
Eulersche Phifunktion $phi(x)={a in NN^+| a<x, "ggT"(a,x)=1}$
Kleiner Satz von Fermat $"ggT"(a,x)=1 => a^(phi(x)) = 1 mod x$

Konjunktion "und" $and$
Disjunktion "oder" $or$
Implikation "wenn ... dann ..." $=>$
Äquivalent "gleich" $<=>$
Negation "nicht" $not$
Junktor  Die Symbole die man verwendet
gültig = Tautologie
semantisch äquivalent = mathematisch äquivalent
unerfüllbar = Kontradiktion

Quantor Wertigkeitsbereich, für den eine Variable gilt
Existentzquantor $exists$
Allquantor $forall$

direkter Beweis $a => b$
indirekter Beweis $not b => not a$ Kontraposition

Menge Zusammenfassung von wohl unterschiedenen Objekten
Betrag von Menge = Anzahl Elemente   $| a | <=> "#" a$
Mengen  $a=b <=> a subset.eq b and b subset.eq a$
aufzählende Darstellung $a={1,2,3}$
beschreibende Darstellung $a={x|P(x)}$
Multimenge (=Liste) element kann mehrmals vorkommen
Kardinalität = endlich => Größe, undendlich => abzählbar/überabzählbar

Vereinigung $union$
Durchschnitt ∩
Komplement $A subset.eq E and A"'" subset.eq E and A " ∩ " A"'" = {} and A union A"'" = E$
Mengendifferenz  A \ B
symmetrische Differenz (A \ B) $union$ (B \ A)
Potenzmenge P({1,2}) = Menge aller Teilmengen {{},{1},{2},{1,2}}
Betrag einer Potenzmenge $|P(a)|=2^(|a|)$
geordnetes Paar $(a,b)=(c,d) <=> a=c and b=d$
ungeordnetes Paar $(a,b)=(c,d) <=> (a=c and b=d) or (a=d and b=c)$
kartesische Produkt $A times B={(a,b) | a in A and b in B}$
Relation $r subset.eq A times B$
binäre Relation $r subset.eq A times A$
Relationdarstellung Kartesisch S. 38
Relationdarstellung Pfeildiagramm S. 38
Relationdarstellung Graph (bei binären) S. 38

Äquivalenzrelation
- Reflexiv $forall a in A: a R a$
- Symmetrisch$forall a,b in A: a R b => b R a$
- Transitiv $forall a,b,c in A: a R b and b R c => a R c$
Identische Relation $forall a,b in A: a R b <=> a=b$
Allrelation Jedes Element mit allen
Partion von A: Zerlegung in disjunkte nichtleere Mengen
Äquivalenzklasse $K(a)={x |x in A and x R a}$

Halbordnung reflexiv, antisymmetrisch, transitiv
Antisymmetrisch $forall a,b in A: a R b and b R a => a=b$
Totalordnung Halbordnung+ $forall a,b in A: a R b or b R a$
Hassediagramm (für Halbordnungen) S. 42

Maximale Kette einer Halbordnung: Wenn man K um ein Element erweitert, ist K' KEINE Totalordnung mehr bezüglich R
Hausdorfsche Maximalitätsprinzip: Jede Halbordnung besitzt eine maximale Kette (auch unendliche)
Wohlordnung: Totalordnung + jede Teilmenge besitzt Minimum

injektiv 1 zu 0/1 Zuweisung
surjektiv 1 zu 1+ Zuweisung
bijektiv 1 zu 1 Zuweisung
indentische Funktion $id_A(a)=a$
Umkehrfunktion $f^-1: B -> A$ (bei bijektiv) $f^-1 circle f=id_A and f circle f^-1=id_B$

Summenregel $A " ∩ " B = {} => |A " ∩ " B|=|A|+|B|$
Produktregel $|A times B| = |A| * |B|$
Gleichheitsregel  $exists f: A->B   => |A| = |B|$

Fakultät $n! = Pi^(n)_(i=1) i$
Binomialkoeffizient $binom(n,k) = n!/(k!*(n-k)!) , 0<=k<=n$
Anordnung ohne Einschränkung/Variation mit Wiederholung $A^k$
Anordnung vershiedener Elemente/Variation ohne Wiederholung $n!/((n-k)!)$
Permutation einer Menge   $n!$
Permutation einer Multimenge $n!/(k_1!*k_2!*...k_j!), k_j$ autreten eines Elements
Auswahl einer Teilmenge/Kombination ohne Wiederholung $binom(n,k)$
Auswahl einer Teilmultimenge/Kombination mit Wiederholung $binom(n+k-1,k)$

Bellzahlen: ANzahl möglicher Partionen n elemntiger Menge $B_n+1 = Sigma^n_(k=0) binom(n,k) B_k$
Schubfachprinzip n Ele Menge in k Parti mind. 1 Menge mind $ceil(n/k)$ Elem haben

Binom Regel: $binom(n+1,k+1)=binom(n,k)+binom(n,k + 1)$
Binomischer Lehrsatz: $sum_(k=1)^n binom(n,k)x^(n-k)y^k=(x+y)^n$

IE Prinzip: $|A union B| = |A|+|B|-|A " ∩ " B|$
fixpunktfreie Permutation Kein Element verweist auf sich selbst


Graph G: Menge an Knoten V = V(G) und Kanten E = E(G)
$V=alpha_0=|V(G)|$...Anzahl der Knoten
$E=alpha_1=|E(G)|$...Anzahl der Kanten
Kante gerichtet (=geordnet) $e=(v_1, v_2)$  ... v1 Anfangs-, v2 Endknoten
ungerichtet (=ungeordnet) $e={v_1, v_2}$
falls alle Kanten gerichtet/ungerichtet => gerichteter/ungerichteter Graph

Schlinge: Kante auf sich selbst $e= (v_i,v_i)<=>{v_i,v_i}={v_i}=v_i v_i$
eine ungerichtete Schlinge als 2 gerichtete sehen (in beide Richtungen eine)
Knoten adjazent wenn durch Kante "verbunden"
Mehrfachkanten=mehr als eine Verbindung zwischen 2 Knoten
schlicht/einfacher Graph: keine Schlinge oder Mehrfachkanten
azyklisch keine Kreise positiver Länge
Azyklische Graphen besitzten mind. einen Knoten $d^+(v_1)=0$ und $d^-(v_2)=0$

Wald  schlichter ungerichteter azyklischer Graph
Wald V=E+k    k...Anzahl der Zusammenhangskomponenten
Baum: Zusammenhangskomponent einer Waldes

Eulersche Linie - Enthält jede Kante genau 1 Mal, geschlossen/offen
Hamiltonsche Linien - Enthält jeden Knoten genau 1 Mal, geschlossen/offen
Planare Graphen -  kreuzungsfrei in $RR^2$ darstellbar
Eulersche Polyederformel V-E+G=2 G... Gebiete (mit außerhalb)
Nicht planar, falls K5 oder K3,3 enthalten ist
chromatische Zahl $""_Chi (G)$ Anzahl der Fraben
Planare Graphen $""_Chi (g)<=4$

Netzwerk - $forall e in E: exists w(e) in RR$ ... w(e) Gewichtung
spannender Baum - $V"'"=V, E"'" subset.eq E$
Gerürt - Wald zu spannendem Wald
Kruskal - maximal und minimal spannende Böume
Dijkstra - immer von niedrigstem zum Nächsten ...
Entfernungsbaum - Weg von Start zu jedem Knoten


binäre algebraische Struktur = Gruppoid = abgeschlossene Operation
Assoz (a\*b)\*c=a\*(b\*c) => halbgruppe
neutrales Ele => Monoid
jedes Ele genau 1 invers => Gruppe
kommutativ a\*b=b\*a   => abelsche/kommutative XXX
symmetrische Gruppe = Gruppe an Funktionen/Abbildungen

Untergruppe - nichtleere Teilmenge, abgeschlossen
triviale Untergruppen - U={e}, U=G
Ordnung - Anzahl der Elemente in $G - |G|$
Index - Anzahl der Rechts/Linksnebenklassen $|G:U|=|G|div|U|$
Satz von Lagrange $(|G| div |U|) in ZZ$
Kleiner Satz von Fermat $forall a in G: a^(|G|)=e$
Normalteiler (U=Untergruppe) - $forall a in G: a circle U=U circle a$
Faktorgruppe $(G"/"N,circle) <=> (a circle N) circle (b circle N)=(a circle b) circle N$

Gruppenhomomorphismus $phi: G->H$ falls $phi(a circle b) = phi(a) * phi(b)$
Isomporphismus $phi:G->H and exists phi^(-1):H->G$ (=bijektiv)
Kern $ker(phi)={a in G | phi(a)=e_H}$
Bild $phi(G)={b in H | exists (a) in G: phi(a)=b}$
Homomorphiesatz $G "/" "ker"(phi) tilde.equiv phi(G)$ ... isomorph

Zyklendarstellung einer Bijektiven Funktion Bsp. (1,5,3)(2,4)
Signum $Pi^(|Z|)_(z in Z) (-1)^(|z|-1)$ ... Z Menge der Zyklen

Ring (R,+,\*) (=special algebraische Struktur)
- (R,+) kommutative Gruppe
- (R,\*) Halbgrupee
- Distributivgesetzte $a*(b+c)=a*b+a*c$ und umgekehrt( "\*" muss nicht kommutativ sein)
Ring und neutral - "Ring mit 1 Element"
Ring und komm - "kommutativer Ring"
Polynomring ($RR[x],+,*$)
Ring der formalen Potenzreiehn ($RR[[x]],+,dot$)

Integritätsring <=> kokmm Ring mit Einsele OHNE Nullteiler
Körper <=> komm Ring mit Einsele und  $forall k in K without {0}: exists k^-1$
Jeder Körper ein Integritätsring, Inverses => kann kein Nullteiler sein
Jeder endliche Integritätsring => auch Körper

Verband $(M,circle, *)$
- $(M, circle)$ komm Halbgruppe
- $(M,*)$ komm Halbgruppe
- Verschmelzungsgesetzte
	- $a=a circle (a * b)$
	- $a=a * (a circle b)$

$a<=b <=> a=a circle b$ ... dadurch als Halbordnung definiert,
Infimum - $"inf"(a,b)=a circle b$ 
Supremum - $sup(a,b)=a*b$

distributiver Verband <=> Verband + Distributivgesetze
- $a circle (b * c) = (a circle b)*(a circle c)$
- $a*(b circle c)=(a*b) circle (a*c)$
Komplement $exists B"'" in P(A) without B: B circle B"'"= emptyset and B * B"'"=A$
Boolsche Algebra, falls Monoide (1 element bzgl $circle$,    0 bzgl. $*$) + $forall a in M:exists a"'"$


$RR^n => RR ... "Skalarkörper", x in RR$ ... Skalare
Parallelogrammregel - Vektor addieren
Vektorraum - (V,+,K)
- (V,+) abelsche Gruppe
- K Körper
- Distributivgesetze
- Assoz
- neutral ($1*x=x$)

erste Mediane ... y=x
