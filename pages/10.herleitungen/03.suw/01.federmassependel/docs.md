---
title: Feder-Masse-Pendel
taxonomy:
    category: docs
---

!! ##### Anmerkung
!! Die Herleitung der folgenden Formel wird im Kerncurriculum **nicht** erwähnt. Daher ist es **wahrscheinlich**, dass sie **nicht** in der Abiturprüfung abgefragt wird (was sinnvoll ist, da die Herleitung relativ kompliziert ist). Als **mathematische Übung** lohnt es sich für Sie aber auf jeden Fall, diese Herleitung einmal intensiv durchzudenken.

! ##### Aufgabe
!
! Die Periodendauer $T$ eines Feder-Masse-Pendels wird beschrieben mit folgender Formel:
!
! $$
! T = 2 \pi \cdot \sqrt{\cfrac{m}{D}}
! $$
!
! dabei ist $m$ = Masse des schwingenden Körpers, $D$ = Federkonstante der verwendeten Feder.
!
! **Leiten Sie diese Formel begründet her**.

**Folgende Kräfte wirken beim Federpendel: **

1) Die **Gewichtskraft** der angehängten Masse $m$ mit $ F_G=m \cdot g$ ($g$ ist der Ortsfaktor) und   
2) die **rückstellende Federkraft** $ F_R = D \cdot y$ ($y$ ist dabei die vertikale Auslenkung).

**Den Schwingungsvorgang kann man wie folgt modellieren:**

1) In der **Ruhelage** befindet sich das Feder-Masse-Pendel in einer Gleichgewichtslage, in der die Gewichtskraft und die Federkraft sich gerade ausgleichen. Das Pendel steht still.

2) Zieht man jetzt an der Feder nach unten, so dehnt man die Feder und speichert **Spannenergie** in der Feder: $E_{Spann} = \frac{1}{2} D s^2$. 

3) Da jetzt die Rückstellkraft größer als die Gewichtskraft ist, wird die Feder nach oben beschleunigt mit $F = m \cdot a$ und die Spannenergie wird in **Bewegungsenergie** $E_{kin} = \frac{1}{2} m v^2$ umgewandelt. 

4) Mit zunehmender Höhe wird die Bewegung durch die Gewichtskraft gebremst und die Bewegungsenergie wird in **Lageenergie** $E_{Pot} = m g h$ umgewandelt. Jetzt überwiegt wieder die Gewichtskraft der Masse und das Pendel wird nach unten beschleunigt.

5) Dieser Vorgang wiederholt sich solange, bis die Reibung die Bewegungsenergie in Wärmeenergie umgewandelt hat. Dann wird das Pendel wieder in seiner **Ruhelage** ruhen. 

In der weiteren Betrachtung werden zur Vereinfachung alle Reibungskräfte vernachlässigt.

**Damit kann man die Formel wie folgt herleiten:**

Die Geschwindigkeit ist die Änderung des Weges während die Zeit vergeht. Ist diese Änderung konstant gilt: $v = \cfrac{\Delta y}{\Delta t}$ ($y$ = zurückgelegter Weg in $y$-Richtung). Beim Feder-Masse-Pendel ändert sich der Weg aber nicht konstant.

Für einen Weg, die sich nicht konstant ändert, gilt zu einem Zeitpunkt $t$: $v(t) = \cfrac{dy}{dt} = y'(t)$, also ist die Geschwindigkeit die zeitliche Ableitung des Weges.

Die Beschleunigung ist die Änderung der Geschwindigkeit. Ist die Änderung der Geschwindigkeit konstant, kann man wieder schreiben: $a = \cfrac{\Delta v}{\Delta t}$.

Bei nicht konstanter Beschleunigung gilt für die Beschleunigung zum Zeitpunkt $t$: $a(t) = \cfrac{dv}{dt} = v'(t)$.

Also gilt insgesamt: 

$$
a(t) = v'(t) = \cfrac{dv}{dt} = \cfrac{d\frac{dy}{dt}}{dt} = y''(t)
$$

wobei hier gesetzt wird, dass die Bewegung immer in der Ruhelage mit $v(0) = 0$ zum Zeitpunkt $t = 0$ beginnt.

!!! In Worten:    
!!! **Die Beschleunigung zu einem Zeitpunkt $t$ ist die Änderung der Änderung des Weges zu diesem Zeitpunkt**.

Im Gleichgewichtsfall ist die Gewichtskraft im Gleichgewicht mit der Rückstellkraft der Feder:

$$
\begin{align}
F_G &= F_R\\
m \cdot g &= D \cdot y_0\\
y_0 &= \cfrac{m \cdot g}{D}
\end{align}
$$

Lenkt man die Feder aus der Ruhelage aus, indem man sie spannt, gilt für die resultierende Kraft (dabei ist die Gewichtskraft der rückstellenden Federkraft entgegengesetzt gerichtet):

$$
\begin{align}
F_{res}(t) &= F_R(t) - F_G\\
 &= D (y_0-y(t)) - m \, g\\
 &= D \left(\cfrac{m \cdot g}{D} - y(t) \right) - m \, g\\
 &= m \, g - D \, y(t) - m \, g\\
 &= - D \, y(t)
\end{align}
$$

Für die resultierende Kraft, welche für die Beschleunigung der Masse verantwortlich ist, gilt also: 

$$
F_{res}(t) = - D \, y(t)
$$

Für die beschleunigende Kraft gilt damit 

$$
F_B(t) = F_{res}(t)
$$ 

und folglich 

$$
m \cdot a(t) = - D \cdot y(t)
$$

Hier ändert sich die rückstellende Kraft ständig, weswegen die Beschleunigung der Masse und der Ort, an dem sich die Masse befindet, abhängig von der Zeit ständig ändern. Man muss also für die Beschleunigung und den Ort eine Funktion suchen, die sich abhängig von der Zeit ändert und den physikalischen Vorgang der periodischen Auf- und Abbewegung richtig beschreibt. 

Anstelle der Beschleunigungsfunktion setzt man jetzt die zweite Ableitung der Ortsfunktion ein.

$$
\begin{align}
m \cdot y''(t) &= - D \cdot y(t) \\
y''(t) &= - \cfrac{D}{m} \cdot y(t)
\end{align}
$$

Das ist eine Differentialgleichung in der eine Funktion $y(t)$ und deren 2. Ableitung $y''(t)$ enthalten sind. Jetzt soll versucht werden eine Funktion zu erraten, welche diese Gleichung löst. Man sucht also eine Funktion, die zwei mal abgleitet identisch mit sich selbst mal einem Vorfaktor von $\frac{D}{m}$ ist!

Die Mathematik kennt eine Funktion, deren 2. Ableitung fast mit der ursprünglichen übereinstimmt: 

$$
sin''(x) = - sin(x)
$$

Das negative Vorzeichen wird von der zweiten Ableitung der sin-Funktion bereitgestellt. Die Kettenregel liefert die innere Ableitung als Produkt. Wenn man darüber nachdenkt, dass ein Faktor zwei Mal mit sich selbst multipliziert $\frac{D}{m}$ sein soll, dann fällt auf, dass das die Wurzel aus dem Ausdruck leistet:

$$
\sqrt{\frac{D}{m}} \cdot \sqrt{\frac{D}{m}} = \frac{D}{m}
$$

Damit wurde eine geeignete Funktion konstruiert: 

$$
y(t) = sin \left(\sqrt{\frac{D}{m}} \cdot t \right)
$$

Begründung:

$$
\begin{align}
y(t) &= sin \left(\sqrt{\cfrac{D}{m}} \cdot t \right)\\
y'(t) &= \sqrt{\cfrac{D}{m}} cos \left(\sqrt{\cfrac{D}{m}} \cdot t \right)\\
y''(t) &= \sqrt{\cfrac{D}{m}} \cdot \sqrt{\cfrac{D}{m}} \left( -sin \left(\sqrt{\cfrac{D}{m}} \cdot t \right) \right) = - \cfrac{D}{m} \cdot sin \left(\sqrt{\cfrac{D}{m}} \cdot t \right) = - \cfrac{D}{m} \cdot y(t)
\end{align}
$$

Die Funktion $y(t) = sin \left(\sqrt{\frac{D}{m}} \cdot t \right)$ löst die Gleichung und eignet sich also zur Beschreibung des Schwingungsvorgangs des Feder-Masse-Pendels.

Die Schwingung wiederholt sich nach einer Periode, also nachdem jede Position bei einer Auf- und Abbewegung genau einmal erreicht wurde. Die Masse erreicht z.B. die Ruhelage aus der gleichen Richtung kommend wieder. Die dafür benötigte Zeit ist die **Periodendauer $T$**.

Die gefundene Funktion ist eine sin-Funktion von der man weiß, dass deren Funktionswerte sich im Gradmaß alle $360°$ und im Bogenmaß alle $2 \pi$ wiederholen, also $sin(0) = sin(2 \pi)$.

Zum Zeitpunkt $t = 0$ gilt $sin(0) = 0$. Nach einer vollständigen Periode gilt dann $sin(2 \pi ) = 0$ also 

$$
\sqrt{\cfrac{D}{m}} \cdot t = 2 \pi
$$

Die Zeit für eine vollständige Periode ist die Periodendauer $T$, also $t = T$ und somit folgt insgesamt:

$T = \sqrt{\cfrac{m}{D}} \cdot 2 \pi \:\:\:$ oder $ \:\:\: T = 2 \pi \cdot \sqrt{\cfrac{m}{D}}$

**Die Formel ist damit erfolgreich begründet hergeleitet worden.**

---