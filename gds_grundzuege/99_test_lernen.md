# Digialschaltungen
"Grundgatter"/Grundoperationen AND OR NOT
## physikalische Systeme

## Gatter
![[Pasted image 20260116111726.png]]
![[Pasted image 20260116111749.png]]
![[Pasted image 20260116111907.png]]
![[Pasted image 20260116112239.png]]
![[Pasted image 20260116112254.png]]
## Multiplexer (MUX)
4 zu 1 Multi
![[Pasted image 20260116112444.png]]

DEMUX 
![[Pasted image 20260116112522.png]]

Volladdierer
![[Pasted image 20260116114825.png]]
![[Pasted image 20260116114942.png]]

ALU
![[Pasted image 20260116115600.png]]

# Prädikatenlogik

Inferenz ... A,B |=C   , so ähnlich wie =>, aber auf einer Ebene "darüber"

F . . . Menge der Funktionssymbole; besitzen Stelligkeit (Arität) 
f /n ∈ F . . . f ist ein n-stelliges Funktionssymbol. (f benötigt n Argumente.) 
f /0 . . . nullstelliges Funktionssymbol, Konstantensymbol 

P . . . Menge der Prädikatensymbole; besitzen Stelligkeit (Arität)
P/n ∈ P . . . P ist ein n-stelliges Prädikatensymbol. (P benötigt n Argumente.) 
P/0 . . . nullstelliges Prädikatensymbol, entspricht Aussagenvariable 

V = {x, y, z, x0, x1, . . . } . . . Individuenvariablensymbole

T... Termstprache: Die Menge T (F, V), der Terme über F und V ist die kleinste Menge, für die gilt: (t1) V ⊆ T Individuenvariablen sind Terme. 
(t2) f ∈ T , falls f /0 ∈ F. Konstantensymbole sind Terme. 
(t3) f (t1, . . . ,tn) ∈ T , falls f /n ∈ F und t1, . . . ,tn ∈ T . Funktionssymbole mit der passenden Zahl an Termargumenten sind Terme. 
Notation: 
- Pre-/Postfixnotation für manche unären (n = 1) Funktionssymbole 
- Infixnotation für manche binären (n = 2) Funktionssymbole 
- Klammerneinsparungen durch Prioritäten
$=>(and(A, B), C) "ist in Infixnotation" (A and B) => C$
$and(A, =>(B, C)) "ist in Infixnotation" A and (B => C)$

Interpretation Eine Interpretation I über einem Wertebereich U ordnet jedem Funktionssymbol aus F eine Funktion wie folgt zu: 
$I(f ) in U "für" f "/"0 in F$
$I(f ): U^n → U "für" f "/" n in F, n > 0$

σ : V → U . . . Wertebelegung für die Variablensymbole 
Der Wert eines Terms in einer Interpretation I mit Variablenbelegung σ wird festgelegt durch die Funktion $"val"_(I,σ)$, definiert als: 
(v1) $"val"_(I,σ)(v) = σ(v) "für" v ∈ V$ 
(v2) $"val"_(I,σ)(f ) = I(f ) "für" f "/"0 ∈ F$
(v3) $"val"_(I,σ)(f (t_1, . . . ,t_n)) = I(f )("val"_(I,σ)(t_1), . . . , "val"_(I,σ)(t_n)) "für" f "/" n ∈ F, n > 0$

![[Pasted image 20260116150219.png]]
S. 15 Prädikatenlogik

Eine Interpretation I über einem Wertebereich U ordnet jedem Symbol der Signatur (F,P) eine Funktion bzw. Relation wie folgt zu: 
$$I(f ) in U "für" f "/"0 in F \
I(f ): U n → U "für" f "/"n in F, n > 0 \
I(P) ∈ {0, 1} "für" P"/"0 in P \
 I(P) ⊆ U^n "für" P"/"n in P, n > 0 \
I(P): U n → {0, 1} ("alternative Sichtweise")$$

Der Wert einer Formel in einer Interpretation I mit Variablenbelegung σ wird festgelegt durch die Funktion $"val"_(I,sigma)$, definiert als: 
(v1) $"val"_(I,sigma)(P) = I(P) "für" P/0 ∈ P;$
(v2) $"val"_(I,sigma)(P(t_1, . . . ,t_n)) = I(P)("val"_(I,sigma)(t_1), . . . , "val"_(I,sigma)(t_n)) "für" P/n ∈ P$
(v3) $"val"_(I,sigma)(⊤) = 1 "und" "val"_(I,sigma)(⊥) = 0$ 
(v4) $"val"_(I,sigma)(¬F) = not "val"_(I,sigma)(F)$ 
(v5) $"val"_(I,sigma)( (F ∗ G) ) = "val"_(I,sigma)(F) ⊛ "val"_(I,sigma)(G), "wobei ⊛ die logische Funktion zum Operator ∗ ist"$
(v6) $"val"_(I,sigma)( ∀x F ) = ( 1 "falls" "val"_(I, sigma)′(F) = 1 forall sigma ′ ∼^x sigma "    " 0 "sonst"$
(v7) $"val"_(I,sigma)( ∃x F ) = ( 1 "falls" "val"_(I,sigma)′(F) = 1 "für mind. ein" sigma^′ ∼^x sigma "   " 0 "sonst"$

σ x∼ σ ′ . . . σ(v) = σ ′ (v) für alle v ∈ V mit v ̸= x 
(σ und σ ′ sind identisch, nur σ(x) und σ ′ (x) können verschieden sein.)

erfüllbar: $"val"_(I, sigma)(F) = 1$ für mind. 1 I und $sigma$, (=I,$sigma$ Modell von F)
wiederlegbar: $"val"_(I, sigma)(F) = 0$ für mind. 1 I und $sigma$, (=I,$sigma$ Gegenmodell von F)
unerfüllbar: $"val"_(I, sigma)(F) = 0$ für alle I und $sigma$
gültig: $"val"_(I, sigma)(F) = 1$ für alle I und $sigma$ (F ist Tautologie)


F1, . . . , Fn |= I,σ G  ... gilt für alle I und σ.

F1, . . . , Fn |= G genau dann, wenn (F1 ∧ · · · ∧ Fn) ⇒ G gültig.

# Automaten
Kennzeichen:
- endliche Menge von Zuständen 
- Übergänge zwischen Zuständen

- Eingaben, die die Übergänge steuern
- Ausgaben oder Aktionen, die in den Zuständen oder während der Übergänge getätigt werden

- Anfangszustand 
- Endzustände (optional) 

- deterministisch: Der momentane Zustand und die nächste Eingabe bestimmen eindeutig den Folgezustand. 
- nichtdeterministisch: Es gibt Zustände, die bei manchen Eingaben mehrere mögliche Folgezustände besitzen.

Begriffe:
- $Sigma$ ... endliche, nicht-leere Menge atomarer Symbole
- Wort über Σ: (endliche) Folge von Zeichen aus $Sigma$
- ⟨$Sigma$ ∗ , ·, ε⟩ bildet ein Monoid:
  - Assoz und $epsilon$=neutral
- Formale Sprache über $Sigma$: beliebige Teilmenge von $Sigma^*$ 
## Endliche Automaten
### DEA
5-Tupel A = ⟨Q, $Sigma$, $delta$, $q_0$, F⟩
- Q ... endliche Menge der Zustände
- $Sigma$ ... Eingabealphabet
- $delta$: Q x $Sigma -> Q$ ... Übergangsfunktion
- $q_0 in Q$ ... Anfangszustand
- $F subset.eq Q$ ... Menge der Endzustände
- $delta^*: Q times Sigma^* -> Q, q in Q, s in Sigma, w in Sigma^*$
	- $delta^*(q,epsilon)=q$
	- $delta^*(q,s w)=delta^*(delta(q,s),w)$
- $L(A) = {w in Sigma^∗ | delta^∗ (q_0,w) in F }$
### NEA
5-Tupel A = ⟨Q, $Sigma$, $delta$, $q_0$, F⟩
- $delta subset.eq Q times (Sigma or epsilon) times Q$ ... Übergangsfunktion
- $delta^*: subset.eq Q times (Sigma or epsilon) times Q$
	- $delta^*(q,epsilon,q) in delta^*$
	- $(q_1,w,q_2) in delta^* and (q_2,s,q_3) in delta => (q_1,w s,q_3) in delta^*$
- $L(A) = {w in Sigma * | (q_0,w, q_f ) in delta^* "für ein" q_f in F }$

### Determinisierung
![[Pasted image 20260117144226.png]]

### Transducer
Ein und Ausgabe
Ausgabe von Zustand und Eingabe
NDT
Mehrere Startzustände und Endzustände
A = ⟨Q, Σ, Γ, δ, I, F⟩
- Γ ... Ausgabealphabet
- $delta$ ... ⊆ Q × (Σ ∪ {ε}) × (Γ ∪ {ε}) × Q
- $δ^∗ ⊆ Q × Σ^∗ × Γ^∗ × Q$

### Mealy
- deterministisch
- Ausgabe
- EIN Anfangszustand
- ALLES sind endzustände
A = ⟨Q, Σ, Γ, δ, $mu$, q0⟩
- $mu$ : Q × Σ → Γ
- γ ∗ (q,sw) = γ(q,s) · γ ∗ (δ(q,s),w)

### Moore
- deterministisch
- Ausgabe von Zustand abhängig
- Ein Anfangszustand
- Alles sind endzustände
A = ⟨Q, Σ, Γ, δ, γ, q0⟩
- γ : Q → Γ
- γ∗ (q,sw) = γ(q) · γ∗(δ(q,s),w)

![[Pasted image 20260118161702.png]]

### Büchi
sowohl deterministisch als auch nichtdeterministisch
A = ⟨Q, Σ, δ, q0, F⟩
gleich wie DEA und NEA

akzeptierte Sprache=unendlich oft wird Endzustand erreicht
NDT kann mehrere Startzustände haben



# Reguläre Sprachen

# Kontextfreie Grammatiken

# Petri-Netze


# ALT Test 2023 w

## Aufgabe A1: Aussagenlogik
![[Pasted image 20260119161414.png]]
rot ... Rot
orange ... Orange
gelb ... Gelb
grün ... Grün
cyan ... Cyan
blau ... Blau
violett ... Violett

$F_1:="rot" or "orange" or "gelb" or "grün" or "cyan" or "blau" or "violett"$
$F_2:= not "gelb" and not "cyan"$
$F_3:="violett" and (("rot" and "orange") or ("rot" and "grün") ... or ("cyan" and "blau"))$
$F_4:=not ("grün" and "rot")$
$F_5:="grün" => ("blau" and "orange")   = not "grün" or  ("blau" and "orange")$
$F=F_1 and F_2 and F_3 and F_4 and F_5$
![[Pasted image 20260119162347.png]]
nach F_2 kein gelb oder cyan
nach F_5 wenn grün => blau und orange => max. 3 farben => kein violett
violett immer dabei wegen F_3

| gelb | cyan | grün | violett | rot | orange | blau | F_1 | F_2 | F_3 | F_4 | F_5 | F   |
| ---- | ---- | ---- | ------- | --- | ------ | ---- | --- | --- | --- | --- | --- | --- |
| 1    | X    | X    | X       | X   | X      | X    | 1   | 0   |     |     |     | 0   |
| X    | 1    | X    | X       | X   | X      | X    | 1   | 0   |     |     |     | 0   |
| 0    | 0    | 1    | X       | X   | 1      | 1    | ... | 1   | 0   |     |     | 0   |
|      |      | 1    | X       | X   | 0      | X    |     | ... |     |     | 0   | 0   |
|      |      | 1    | X       | X   | X      | 0    |     |     |     |     | 0   | 0   |
|      |      | 0    | 0       | X   | X      | X    |     |     | 0   | 1   | 1   | 0   |
|      |      |      | 1       | 0   | 0      | X    |     |     | 0   | ... | ... | 0   |
|      |      |      | 1       | 0   | 1      | 1    |     |     | 1   |     |     | 1   |
|      |      |      | 1       | 1   | 0      | 0    |     |     | 0   |     |     |     |
|      |      |      | 1       | 1   | 0      | 1    |     |     | 1   |     |     | 1   |
|      |      |      | 1       | 1   | 1      | 0    |     |     | 1   |     |     | 1   |
|      |      |      | 1       | 1   | 1      | 1    |     |     | 0   |     |     | 0   |
![[Pasted image 20260119163304.png]]
erstes wahr
zweites falsch
![[Pasted image 20260119163436.png]]
$exists y exists "ev" exists x "Einladung"(y,x,"ev") and not "Event"("ev")$

![[Pasted image 20260119163739.png]]
$forall x "Laut"(x) xor forall x "Event"(x)$

![[Pasted image 20260119163838.png]]
$forall p exists e "Person"(p) and "Teilnahme"(p,e) and "Laut"(e)=> "Laut"(p)$
![[Pasted image 20260119163957.png]]
$exists e "Event"(e) and forall p "Person"(p) and "Laut"(p) => "Teilnahme"(p,e)$

![[Pasted image 20260119164125.png]]
$exists p exists e "Person"(p) and "Event"(e) and exists x "Einladung"(p,x,e) and not exists x "Einladung"(x,p,e)$

![[Pasted image 20260119164420.png]]
1-2
2-1
3-2
![[Pasted image 20260119164635.png]]
nicht äquivalent
exists x a
not exists x not a = forall x a
nicht äquivalent

![[Pasted image 20260119164906.png]]
$Sigma={0,1,"reset"}$
$Γ ={0,1,"err"}$

![[Pasted image 20260119165101.png]]
siehe mappe

![[Pasted image 20260119165546.png]]
11011010  => 10010011
01011100 => err err err err err err err err
![[Pasted image 20260119165726.png]]
falsch
falsch
??? (wahr geraten vom namen her)
wahr
falsch
falsch
falsch
wahr ... kann auch akzeptieren  muss nicht

![[Pasted image 20260119170001.png]]
$[-][0-9]+(.[0-9]+)?$

![[Pasted image 20260119170136.png]]
`[A-U](\.[0-9]{2}(\.[0-9]{3}(\.[0-9]{4})?)?)?`
![[Pasted image 20260119170431.png]]
1,{b,x,bb,bx}*{b,f}={bb,xb,bbb,bxb,bf,xf,bbf,bxf}
2, {ok, onl, o, oll, onn, oln}
3, {$epsilon$}
4, {rr,rh,rq,hr,hh,hq,qr,qh,qq}
5, {o, nl}

![[Pasted image 20260119170912.png]]
siehe mappe

![[Pasted image 20260119171242.png]]
links, beides 3
rechts, beides 1

![[Pasted image 20260119171351.png]]
siehe mappe

in 65 min mit nachschauen welcher mealy moore, und welche regex welche
