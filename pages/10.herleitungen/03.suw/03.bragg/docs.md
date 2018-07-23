---
title: Bragg-Reflexion
taxonomy:
    category: docs
---

! ##### **Aufgabe:**
! 
! Schickt man Mikrowellen auf eine Anordnung von einigen Reihen mit Metallstäben (die Reihen haben einen Abstand $d$), dann kann man unter einem Glanzwinkel $\alpha$ mit einem geeigneten Detektor Maxima feststellen.
! 
! **Leiten** Sie begründet mit Hilfe einer geeigneten Skizze eine Formel für den Zusammenhang zwischen der Wellenlänge $\lambda$ der Mikrowellenstrahlung und dem Glanzwinkel $\alpha$ **her**.

Für diese Herleitung wird das klassische Modell "Mikrowellenstrahlung ist eine elektromagnetische Welle (= Licht)" gewählt.

Die Situation wird mit Hilfe der folgenden Skizze veranschaulicht:

![](suw_bragg_01.svg?classes=caption "Abbildung 1")

Wie in Abbildung 1 gezeigt wird, legt der Lichtstrahl 2 aufgrund der versetzten Reihen von Metallstäben bis zum Detektor einen weiteren Weg als der Lichtstrahl 1 zurück. Der Gangunterschied beträgt insgesamt $\Delta s$.

Nach dem huygenschen Prinzip senden die Metallstäbe gleichphasige Elementarwellen aus. Ist der Gangunterschied zweier gleichphasiger Wellenzüge ein ganzzahliges Vielfaches der Wellenlänge $\lambda$, verstärken sie sich zu einem Maximum (konstruktive Interferenz). Es gilt dann

$$
\Delta s = n \cdot \lambda \:\:\: \text{mit} \:\:\: n = 0, 1, 2,...
$$

Den Glanzwinkel $\alpha$, unter dem der Mikrowellenstrahl die Metallstabreihe trifft, findet man in dem rechtwinkeligen Dreick wieder, das durch das Lot auf den zweiten Lichtstrahl, den Abstand $d$ zwischen den beiden Metallstabreihen und der Hälfte des Gangunterschieds $\Delta s$ gebildet wird (siehe Abbildung 2).

![](suw_bragg_02.svg?classes=caption "Abbildung 2")

Es gilt also

$$
sin(\alpha) = \frac{\text{Gegenkathete}}{\text{Hypothenuse}} = \frac{\frac{\Delta s}{2}}{d} = \frac{\Delta s}{2 \cdot d}
$$

Mit $\Delta s = n \cdot \lambda$ folgt:

$$
sin(\alpha) = \frac{n \cdot \lambda}{2 \cdot d}
$$

Formt man diese Gleichung so um, dass $n \cdot \lambda$ auf der linken Seite stehen, folgt

$$
n \cdot \lambda = 2 \cdot d \cdot sin(\alpha)
$$

**Damit ist der Zusammenhang zwischen der Wellenlänge $\lambda$ und dem Glanzwinkel $\alpha$ erfolgreich hergleitet worden.**
