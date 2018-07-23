---
title: Elektrische Feldstärke
taxonomy:
    category: docs
---

---

! ##### **Aufgabe:**
! 
! **Beschreiben** Sie an einem geeigneten Beispiel, wie man die elektrische Feldstärke in einem Plattenkondensator messen kann und **leiten** Sie begründet eine Formel **her**, um die elektrische Feldstärke $E$ zu berechnen. **Erläutern** Sie, wie die in der hergeleiteten Formel vorkommenden  physikalischen Größen gemessen werden können.

In einem Plattenkondensator hängt an einem Seil der Länge $L$ eine positiv geladene Kugel mit sehr geringen Gewicht (z.B. Tischtennisball). Wird der Plattenkondensator aufgeladen, wirkt im Inneren des Plattenkondensators auf die geladene Kugel eine elektrische Kraft $F_{el}$, die den Tischtennisball auslenkt. Da der Tischtennisball eine Masse $m$ hat, wirkt auf ihn die Gewichtskraft $F_G$. Diese bewirkt eine Rückstellkraft $F_R$ die vom Betrag gleich der elektrischen Kraft $F_{el}$ ist, aber relativ zu dieser entgegengesetzt gerichtet ist (siehe Abbildung 1).

![](efeld_efeldstaerke_01.svg?classes=caption "Abbildung 1")

In dieser **Gleichgewichtslage** gilt:

1) Im **oberen Dreieck** ist die Seillänge $L$ die **Hypothenuse** und die Länge des Lots von der ausgelenkten Kugel auf die Schnur in der Ruhelage $s$ die **Gegenkathete** zum **Winkel $\alpha$**. Damit gilt

$$
sin(\alpha) = \frac{\text{Gegenkathete}}{\text{Hypothenuse}} = \frac{s}{L}
$$

und

$$
\alpha = arcsin \left( \frac{s}{L} \right)
$$

2) Im **unteren Dreieck** ist $F_G$ die **Ankathete** und $F_{el}$ die **Gegenkathete** zum Winkel **$\alpha$**. Damit gilt

$$
tan(\alpha) = \frac{\text{Gegenkathete}}{\text{Ankathete}} = \frac{F_{el}}{F_G}
$$

Für die Gewichtskraft $F_G$ gilt $F_G = m \cdot g$, wobei $g$ der Ortsfaktor ist. Damit gilt für die elektrische Kraft $F_{el}$ 

$$
\begin{align}
F_{el} &= F_G \cdot tan \left( \alpha \right) \\
F_{el} &= F_G \cdot tan \left( arcsin \left( \frac{s}{L} \right) \right) \\
F_{el} &= m \cdot g \cdot tan \left( arcsin \left( \frac{s}{L} \right) \right)
\end{align}
$$

Die elektrische Feldstärke ist per Definition die elektrische Kraft pro Ladung, also 

$$
E = \frac{F_{el}}{Q}
$$

Für die elektrische Feldstärke $E$ gilt folglich:

$$
E = \frac{F_{el}}{Q} = \frac{m \cdot g}{Q} \cdot tan \left( arcsin \left( \frac{s}{L} \right) \right)
$$

**Damit ist eine geeignete Formel für die elektrische Feldstärke $E$ hergeleitet worden:**

$$
E = \frac{m \cdot g}{Q} \cdot tan \left( arcsin \left( \frac{s}{L} \right) \right)
$$

---

##### Näherung

Für sehr kleine Auslenkungen ($\alpha < 5°$) der Kugel aus der Ruhelage, gilt in guter **Näherung**: 

$$
tan(\alpha) \approx sin(\alpha)
$$

Beispiel: $sin(3°) = 0,05234$ und $tan(3°) = 0,05240$.

Damit kann man wie folgt annähern: 

$$
tan \left( arcsin \left( \alpha \right) \right) \approx \alpha
$$

Mit dieser Näherung kann die Formel für die elektrische Feldstärke $E$ wie folgt vereinfacht werden: 

$$
E = \frac{m \cdot g \cdot s}{Q \cdot L}
$$

---

##### Messung der Größen

Die in der hergeleiteten Formel vorkommenden Messgrößen können wie folgt gemessen werden:

Die **Masse $m$** kann mit einer geeigneten **Waage** gemessen werden.

Der **Ortsfaktor $g$** kann der **Formelsammlung** entnommen werden: $g = 9,81 \frac{N}{kg}$.

Die **Länge $s$** kann mit einer **optischen Projektionsmethode** bestimmt werden:

![](efeld_efeldstaerke_02.svg?classes=caption "Abbildung 2")

Zuerst misst man in der Ruhelage bei ungeladenem Kondensator die Entfernung $a$ zwischen Lampe und Kugel im Kondensator. Dann die Entfernung $a'$ zwischen Lampe und Schirm auf den projiziert wird. Dann markiert man auf dem Schirm die Projektion der Position der Kugel in Ruhelage. Schließlich lädt man den Kondensator auf und misst auf dem Schirm die Länge $s'$, also die Projektion der Strecke $s$ auf den Schirm bei ausgelenkter Kugel. Nach dem **Strahlensatz** folgt:

$$
\frac{a}{a'} = \frac{s}{s'}
$$

Damit kann man $s$ mit folgender Formel berechnen:

$$
s = \frac{a}{a'} \cdot s'
$$

Die **Schnurlänge $L$** kann mit einem geeigneten **Metermaß** gemessen werden.

Die **Ladung $Q$** kann mit der **"Pendelmethode"** gemessen werden. Pro Anschlag wird die Ladung $Q_K$ von einer Platte zur anderen transportiert. Bei der Hin- und Herbewegung der Kugel fließt ein pulsierender Gleichstrom, der das Vorzeichen der Ladung bei jeder Plattenberührung ändert. Ein geeignetes Messgerät kann jeweils den Betrag des pulsierenden Gleichstroms bestimmen und die mittlere Stromstärke anzeigen. Ist $t_1$ die Zeit, die die Kugel von einer Platte zur anderen benötigt, gilt damit:

$$
\overline{I} = \frac{Q_K}{t_1}
$$

Während einer Messung zählt man jetzt z.B. 100 Pendelbewegungen von einer Platte zur anderen und misst dabei mit einer Stoppuhr die Zeit $t_{100}$ für alle 100 Pendelbewegungen. Für die Zeit für eine Pendelbewegung gilt dann:

$$
t_1 = \frac{t_{100}}{100}
$$

Ließt man vom Messgerät die mittlere Stromstärke $\overline{I}$ während der 100 Pendelbewegungen ab, kann man damit die Ladung der Kugel angenähert berechnen:

$$
Q_K = \overline{I} \cdot t_1
$$

**So kann man alle benötigten Größen zur Berechnung der elektrischen Feldstärke $E$ messen.**

---