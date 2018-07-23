---
title: Elektronenstrahl im Kondensator
taxonomy:
    category: docs
---

Eine **Elektronenstrahlröhre** ist wie folgt aufgebaut:

![](efeld_estrahlroehre_01.svg?classes=caption "Abbildung 1")

Nach der Erzeugung, Beschleunigung und Fokussierung wird der Elektronenstrahl in einem Ablenkkondensator in y-Richtung abgelenkt. Folgende Aufgabe ist in diesem Zusammenhang denkbar. 

! ##### **Aufgabe**
!
! Die Flugbahn eines Elektronenstrahls in einem Ablenkkondensator (siehe Abbildung 2), kann beschrieben werden durch die Formel
!
! $$
! y(x) = \frac{U_y}{4 \cdot d \cdot U_B} \cdot x^2
! $$
!   - $y(x)$ = $y$-Koordinate des Elektronenstrahls an der Stelle $x$ im Ablenkkondensator
!   - $d$ = Abstand der Kondensatorplatten
!   - $U_y$ = Spannung zwischen den Platten des Ablenkkondensators
!   - $U_B$ = Beschleunigungsspannung zwischen Glühdraht und Lochanode in $x$-Richtung
!   - $x$ = $x$-Koordinate des Elektronenstrahls im Ablenkkondensator
!
! **Leiten Sie diese Formel begründet her.**

![](efeld_estrahlroehre_02.svg?classes=caption "Abbildung 2")

Für die folgende Herleitung wird das klassische Modell **"ein Elektron ist ein geladenes Teilchen mit Masse und Ausdehnung"** verwendet.

---

**Bewegung des Elektrons in x-Richtung:**

Der Elektronenstrahl erreicht den Ablenkkondensator mit der Geschwindigkeit 

$$
v_x = \sqrt{\frac{2 \cdot U_B \cdot q}{m_e}}
$$

im Punkt $O(0/0)$ (Herleitung siehe **Elektronenstrahlerzeugung**).

In $x$-Richtung wirkt auf das Elektron keine Kraft. Daher bewegt sich das Elektron in **$x$-Richtung** mit der **konstanten Geschwindigkeit** 

$$
v_x = \frac{x}{t}
$$

Zum Zeitpunkt $t$ befindet sich das Elektron dann am Ort $x = v_x \cdot t$.

---

**Kraftwirkung auf das Elektron im Ablenkkondensator:**

Innerhalb des Ablenkkondensators wird ein Elektron von der negativ geladenen Platte abgestossen und von der positiv geladenen Platte angezogen. In $y$-Richtung wirkt also die Kraft $F_{el}$.

Für die elektrische Feldstärke $E$ gilt: 

$$
E = \frac{F_{el}}{q}
$$

mit $q$ = Ladung eines Elektrons und damit 

$$
F_{el} = q \cdot E
$$

Die elektrische Feldstärke $E$ kann mit Hilfe der Spannung $U_y$ beschrieben werden: 

$$
E = \frac{U_y}{d}
$$

Also gilt insgesamt für die auf das Elektron wirkende **elektrische Kraft $F_{el}$** im Ablenkkondensator: 

$$
F_{el} = q \cdot E = q \cdot \frac{U_y}{d}
$$

oder

$$
F_{el} = \frac{U_y \cdot q}{d}
$$

---

**Bewegung in y-Richtung:**

Aufgrund der in $y$-Richtung wirkenden Kraft $F_{el}$, wird das Elektron in $y$-Richtung beschleunigt. Da sich die beschleunigende Kraft $F_{el}$ innerhalb des Plattenkondensators nicht ändert, ist die **Beschleunigung** $a_y$ des Elektrons in **$y$-Richtung konstant** und es gilt das Newtonsche Grundgesetz:

$$
F = m \cdot a
$$

und hier speziell 

$$
F_{el} = m_e \cdot a_y
$$

Für die Beschleunigung $a_y$ gilt also mit $F_{el} = \frac{U_y \cdot q}{d}$:

$$
a_y = \frac{F_{el}}{m_e} = \frac{U_y \cdot q}{m_e \cdot d}
$$

Bei einer beschleunigten Bewegung in $y$-Richtung gilt für den Ort $y$ (siehe Formelsammlung):

$$
y = \frac{1}{2} \cdot a_y \cdot t^2
$$

ersetzt man $a_y$ mit $a_y = \frac{U_y \cdot q}{m_e \cdot d}$, folgt:

$$
y = \frac{1}{2} \cdot \frac{U_y \cdot q}{m_e \cdot d} \cdot t^2
$$

---

**$y$-Ablenkung in Abhängigkeit vom Ort $x$:**

Aus $v_x = \frac{x}{t}$ folgt 

$$
t = \frac{x}{v_x}
$$

Damit ersetzt man $t$ in der Formel für die Auslenkung $y$:

$$
y = \frac{1}{2} \cdot \frac{U_y \cdot q}{m_e \cdot d} \cdot t^2 = \frac{1}{2} \cdot \frac{U_y \cdot q}{m_e \cdot d} \cdot \left( \frac{x}{v_x} \right) ^2 = \frac{U_y \cdot q}{2 \cdot m_e \cdot d \cdot v_x^2} \cdot x^2
$$

Für die Geschwindkeit $v_x$ wissen wir, dass gilt: 

$$
v_x = \sqrt{\frac{2 \cdot U_B \cdot q}{m_e}}
$$

Damit wird das $v_x$ in der Formel für die Auslenkung $y$ ersetzt:

$$
\begin{align}
\require{cancel}
y &= \frac{U_y \cdot q}{2 \cdot m_e \cdot d \cdot \left( \sqrt{\frac{2 \cdot U_B \cdot q}{m_e}} \right) ^2} \cdot x^2 \\
y &= \frac{U_y \cdot q}{2 \cdot m_e \cdot d \cdot \frac{2 \cdot U_B \cdot q}{m_e} } \cdot x^2 \\
y &= \frac{U_y \cdot \cancel{q} \cdot \cancel{m_e}}{4 \cdot \cancel{m_e} \cdot d \cdot U_B \cdot \cancel{q}} \cdot x^2 \\
\end{align}
$$

und schließlich:

$$
y(x) = \frac{U_y}{4 \cdot d \cdot U_B} \cdot x^2
$$

**Damit ist die Formel begründet hergeleitet worden.**

---

! ##### **Aufgabe**
!
! Ein Elektronenstrahl durchfliegt einen Ablenkkondensator der Länge $l$ mit dem Plattenabstand $d$. Nachdem ein Elektron den Kondensator verlassen hat, fliegt es kräftefrei weiter, bis es auf einen Schirm im Punkt $Q(x_Q/y_Q)$ auftrifft (siehe Abbildung 3). Für die $x$-Koordinate des Auftreffpunkts $Q$ gilt offensichtlich $x_Q = l + s$. Für die $y$-Koordinate von $Q$ gilt: 
!
! $$
! y_Q = \frac{U_y}{4 \cdot d \cdot U_B} \cdot (l^2 + 2 \cdot l \cdot s)
! $$
!   - $U_y$ = Spannung zwischen den Platten des Ablenkkondensators
!   - $U_B$ = Beschleunigungsspannung zwischen Glühdraht und Lochanode in $x$-Richtung
!   - $s$ = Abstand des Schirms vom Ablenkkondensator
!
! **Leiten Sie diese Formel begründet her.**

![](efeld_estrahlroehre_03.svg?classes=caption "Abbildung 3")

Für die folgende Herleitung wird das klassische Modell **"ein Elektron ist ein geladenes Teilchen mit Masse und Ausdehnung"** verwendet.

Das Elektron erreicht den Ablenkkondensator im Punkt $O(0/0)$. Nachdem es den Ablenkkondensator im Punkt $R$ verlassen hat, fliegt es geradlinig mit konstanter Geschwindigkeit weiter, denn es wirkt auf das Elektron keine Kraft mehr (idealisiert). 

Es trifft im Punkt $Q(x_Q/y_Q)$ auf den Schirm. Dabei ist $x_Q = l + s$.

Auf dem Weg vom Ablenkkondensator zum Schirm (**vom Kondensator zum Schirm = KS**) legt das Elektron den Weg $y_{\text{KS}}$ zurück. Insgesamt hat es also folgenden Weg in y-Richtung zurückgelegt:

$$
y_Q = y(l) + y_{\text{KS}}
$$

---

**Bestimmung von $y_{KS}$:**

Zwischen Ablenkkondensator und Schirm bewegt sich das Elektron mit der Geschwindigkeit $v_x$ fort, da es zu keinem Zeitpunkt nach Verlassen der Lochanode in $x$-Richtung beschleunigt wurde. Bis zum Auftreffen auf den Schirm vergeht also die Zeit

$$
t_{\text{KS}} = \frac{s}{v_x}
$$

Im Ablenkkondensator (**Kondensator = K**) wird das Elektron für die Zeit  

$$
t_{\text{K}} = \frac{l}{v_x}
$$

mit der Beschleunigung $a_y$ beschleunigt (siehe obige Herleitung):

$$
a_y = \frac{U_y \cdot q}{m_e \cdot d}
$$

Beim Verlassen des Ablenkkondensators hat das Elektron also in $y$-Richtung die Geschwindigkeit $v_y$:

$$
v_y = a_y \cdot t_{\text{K}} = \frac{U_y \cdot q}{m_e \cdot d} \cdot \frac{l}{v_x}
$$

Auf dem Weg vom Ablenkkondensator zum Schirm legt das Elektron in $y$-Richtung also folgenden Weg zurück:

$$
y_{\text{KS}} = v_y \cdot t_{\text{KS}} = \frac{U_y \cdot q}{m_e \cdot d} \cdot \frac{l}{v_x} \cdot \frac{s}{v_x}
$$

Setzt man jetzt für die Geschwindigkeit $v_x = \sqrt{\frac{2 \cdot U_B \cdot q}{m_e}}$ ein (siehe Herleitung zur Elektronenstrahlerzeugung), dann folgt:

$$
\begin{align}
\require{cancel}
y_{\text{KS}} &= \frac{U_y \cdot q}{m_e \cdot d} \cdot \frac{l}{v_x} \cdot \frac{s}{v_x} \\
 &= \frac{U_y \cdot q}{m_e \cdot d \cdot v_x^2} \cdot l \cdot s \\
 &= \frac{U_y \cdot q}{m_e \cdot d \cdot \left( \sqrt{\frac{2 \cdot U_B \cdot q}{m_e}} \right)^2} \cdot l \cdot s \\
 &= \frac{U_y \cdot \cancel{q}}{\cancel{m_e} \cdot d \cdot \left( \frac{2 \cdot U_B \cdot \cancel{q}}{\cancel{m_e}} \right) } \cdot l \cdot s
\end{align}
$$

Also legt das Elektron auf dem Weg vom Ablenkkondensator zum Schirm in $y$-Richtung folgenden Weg zurück: 

$$
y_{\text{KS}} = \frac{U_y}{2 \cdot d \cdot U_B} \cdot l \cdot s
$$

---

**Bestimmung von $y(l)$:**

Innerhalb des Ablenkkondensators bewegt sich das Elektron beschleunigt in $y$-Richtung. Dabei gilt für die $y$-Koordinate in Abhängigkeit vom Ort $x$ (Herleitung siehe oben):

$$
y(x) = \frac{U_y}{4 \cdot d \cdot U_B} \cdot x^2
$$

Wenn die Ablenkspannung $U_y$ so eingestellt wird, dass ein Elektron den Ablenkkondensator verlassen kann ohne auf einer der Kondensatorplatten aufzutreffen, gilt für die $y$-Koordinate an der Stelle $x = l$:

$$
y(l) = \frac{U_y}{4 \cdot d \cdot U_B} \cdot l^2
$$

   - $d$ = Abstand der Kondensatorplatten
   - $U_y$ = Spannung zwischen den Platten des Ablenkkondensators
   - $U_B$ = Beschleunigungsspannung zwischen Glühdraht und Lochanode in $x$-Richtung
   - $l$ = Länge des Ablenkkondensators

---

**Bestimmung des insgesamt zurückgelegten Wegs $y_Q$ in $y$-Richtung:**

Der insgesamt in $y$-Richtung zurückgelegte Weg $y_Q$ ist die Summe aus $y(l)$ und $y_{\text{KS}}$:

$$
y_Q = y(l) + y_{\text{KS}}
$$

mit 

$$
y(l) = \frac{U_y}{4 \cdot d \cdot U_B} \cdot l^2
$$ 

und 

$$
y_{\text{KS}} = \frac{U_y}{2 \cdot d \cdot U_B} \cdot l \cdot s
$$

Setzt man diese Ausdrücke in die Summe $y_Q = y(l) + y_{\text{KS}}$ ein, folgt:

$$
\begin{align}
y_Q &= \frac{U_y}{4 \cdot d \cdot U_B} \cdot l^2 + \frac{U_y}{2 \cdot d \cdot U_B} \cdot l \cdot s \\
 &= \frac{U_y}{4 \cdot d \cdot U_B} \cdot \left(l^2 + 2 \cdot l \cdot s \right)
\end{align}
$$

Also

$$
y_Q = \frac{U_y}{4 \cdot d \cdot U_B} \cdot \left(l^2 + 2 \cdot l \cdot s \right)
$$

**Damit ist die Formel begründet hergeleitet worden.**

---