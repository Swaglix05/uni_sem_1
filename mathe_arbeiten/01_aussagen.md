Eine Aussage ist ein Satz, dem man einen objektiven Wahrheitswert zuweisen kann, der entweder wahr oder falsch ist. Wir identifizieren den Wahrheitswert wahr mit der Zahl 1 und falsch mit 0. Einige Beispiele von Aussagen und ihren Wahrheitswerten sind:

<table><tr><td>Aussage</td><td>Wahrheitswert</td></tr><tr><td>Wale sind Säugetiere.</td><td>1</td></tr><tr><td>2 + 2 = 4</td><td>1</td></tr><tr><td>10 ist eine Primzahl.</td><td>0</td></tr><tr><td>4 ist groß aber als 3.</td><td>1</td></tr></table>

Bei einer Aussage muss es sich also um einen ganzen Satz, z.B. der deutschen Sprache, handeln. So ist etwa “Zwei plus zwei ist fünf.” eine Aussage, “zwei plus zwei” aber nicht.

"Hoffentlich regnet es bald." oder "Lesen Sie das Skriptum." sind während Sätze der deutschen Sprache, aber keine Aussagen in unserem Sinn da ihren kein Wahrheitswert zugewiesen werden kann.

Ein weiteres wichtiges Element dieser Definition ist die Objektivität. Es gibt zwar viele interessante Aussagen denen kein objektiver Wahrheitswert zugewiesen werden kann, wie z.B. "Avocado schmeckt gut.", aber solche Aussagen sind nicht Gegenstand der Mathematik und deshalb schlieben wir sie hier aus.

Weiters ist es für die Frage ob ein Satz eine Aussage ist unerheblich ob der Wahrheitswert besteht. So ist z.B. auch der folgende Satz eine Aussage

"Jede gerade Zahl die grober gleich 4 ist kann als Summe zweier Primzahlen geschrieben werden."

These Aussage ist auch als Goldbachsche Vermutung besteht. Es ist in der Mathematik nicht besteht. Ob diese Aussage wahr oder falsch ist. Eine Aussage ist es trotzdem weil ihr ein objektiver Wahrheitswert zugewiesen werden kann, auch wenn niemand weiß welcher es ist.

Es gibt eine Reihe von Mänglichkeiten um Aussagen zu verknüpfen und darauf neue Aussagen zu erhalten.

Konjunktion (und-Verknüpfung). Falls  $A$  und  $B$  Aussen sind, so ist auch  $A \wedge B$  (ausgesprochen als "A und  $B$ ) eine Aussage. Wir sagen auch dass  $A \wedge B$  die Konjunktion von  $A$  und  $B$  ist und dass die Aussen  $A$  und  $B$  die Konjunkte von  $A \wedge B$  sind. Die Aussen  $A \wedge B$  ist wahr/genau dann

wenn sowohl  $A$  wahr ist als auch  $B$  wahr ist. Die Bedeutung der Konjunktion kann durch die folgenden Wahrheitsstafel definiert werden. Auf der linken Seite werden alle (vier) möglichkeiten für die Wahrheitswerte von  $A$  und  $B$  eingetragen. Auf der rechten Seite wird, für jeder dieser möglichkeiten, der Wahrheitswert von  $A \land B$  eingetragen.

<table><tr><td>A</td><td>B</td><td>A∧B</td></tr><tr><td>0</td><td>0</td><td>0</td></tr><tr><td>0</td><td>1</td><td>0</td></tr><tr><td>1</td><td>0</td><td>0</td></tr><tr><td>1</td><td>1</td><td>1</td></tr></table>

![](01_aussagen_warning.png)
$\textbf{Warning 1.1.}$  Das Symbol  $\wedge$  scarf nicht auf naive Weise als Abkürzung des Wortes "und" benutzt werden. So kann z.B. die Aussage  $x$  und  $y$  sind großer als  $0$  nicht geschrieben werden als  $x \wedge y > 0$  da  $x \wedge y$  keine Zahl ist. Richtig ist stattdessen:  $x > 0 \wedge y > 0$ . Ähnliches gilt für die im Weiteren vorgestellt den Verknüpfungen auch.

Disjunktion (oder-Verknupfung). Falls  $A$  und  $B$  Aussagen sind, so ist auch  $A\lor B$  (ausgesprochen als "A oder  $B$ ") eine Aussage2. Die Aussage  $A\lor B$  liegt Disjunktion von  $A$  und  $B$  und die Aussen  $A$  und  $B$  halten Disjunkte von  $A\lor B$ . Die Aussenage  $A\lor B$  ist wahr genau dann wenn  $A$  wahr, wenn  $B$  wahr ist oder wenn sowohl  $A$  als auch  $B$  wahr sind. Durch eine Wahrheitsstafel kann das wie folgt dargestellt werden:

<table><tr><td>A</td><td>B</td><td>A ∨ B</td></tr><tr><td>0</td><td>0</td><td>0</td></tr><tr><td>0</td><td>1</td><td>1</td></tr><tr><td>1</td><td>0</td><td>1</td></tr><tr><td>1</td><td>1</td><td>1</td></tr></table>

Es handelt sich damit also um eine inklusive Disjunktion, d.h. falls beiden Disjunkte wahr sind ist auch die Disjunktion wahr. Bei einer exclusive Disjunktionäre in diesen Fall die Disjunktion falsch. In der Alltagssprache wird das Wort "oder" sowohl für inklusive als auch für exklusive Disjunktion verwendet wie der folgende Dialog veranschaulicht:

Kellner: Wollen Sie Kaffee oder Tee? (exklusives oder)

Gast: Kaffeeitte.

Kellner: Wollen Sie Zucker oder Milch dazu? (inklusives oder)

Gast: Beides, danke.

In der Mathematik werden wir mit "oder" immer das inklusive oder unseren.

Negation (Verneinung). Falls  $A$  eine Aussage ist, dann ist auch  $\neg A$  (ausgesprochen als "nicht  $A$ ") eine Aussage. Die Aussage  $\neg A$  heißt auch Negation oder Verneinung von  $A$  und ist wahr wenn  $A$  falsch ist und umgekehrt, siehe folgende Wahrheitsstafel:



<table><tr><td>A</td> $\neg A$ <td> 
 
</td></tr><tr><td>0</td><td>1</td></tr><tr><td>1</td><td>0</td></tr></table>

Die Verneinung wird damit in einem streng logischen Sinn verstanden. Sei z.B. A die Aussage "Die Wand ist weiß". Dann ist die Verneinung ¬A von A die Aussage "Die Wand ist nicht weiß", nicht aber die Aussage "Die Wand ist schwarz". Die Verneinung ist also nicht desselbe wie das Gegenteil.

Implication. Sind  $A$  und  $B$  Aussagen, dann ist auch  $A \Rightarrow B$  (ausgesprochen als "A impliziert  $B$ ", "wenn  $A$  dann  $B$ , "aus  $A$  folgt  $B$ ", ...) eine Aussage. Ein Beispiel für eine Implication ist die Aussage "Falls es regnet, dann ist die Straße nass." Man beachte dass die Implication (anders als Konjunktion und Disjunktion) nicht commutativ ist, d.h.  $A \Rightarrow B$  hat eine andere Bedeutung als  $B \Rightarrow A$ . Falls die Straße nass ist, bedeutet das nicht dass es regnet; sie konnte auch gerade gewaschen worden sein. Die Interpretation von Impikationen wird durch die folgende Wahrheitstafel definiert.

<table><tr><td>A</td><td>B</td><td>A ⇒ B</td></tr><tr><td>0</td><td>0</td><td>1</td></tr><tr><td>0</td><td>1</td><td>1</td></tr><tr><td>1</td><td>0</td><td>0</td></tr><tr><td>1</td><td>1</td><td>1</td></tr></table>

Falls also  $A$  wahr ist, dann hat  $A \Rightarrow B$  den Wahrheitswert von  $B$ . Falls  $A$  falsch ist dann ist es egal was rechts steht,  $A \Rightarrow B$  hat immer den Wahrheitswert wahr. Man beachte dass dadurch  $A \Rightarrow B$  auch wahr ist wenn sowohl  $A$  als auch  $B$  falsch sind. Z.B. ist die Aussage "Falls der Mond aus Käse ist, dann ist  $2 + 2 = 5$ ." wahr. Das ist etwas unintuitiv, da das Material des Mondes nichts mit den Wert von  $2 + 2$  zu tun hat. In der Mathematik spiel thises Phenomen aber practisch keine Rolle da man typischerweise solche Implicationen betrachtet wo 1. die Voraussetzung etwas mit der Folgerung zu tun hat und 2. die Voraussetzung wahr ist.

Aequivalenz. Die letzte Verknüpfung von Aussagen die wir betrachten sollen ist die logische Äquivalenz. Sind  $A$  und  $B$  Aussagen so ist auch  $A \Leftrightarrow B$  (ausgesprochen als "A.Genau dann wenn  $B$ " oder "A dann und nur dann wenn  $B$ ) ) eine Aussage. Die Wahrheitstafel für die Äquivalenz ist:

<table><tr><td>A</td><td>B</td><td>A ⇌ B</td></tr><tr><td>0</td><td>0</td><td>1</td></tr><tr><td>0</td><td>1</td><td>0</td></tr><tr><td>1</td><td>0</td><td>0</td></tr><tr><td>1</td><td>1</td><td>1</td></tr></table>

Formeln. Eine Aussage kann also durch die Konnektive  $\wedge, \vee, \neg, \Rightarrow$  und  $\Leftrightarrow$  aus einfacheren Aussagen zusammengesetzt werden. Diese bezeichnet man auch als atomare Aussagen der zusammengesetzten Aussage. So sind z.B.  $A$  und  $B$  die atomaren Aussagen der zusammengesetzten Aussage ( $\neg A \lor B) \Leftrightarrow (A \Rightarrow B)$ . Wie Sie es vom Rechnen mit Zahlen gewöhnt sind gibt es auch hier Klammersetzungsregeln: am stärksten bindet die Negation  $\neg$ , dann kommt die "Punktrechnungen"  $\wedge$  und  $\vee$  vor den "Strichrechnungen"  $\Rightarrow$  und  $\Leftrightarrow$ . Damit kann die obige Aussage auch geschrieben werden als  $\neg A \lor B \Leftrightarrow (A \Rightarrow B)$  oder als (( $\neg A$ $\lor B$ )  $\Leftrightarrow (A \Rightarrow B)$ .

Ist der Wahrheitswert der atomaren Aussagen besteht so kann darauf der Wahrheitswert der zusammengesetzten Aussage berechnet werden. Damit können auch für komplexere zusammengesetzte Aussagen Wahrheitsstafeln erstellt werden. Ein Beispiel für eine Wahrheitsstafel ist:

<table><tr><td>A</td><td>B</td><td>¬A</td><td>¬A ∨ B</td><td>A ⇒ B</td><td>(¬A ∨ B) ⇌ (A ⇒ B)</td></tr><tr><td>0</td><td>0</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>0</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td><td>1</td></tr><tr><td>1</td><td>1</td><td>0</td><td>1</td><td>1</td><td>1</td></tr></table>

Beim Erstellen einer Wahrheitsstafel ist es oft practisch auch die Wahrheitswerte von Teilaussagen als Zwischenergebnisse zu berechnen (wie das hier für z.B. für  $\neg A \lor B$  gemacht wurde).

Eine Aussage heißt erfüllbar wenn es eine Wahrheitswertbelegung ihrer atomaren Aussagen gibt die sie wahr macht, d.h. wenn es eine Zeile in der Wahrheitsstafel gibt die 1 ergibt. Eine Aussage heißt unerfüllbar wenn das nicht der Fall ist, d.h. wenn alle Zeilen der Wahrheitsstafel 0 ergeben. Eine Aussage heißt gültig wenn sie unter allen Wahrheitswertbelegungen ihrer atomaren Aussagen wahr ist, d.h. wenn alle Zeilen ihrer Wahrheitsstafel 1 ergeben. So ist etwa im obigen Beispiel die Aussage  $A \Rightarrow B$  erfüllbar und die Aussage  $(\neg A \lor B) \Leftrightarrow (A \Rightarrow B)$  gültig.

Das Teilgebiet der Logik, das sich mit Aussagen beschäftigt die aus atomaren Aussagen durch Operationen wie diesen zusammengesetzt sind, bezeichnet man als Aussagenlogik. Eine zusammengesetzte Aussage bezeichnet man auch als aussagenlogische Formel.

Rechenregeln. Innerhalb einer zusammengesetzten Aussage kann man, wie beim Rechnen mit Gleichungen, eine Teilaussage durch eine andere äquivalente Teilaussage ersetzen ohne ihre Bedeutung zu verändern. Z.B. wollen wir aufgrund obiger Wahrheitsstafel dass  $\neg A \lor B$  und  $A \Rightarrow B$  für alle Aussagen  $A$  und  $B$  äquivalent sind. Daraus folgt z.B. dass die Aussagen

$$
F \Rightarrow ((C \wedge D) \Rightarrow E) \quad \text {u n d} \quad F \Rightarrow (\neg (C \wedge D) \vee E)
$$

ebenfalls äquivalent sind. Für Aussagen gelten die folgenden Rechenregeln:

Kommutativität:  $A \wedge B \Leftrightarrow B \wedge A$

Assoziativität:  $(A\wedge B)\wedge C\Leftrightarrow A\wedge (B\wedge C)$

Idempotentz:  $A\wedge A\Leftrightarrow A$

$A\lor B\Leftrightarrow B\lor A$

$$
(A \lor B) \lor C \Leftrightarrow A \lor (B \lor C)
$$

$$
A \lor A \Leftrightarrow A
$$

Distributivität:  $A \wedge (B \lor C) \Leftrightarrow (A \land B) \lor (A \land C)$

$$
A \vee (B \wedge C) \Leftrightarrow (A \vee B) \wedge (A \vee C)
$$

Regeln von de Morgan:  $\neg (A\lor B)\Leftrightarrow \neg A\land \neg B$

$$
\neg (A \wedge B) \Leftrightarrow \neg A \vee \neg B
$$

Zur Implication:  $\neg A \lor B \Leftrightarrow A \Rightarrow B$

$$
(A \Leftrightarrow B) \Leftrightarrow (A \Rightarrow B) \wedge (B \Rightarrow A)
$$

Doppelnegation:  $\neg \neg A\Leftrightarrow A$

All these Rechenregeln können durch Wahrheitsfalen bewiesen werden.

# Das Wichtigste in Kürze.

- Eine Aussage ist ein Satz, dem man einen objektiven Wahrheitswert zuweisen kann, der entweder wahr oder falsch ist.  
- Aussagen werden durch Verknüpfungen, wie z.B. ∧, ∨, ¬, ⇒, ⇌, zu neuen Aussagen zusammen-gesetzt.  
- Mit einer Wahrheitsstafel kann festgestellt werden, ob eine gegebenen Aussage (un)erfüllbar oder (un)gültig ist.  
- Gültige Äquivalenzen können wie Rechenregeln verwendet werden.
