S.62
![[Pasted image 20251106081746.png]]
ADM sind Graphen immer endlich (sowohl V als auch E)
![[Pasted image 20251106081757.png]]

![[Pasted image 20251106081908.png]]
![[Pasted image 20251106082041.png]]
nachbar und berührt (immer das rote)


ungerichteter Graph:
$G=(v,E)$
$e=\{u,v\} \iff e=u,v$

gerichteter Graph:
$G=(V,E)$
$e=(u,v) \iff    u\implies v$

![[Pasted image 20251106082418.png]]
Gamma = $\Gamma$

$d(v)=\left| \{e=vu,e \in E \right\}|$

bei ungerichteten: 
- mehrfach-verbindungen zählen doppelt
- schlingen zählen doppelt

![[Pasted image 20251106083238.png]]
Handschlag-lemma

links ungerichtet  bzw. recht gerichtet
Verhältnis zwischen Graden und Edges

beweis:
jede kante hat 2 endknoten (entweder zwei gleiche oder 2 unterschiedliche)
 damit jede kante zählt 2 pro Grad 
![[Pasted image 20251106083836.png]]

bei gerichtet genau das gleiche, nur pro kante 1 zu hin, 1 zu weggrad, damit immer gleich

![[Pasted image 20251106084340.png]]
![[Pasted image 20251106084435.png]]

![[Pasted image 20251106084631.png]]
Endknoten von einem ist anfang vom nächsten (=nicht geschlossene Kette)

![[Pasted image 20251106084819.png]]
Kante 4 und 7 sind die gleiche, deshalb Kantenzug

bei gerichteten Graphen ist ein Weg => Bahn

offene Kantefolge, wenn Anfang und Ende unterschieldich sind
	-> sonst geschlossen
	circle und cycle im englischen
![[Pasted image 20251106085124.png]]


![[Pasted image 20251106085525.png]]
![[Pasted image 20251106085859.png]]

zweiter Satz
![[Pasted image 20251106090108.png]]
Der Kreis muss nicht durch den Anfang oder das Ende gehen, aber es gibt einen

![[Pasted image 20251106090200.png]]
gilt nur für schlichte Graphen

![[Pasted image 20251106090929.png]]
beide Richtungen bei gerichtetem

![[Pasted image 20251106091638.png]]

$A^k\implies$ Kantenfolge der Länge k zwischenElementen
C ist auch ein Matrix

Beispiel:
![[Pasted image 20251106092652.png]]


![[Pasted image 20251106092953.png]]

![[Pasted image 20251106093023.png]]
"Schatten eines Gerichteten Graphs"= Richtung weglassen => ungerichteter Graph


![[Pasted image 20251106093226.png]]
Teilgraphen die Zusammenhängen, zu denen man nichts dazugeben kann


![[Pasted image 20251106093640.png]]
in dem Fall Wald mit 3 Bäumen

![[Pasted image 20251106093835.png]]
Abstand=Distanz

![[Pasted image 20251106094102.png]]

![[Pasted image 20251107081953.png]]

![[Pasted image 20251107082505.png]]
Verhältnis Kanten und Knoten bei Bäumen: $|V|=|E|+1$
bei Forests/Wälder:  $|V|=|E|+ K$,  K... Anzahl aller Zusammenhangskomponenten (Bäume)


bei azyklischen gerichteten Graphen: 
- kein Zyklus positiver Länge


![[Pasted image 20251107085455.png]]
S. 70
![[Pasted image 20251107085845.png]]

![[Pasted image 20251111082647.png]]

![[Pasted image 20251111082529.png]]
danach entfernt man die Linie, falls man noch nicht durch alle Kanten gegangen ist
und man entfernt insgesamt eine gerade Anzahl an Kanten, da man jeden Knoten pro betreten auch einmal verlässt

![[Pasted image 20251111082449.png]]
![[Pasted image 20251111082631.png]]
![[Pasted image 20251111082757.png]]


![[Pasted image 20251111083441.png]]
NP-hartes Problem, nicht lösbar allg.

# Planare Graphen
![[Pasted image 20251111084755.png]]
S. 72 
kreuzungsfrei in der Ebene darstellbar

isomorph zu einem Ebenengraph
 $<=>$ bijektive Abbildung mit Beachtungen der Adjazenzen

$alpha_2(G)=4$ beim rechten Beispiel (die Ebene außerhalb zählt dazu)


Eulersche Polyederformel angewendet auf S. 73

![[Pasted image 20251111090156.png]]
planarer Graph mit genau K zusammenhängenden Komponenten

Beweis:
![[Pasted image 20251111090846.png]]
falls er keinen Kreis hat oben (einen Endknoten)

falls er einen Kreis hat (keinen Endknoten):
![[Pasted image 20251111091250.png]]
eine Kante im Kreis rausnehmen, dann hat man eine Kante aber auch ein Gebiet weniger => wieder zusammenhängend => wieder Fall 1

## Stereographische Projektion

nicht im Buch
![[Pasted image 20251111091948.png]]

![[Pasted image 20251111092638.png]]
Eulersche Polyederformel

![[Pasted image 20251111093128.png]]

![[Pasted image 20251111093531.png]]
K5 ist nicht planar darstellbar, da nach der eulerschen Polyederformel max. 9 Kanten vorkommen dürften
## Satz von Kuratowski
S. 73
K5 und K3,3. Das sind die böse Graphen
### Unterteilungsgraph
In Kanten weitere Knoten dazwischen machen
Wenn ein Teilgraph bereits nicht planar ist, ist der ganze Graph nicht planar

### Vierfarbensatz
S. 74 
originaler Graph => planaren Graph, jedes Gebiet wird ein Knoten, jede Verbindung zwischen zwei Gebieten wird eine Kante

chromatische Zahl eines Baumes: 2


### kantendisjunkte Wege
Satz von Menger

![[Pasted image 20251113082336.png]]
anzahl an kantendisjunkten Wege = min. aller möglichen Schnitte
![[Pasted image 20251113082438.png]]

### Netzwerke

![[Pasted image 20251113082743.png]]
Netzwerke haben in der Regel einfache Kanten, mehrfache Kanten machen meistens keinen Sinn

![[Pasted image 20251113082940.png]]


![[Pasted image 20251113083527.png]]
![[Pasted image 20251113083503.png]]
gerüst=spannender Wald



![[Pasted image 20251113083753.png]]
Beispiel: falls links der Baum, dann ist mitte spannender Baum aber rechts nicht, da nicht alle Zusammenhangskomponenten vorkommen

# Dijkstra beweis wird geskipped

![[Pasted image 20251113085719.png]]

|W| ... Länge des Wegs
$W: E -> R_0^+$

![[Pasted image 20251113092043.png]]





