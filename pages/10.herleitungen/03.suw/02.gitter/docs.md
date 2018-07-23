---
title: Das optische Gitter
taxonomy:
    category: docs
---

! ##### Aufgabe:
! 
! Erzeugt man bei Verwendung eines Gitters auf einem Schirm ein Interferenzbild, dann gilt für die **Maxima**:
! 
! $$
! n \cdot \lambda = g \cdot \sin \left[ \arctan \left(\frac{a_n}{e} \right) \right]
! $$
! $n = 0, 1, 2, 3, ...$   
! $\lambda = $ Wellenlänge des verwendeten Lichtstrahl   
! $g = $ Gitterkonstante (Abstand zweier benachbarter Gitteröffnungen)   
! $a_n = $ Abstand zwischen 0. Maximum und n. Maximum   
! $e = $ Abstand zwischen Gitter und Schirm
!
! **Leiten** Sie diese Gleichung **begründet** mit Hilfe geeigneter Skizzen **her**.

Bei dieser Herleitung wird das klassische Modell **"Licht ist eine elektromagnetische Welle"** verwendet. 

Das von der Lichtquelle kommende Licht trifft auf das Gitter. Jede Gitteröffnung wird nach dem **huygenschen Prinzip** als Ausgangspunkt einer **Elementarwelle** angesehen, die das Gitter **gleichphasig** verlassen. Auf dem Schirm interferieren die Elementarwellen, so dass dort **Maxima** (helle Stellen) und **Minima** (dunkle Stellen) zu beobachten sind.

Anstelle der gesamten Elementarwellen betrachten wir im folgenden vereinfachend den vom Gitter ausgehenden Lichtstrahl in Richtung des 0. Maximums und den Lichtstrahl in Richtung des 1. Maximums. Diese Lichtstrahlen bilden zusammen mit dem Schirm ein rechtwinkeliges Dreieck (siehe **Abbildung 1**).

![](suw_gitter_01.svg?classes=caption "Abbildung 1")

Relativ zum Winkel $\alpha$, unter dem man auf dem Schirm ein Maximum beobachtet, ist $a_n$ die **Gegenkathete** und $e$ die **Ankathete**. Damit gilt:
$$
\tan(\alpha) = \frac{\text{Gegenkathete}}{\text{Ankathete}} = \frac{a_n}{e} \Leftrightarrow \alpha = \arctan \left( \frac{a_n}{e} \right)
$$

Im Unterricht wird dieses Experiment mit UV-, sichtbarem und Infrarot-Licht durchgeführt. Damit ein deutliches 1. Maximum zu beobachten ist, muss die Gitterkonstante $g$ (Abstand der Mitte zweier Gitteröffnungen) etwa $1/500 \: mm$ groß sein. Die Entfernung zweier benachbarter Gitteröffnungen ist im Vergleich zum Abstand Gitter-Schirm sehr klein. Je kleiner der Abstand zweier benachbarter Gitteröffnungen ist, desto **paralleler** werden die Lichtstrahlen, die sich in einem Punkt treffen (siehe **Abbildung 2**). 

![](suw_gitter_02.svg?classes=caption "Abbildung 2")

Wir können also in guter **Näherung** annehmen, dass bei einer Gitterkonstante von nur einem Bruchteil eines Millimeters, **zwei benachbarte Lichtstrahlen**, die von nebeneinanderliegenden Gitteröffnungen ausgehen und sich in einem Punkt auf dem Schirm treffen, **in guter Näherung als parallel angesehen** werden können.

Da die Elementarwellen das Gitter gleichphasig verlassen, interferieren zwei Lichtstrahlen in einem Punkt auf dem Schirm konstruktiv, wenn für deren Gangunterschied $\Delta s$ gilt, dass dieser ein ganzzahliges Vielfaches der Wellenlänge $\lambda$ ist. Für Maxima gilt also: $\Delta s = n \cdot \lambda$ mit $n = 0, 1, 2,...$.

In **Abbildung 3** sind stark vergrößert zwei Lichtstrahlen skizziert, die von zwei benachbarten Gitteröffnungen ausgesandt werden. Aufgrund der **Näherung aus Schritt 4** gilt, dass diese Lichtstrahlen den Schirm in einem Punkt treffen. Die Lichtstrahlen verlassen das Gitter unter dem Winkel $\alpha$, daher ist der Weg zu dem Interferenzpunkt auf dem Schirm verschieden lang. Die Differenz der beiden verschiedenen Weglängen wird als Gangunterschied $\Delta s$ bezeichnet.

![](suw_gitter_03.svg?classes=caption "Abbildung 3")

Wie **Abbildung 3** zeigt, ist der Winkel $\alpha$ zwischen Lichtstrahl und optischer Achse in dem rechtwinkeligen Dreieck zu finden, das die Gitterkonstante $g$, der Gangunterschied $\Delta s$ und das Lot auf den Lichtstrahl bilden. Relativ zum Winkel $\alpha$ ist $g$ die Hypothenuse und $\Delta s$ die Gegenkathete. Damit gilt:

$$
\sin(\alpha) = \frac{\text{Gegenkathete}}{\text{Hypothenuse}} = \frac{\Delta s}{g}
$$

**Zusammenfassend gilt:**

$$
\begin{align}
\sin(\alpha) &= \frac{\Delta s}{g} \Leftrightarrow \Delta s = g \cdot \sin(\alpha) \\
\alpha &= \arctan \left( \frac{a_n}{e} \right) \\
\Delta s &= n \cdot \lambda
\end{align}
$$

Woraus folgt:

$$
\Delta s = g \cdot \sin \left( \arctan \left( \frac{a_n}{e} \right) \right)
$$

und schließlich

$$
n \cdot \lambda = g \cdot \sin \left( \arctan \left( \frac{a_n}{e} \right) \right)
$$

**Damit ist die Formel begründet hergeleitet worden.**

---

#### Variation der Herleitung für kleine Winkel $\alpha$

! ##### Aufgabe:
! 
! Erzeugt man bei Verwendung eines Gitters auf einem Schirm ein Interferenzbild, dann gilt bei $g \ll e$ für die **Maxima**:
! 
! $$
! n \cdot \lambda = g \cdot \frac{a_n}{e}
! $$
! $n = 0, 1, 2, 3, ...$   
! $\lambda = $ Wellenlänge des verwendeten Lichtstrahl   
! $g = $ Gitterkonstante (Abstand zweier benachbarter Gitteröffnungen)   
! $a_n = $ Abstand zwischen 0. Maximum und n. Maximum   
! $e = $ Abstand zwischen Gitter und Schirm
!
! **Leiten** Sie diese Gleichung **begründet** mit Hilfe geeigneter Skizzen **her**.

**Der Anfang der Argumentation entspricht der obigen Herleitung.** 

**Ergänzung:** Für sehr kleine Winkel $\alpha$ mit $\alpha < 5°$ gilt in guter Näherung, dass $sin(\alpha) \approx \tan(\alpha)$ ist. 

Beispiel: $sin(3°) = 0,05234$ und $tan(3°) = 0,05240$.

Damit gilt für kleine Winkel $\alpha$ in guter Näherung: 

$$
\sin(\arctan(\alpha)) \approx \alpha
$$

und die Formel 

$$
n \cdot \lambda = g \cdot \sin \left( \arctan \left( \frac{a_n}{e} \right) \right)
$$

vereinfacht sich zu 

$$
n \cdot \lambda = g \cdot \frac{a_n}{e}
$$

Damit ist die Formel begründet hergeleitet worden.

---