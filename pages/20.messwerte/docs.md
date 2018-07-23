---
title: Messwerte
taxonomy:
    category: docs
---

Bei der Durchführung von Experimenten sammelt man **Messwerte**. Auf der Grundlage dieser Messwerte versucht man **Vorhersagen** für zukünftige Experimente ableiten zu können. Diese Vorhersagen sind dann leicht möglich, wenn man die Messwerte mit Hilfe einer **mathematischen Formel** angenähert darstellen kann. Die Suche nach einer geeigneten Funktion nennt man **Regression**. 

Im Abitur gibt es immer wieder Aufgaben, bei denen Sie zu einer Messtabelle eine Funktion finden sollen, durch welche die Messwerte angenähert berechnet werden können. 

! ##### **Beispiel:**
!
! Ein **Auto** fährt auf einer geraden, ebenen Strecke. Mit Hilfe eines Zeitmesseinrichtung (z.B. Stoppuhr) und einer Längenmesseinrichtung (z.B. Laserentfernungsmesser) wird zu bestimmten Zeitpunkten seine Position gemessen. Dabei notiert man folgende **Messwerte**:
!
! | Messtabelle | | | | | | | | |
! |-------------------------------------------------------|
! | Zeit $t$ in s | 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 
! | Ort $s$ in m  | 11 | 23 | 32 | 42 | 55 | 67 | 76 | 89 |
!
! **Stellen** Sie diese Messwerte **grafisch dar**.
!
! **Ermitteln** Sie aus den Messwerten der Tabelle den zwischen $s$ und $t$ bestehenden funktionalen Zusammenhang $s(t)$. Dokumentieren Sie Ihre Vorgehensweise.

---

#### **Grafische Darstellung der Messwerte**

![](messwerte_01.svg?classes=caption "Abbildung 1")

---

#### **Funktionaler Zusammenhang**

Die grafische Darstellung der Messwerte lässt einen linearen Zusammenhang vermuten, also wird als Regressionsmethode die **lineare Regression** gewählt.

Um die lineare Regression durchzuführen, werden die Werte für die Zeit $t$ als **unabhängige Werte** und die Werte für die Strecke $s$ als von der Zeit $t$ **abhängige Werte** gewählt. Die lineare Regression z.B. mit dem GTR liefert:

$$
y = 11,06 \cdot x - 0,39
$$

---

#### **Physikalisierung des funktionalen Zusammenhangs**

Als **y-Achsenabschnitt** liefert die lineare Regression $-0,39$. Das macht physikalisch keinen Sinn, da zum Zeitpunkt $t = 0 \: s$ die Messung des Wegs bei $s = 0 \: m$ beginnt. Das Wertepaar $t = 0 \: s$ und $s(0) = 0 \: m$ wird also in die Messtabelle aufgenommen und die Regression damit nochmals durchgeführt.

| Messtabelle | | | | | | | | | |
|------------------------------------------------------------|
| Zeit $t$ in s | 0  | 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 
| Ort $s$ in m  | 0  | 11 | 23 | 32 | 42 | 55 | 67 | 76 | 89 |

Mit diesen Werten liefert die lineare Regression folgenden Funktionsterm:

$$
y = 10,93 \cdot x
$$

Für $y$ setzt man jetzt die Strecke $s$ in Abhängigkeit von $t$ und für $x$ setzt man die Zeit $t$. Damit lässt sich der Funktionsterm wie folgt schreiben:

$$
s(t) = 10,93 \cdot t
$$

Auf der linken Seite hat der Weg $s(t)$ die physikalische Einheit $m$ (Meter). Rechts wird für $t$ als Einheit $s$ (Sekunden) eingesetzt. Das passt noch nicht. Als bekommt die Steigung die Einheit $\frac{m}{s}$, so dass sich Sekunden kürzen und Meter als Einheit bleibt. Diese Wahl macht Sinn, denn die Steigung im Zeit-Weg-Diagramm entspricht der Geschwindigkeit $v$, welche die Einheit $\frac{m}{s}$ hat.

Also beschreibt folgende Gleichung den Zusammenhang zwischen der Zeit $t$ und der zurückgelegten Strecke $s$ bei den vorliegenden Messwerten in guter Näherung:

$$
s(t) = 10,93 \tfrac{m}{s} \cdot t
$$

---

!!! Nicht immer lassen sich Messwerte durch eine solch einfache Formel mathematisch beschreiben. Oft sehen die Formeln deutlich komplizierter aus. **In diesem Kapitel** wird gezeigt, wie Messwerte richtig dargestellt werden, wie man die richtige **Regressionsmethode** wählt, die **Physikalisierung** der mathematischen Formel gelingt und wie man mit Messunsicherheiten umgeht.