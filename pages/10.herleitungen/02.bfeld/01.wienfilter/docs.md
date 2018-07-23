---
title: Wienfilter
taxonomy:
    category: docs
---

! ##### Aufgabe:
! 
! Mit einem **Wien-Filter** kann man aus einem Strahl geladener Objekte diejenigen mit einer bestimmten Geschwindigkeit $v$ herausfiltern.
! 
! **Erklären** Sie die Funktionsweise eines Wienfilters und **leiten Sie begründet eine Formel her**, die den Zusammenhang zwischen den Feldgrößen und der Geschwindigkeit angibt.

Für die folgende **Erklärung** wird das klassische Modell **"geladenes Objekt ist ein Teilchen mit Masse und Ausdehnung"** verwendet.

Der Strahl mit den geladenen Objekten soll im folgenden ein **Elektronenstrahl** sein. Im gewählten Beispiel soll das **Magnetfeld B** in die Ebene zeigen und das **elektrische Feld E** von unten nach oben gerichtet sein.

![](bfeld_wienfilter_01.svg?classes=caption "Abbildung 1")

Sobald der Elektronenstrahl den Bereich des geladenen Kondensators erreicht, erfährt ein Elektron eine elektrische Kraft $F_{el}$ nach oben, da es vom  Minuspol abgestoßen und vom Pluspol angezogen wird. Durch das gleichzeitig im Kondensator vorhandene Magnetfeld erfährt das Elektron nach der linken-Hand-Regel eine Lorentzkraft $F_L$ nach unten (siehe Abbildung 2). 

![](bfeld_wienfilter_02.svg?classes=caption "Abbildung 2")

Alle Elektronen, welche mit der betragsgleichen Kraft nach oben und unten abgelenkt werden, können den Wienfilter **geradlinig** durchfliegen (grauer Strahl). Überwiegt die elektrische Kraft $F_{el}$, werden die Elektronen nach **oben abgelenkt** (roter Strahl). Ist der Betrag der Lorentzkraft $F_L$ größer, werden die Elektronen nach **unten abgelenkt** (grüner Strahl).

![](bfeld_wienfilter_03.svg?classes=caption "Abbildung 3")

Im folgenden soll **hergeleitet** werden, welche Geschwindigkeit ein Elektron haben muss, um den Wien-Filter geradlinig zu durchfliegen.

Für die **elektrische Kraft $F_{el}$**, welche im Kondensator auf ein Elektron wirkt, gilt: 

$$
F_{el} = q \cdot E
$$

mit $q$ = Ladung eines Elektrons, $E$ = Elektrische Feldstärke

Für die **Lorentzkraft $F_L$**, welche im Bereich des Magnetfelds auf ein Elektron wirkt, gilt:

$$
F_L = q \cdot v \cdot B
$$

mit $q$ = Ladung eines Elektrons, $v$ = Geschwindigkeit eines Elektrons, $B$ = magnetische Feldstärke

Für die Elektronen, welche den Wien-Filter geradlinig durchfliegen, gilt:

$$
F_{el} = F_L
$$

Setzt man die Formeln ein, folgt:

$$ 
\begin{align}
F_{el} &= F_L \\
q \cdot v \cdot B &= q \cdot E \\
v \cdot B &= E \\
v &= \frac{E}{B}
\end{align}
$$

**Damit hat man gezeigt:** Alle Elektronen mit der Geschwindigkeit $v = \frac{E}{B}$ können den Wienfilter geradlinig durchfliegen. Da bei der Herleitung die Ladung $q$ weggefallen ist, gilt diese Formel für alle geladenen Objekte, also auch z.B. Protonen und Ionen.

---