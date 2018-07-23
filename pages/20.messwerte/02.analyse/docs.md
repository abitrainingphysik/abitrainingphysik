---
title: Analyse der Messtabelle
taxonomy:
    category: docs
---

---

Bevor Sie eine Regression durchführen können, müssen Sie zuerst eine geeignete **Regressionsmethode** auswählen. 

Dazu sollten Sie immer zuerst ein **Schaubild** auf Basis der gegebenen Messwerte anfertigen oder sich digital anzeigen lassen. Wenn Sie die **Form des Graphen** sehen, können Sie oft die richtige Methode vermuten. Bei manchen Funktionstypen haben die Messwerte auch Eigenschaften, die **rechnerisch überprüft** werden können. 

Wenn Sie sich für eine Regressionsmethode entschieden und diese durchgeführt haben, sollten Sie auf jeden Fall den **Graphen** der gefundenen Funktion **über die Messwerte legen**, um zu prüfen, ob der Graph der gefundenen Funktion zu den Messwerten passt. Falls die Abweichungen zu groß sind, sollten Sie die Regression mit einer anderen Methode wiederholen.

Im folgenden werden die **Funktionstypen** vorgestellt, die häufig im Physik-Abitur im Zusammenhang mit Messwertanalysen vorkommen. Prägen Sie sich die Form des Graphen und den dazugehörigen Funktionsterm ein, dann fällt Ihnen sie Entscheidung für eine geeignete Regressionsmethode leichter.

---

### Proportionalität

| Messtabelle | | | | | | | | |
|-------------------------------------------|
| x | 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 
| y | 11 | 23 | 32 | 42 | 55 | 67 | 76 | 89 |

Der Graph einer Proportionalität ist eine **Ursprungsgerade**.

![](analyse_01.svg?classes=caption "Abbildung 1")

!!!! **Funktionsterm:** $\:\:\: y = k \cdot x \:\:\:$

!!! **Rechnerisch überprüfbare Eigenschaft:**   
!!! Für eine Proportionalität gilt, dass der **Quotient** der Werte eines Wertepaars in guter Näherung **konstant** ist. Aus $\:\:\: y = k \cdot x \:\:\:$ folgt $\:\:\: k = \frac{y}{x} = const$. 


Überprüfung anhand der Messtabelle:

| Messtabelle | | | | | | | | |
|-------------------------------------------------------|
| x                 | 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 
| y                 | 11 | 23 | 32 | 42 | 55 | 67 | 76 | 89 |
| $k = \frac{y}{x}$ | 11 |11,5|10,7|10,5| 11 |11,2|10,9|11,1|

Der Wert von $k$ schwankt um $11$ und ist in guter Näherung konstant. 

!!! **Geeignete Regressionsmethode:**   
!!! **Lineare Regression** (Geogebra) bzw. **LinReg** (GTR) mit $y = a \cdot x + b$. 

Da die Zielfunktion eine Proportionalität sein soll, gehört der Ursprung $O(0/0)$ mit zu den Wertepaaren, die für die Regression berücksichtigt werden. Geogebra bzw. GTR liefert dann:

$$
y = 11,03 \cdot x -0,24
$$

Der y-Achsenabschnitt wird weggelassen, damit die Zielfunktion eine Proportionalität ist. Also gilt in guter Näherung:

$$
y = 11 \cdot x
$$

---

### Lineare Funktion

| Messtabelle | | | | | | | | | |
|----------------------------------------------------------|
| x | 0   | 0,5 | 1   | 1,5 | 2   | 2,5 | 3,0 | 3,5 | 4,0 |
| y |-1,54|-1,22|-0,91|-0,62|-0,38|-0,19| 0,11| 0,40| 0,72|

Der Graph einer linearen Funktion ist eine **Gerade**.

![](analyse_02.svg?classes=caption "Abbildung 2")

!!!! **Funktionsterm:** $\:\:\: y = k \cdot x + b\:\:\:$

!!! **Rechnerisch überprüfbare Eigenschaft:**  
!!! Für eine lineare Funktion gilt, dass der **Quotient** aus der Differenz zweier y-Werte und der Differenz zweier x-Werte in guter Näherung **konstant** ist: $\:\:\: y = k \cdot x + b \:\:\:$ mit $\:\:\: k = \frac{\Delta y}{\Delta x} = \frac{y_2 - y_1}{x_2 - x_1}$.

Überprüfung anhand von Werten aus der Messtabelle:

$$
\begin{align}
&k_1 = \frac{y_2 - y_1}{x_2 - x_1} = \frac{-1,22 - (-1,54)}{0,5 - 0} = 0,64 \\
&k_2 = \frac{-0,62 - (-1,22)}{1,5 - 0,5} = 0,6 \\
&k_3 = \frac{0,11 - (-0,91)}{3 - 1} = 0,51 \\
&k_4 = \frac{0,40 - (-1,22)}{3,5 - 0,5} = 0,54 \\
&k_4 = \frac{0,72 - (-0,19)}{4 - 2,5} = 0,61
\end{align}
$$

Der Wert von $k$ schwankt um $0,55$ und ist in guter Näherung konstant. 

!!! **Geeignete Regressionsmethode:**   
!!! **Lineare Regression** (Geogebra) bzw. **LinReg** (GTR) mit $y = a \cdot x + b$. 

Geogebra bzw. GTR liefert:

$$
y = 0,55 \cdot x -1,49
$$

---

### Antiproportionalität

| Messtabelle | | | | | | | | | |
|---------------------------------------------------------------------|
| x | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 
| y | 9,8 | 4,8 | 3,2 | 2,5 | 2,0 | 1,6 | 1,4 | 1,3 | 1,1 |

Der Graph einer Antiproportionalität ist eine **Hyperbel**.

![](analyse_03.svg?classes=caption "Abbildung 3")

!!!! **Funktionsterm:** $\:\:\: y = k \cdot \frac{1}{x}$

!!! **Rechnerisch überprüfbare Eigenschaft:**    
!!! Für eine Antiproportionalität gilt, dass das **Produkt** der Werte eines Wertepaars in guter Näherung **konstant** ist: $\:\:\: y = k \cdot \frac{1}{x} \:\:\:$ also $\:\:\: k = y \cdot x$.

Überprüfung anhand der Messtabelle:

| Messtabelle | | | | | | | | | |
|---------------------------------------------------------------------|
| x               | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 
| y               | 9,8 | 4,8 | 3,2 | 2,5 | 2,0 | 1,6 | 1,4 | 1,3 | 1,1 |
| $k = y \cdot x$ | 9,8 | 9,6 | 9,6 | 10,0| 10,0| 9,6 | 9,8 | 10,4| 9,9 | 

Der Wert von $k$ schwankt um $9,8$ und ist in guter Näherung konstant. Wegen 

$$
y = k \cdot \frac{1}{x} = k \cdot x^{-1}
$$

kann eine Antiproportionalität als Potenzfunktion mit dem Exponenten $-1$ aufgefasst werden.

!!! **Geeignete Regressionsmethode:**   
!!! **Potenz-Regression** (Geogebra) bzw. **PwrReg** (GTR) mit $\:\:\: y = a \cdot x^b$.

Geogebra bzw. GTR liefert:

$$
y = 9,64 \cdot x^{-0,98}
$$

Da eine Antiproportionalität modelliert werden soll, setzt man den Exponenten gleich $-1$. Also gilt in guter Näherung:

$$
y = 9,64 \cdot x^{-1} = 9,64 \cdot \frac{1}{x}
$$

---

### Potenzfunktion

| Messtabelle | | | | | | | | | |
|------------------------------------------------|
| x |100 |180 |205 |255 |290 |510 |580 |820 |910 | 
| y | 86 | 65 | 60 | 54 | 50 | 38 | 36 | 30 | 29 |

Der Graph einer **Potenzfunktion** kann vielfältig aussehen. Ein Beispiel ist folgende Potenzfunktion, die auf den ersten Blick aussieht, wie eine Antiproportionalität.

![](analyse_04.svg?classes=caption "Abbildung 4")

!!!! **Funktionsterm:** $\:\:\: y = k \cdot x^b$

!!! **Geeignete Regressionsmethode:**  
!!! **Potenz-Regression** (Geogebra) bzw. **PwrReg** (GTR) mit $\:\:\: y = a \cdot x^b$.

Geogebra bzw. GTR liefert:

$$
y = 849,38 \cdot x^{-0,5}
$$

$x^{-0,5}$ kann geschrieben werden als $\frac{1}{\sqrt{x}}$ also folgt:

$$
y = 849,38 \cdot \frac{1}{\sqrt{x}}
$$

Neben diesem Beispiel können Potenzfunktionen auch z.B. Parabeln oder Wurzelfunktionen sein.

---

### Parabelfunktion

Die **Parabelfunktion** ist eine Variation der Potenzfunktion.

| Messtabelle | | | | | | | | | |
|------------------------------------------------|
| x |10 |15 |20 |25 |30  |35  |40  |45  |50  | 
| y |135|305|538|840|1219|1651|2163|2735|3378|

![](analyse_08.svg?classes=caption "Abbildung 8")

!!!! **Funktionsterm:** $\:\:\: y = k \cdot x^b$

!!! **Geeignete Regressionsmethode:**  
!!! **Potenz-Regression** (Geogebra) bzw. **PwrReg** (GTR) mit $\:\:\: y = a \cdot x^b$.

Geogebra bzw. GTR liefert:

$$
y = 1,35 \cdot x^2
$$

---

### Wurzelfunktion

Die **Wurzelfunktion** ist eine Variation der Potenzfunktion.

| Messtabelle | | | | | | | | | |
|------------------------------------------------|
| x |100|180|205|255|290|510|580|820|910 | 
| y |345|463|491|550|588|780|830|985|1040|

![](analyse_05.svg?classes=caption "Abbildung 5")

!!!! **Funktionsterm:** $\:\:\: y = k \cdot x^b$

!!! **Geeignete Regressionsmethode:**  
!!! **Potenz-Regression** (Geogebra) bzw. **PwrReg** (GTR) mit $\:\:\: y = a \cdot x^b$.

Geogebra bzw. GTR liefert:

$$
y = 34,47 \cdot x^{0,5}
$$

$x^{0,5}$ kann geschrieben werden als $\sqrt{x}$ also folgt:

$$
y = 34,47 \cdot \sqrt{x}
$$

---

### Exponentielle Abnahme

Ein erstes Erkennungsmerkmal für eine exponentielle Abnahme ist, dass der Graph im Gegensatz zu den Hyperbeln einen Schnittpunkt mit der y-Achse (**Anfangsbestand**) besitzt.

| Messtabelle | | | | | | | | | | |
|---------------------------------------------------------------------|
| x | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 
| y | 19,6| 9,8 | 4,9 | 2,4 | 1,3 | 0,6 | 0,3 | 0,16| 0,07| 0,04|

![](analyse_06.svg?classes=caption "Abbildung 6")

!!!! **Funktionsterm:** $\:\:\: y = k \cdot b^x$

!!! **Rechnerisch überprüfbare Eigenschaft:**   
!!! Die **exponentielle Abnahme** hat die Eigenschaft, dass sich der Bestand in gleichen Intervallen um den gleichen Anteil verringert. 

Rechnerische Überprüfung der exponentiellen Abnahme:

Intervall $[0;1]$: $\frac{9,8}{19,6} = 0,5 = 50 \%$  
Intervall $[2;3]$: $\frac{2,4}{4,9} = 0,49 = 49 \%$  
Intervall $[6;7]$: $\frac{0,16}{0,3} = 0,53 = 53 \%$  
...

In jedem Intervall der Breite $1$ verringert sich der Bestand um etwa 50%.

!!! **Geeignete Regressionsmethode:**   
!!! **Wachstum-Regression** (Geogebra) bzw. **ExpReg** (GTR) mit $\:\:\: y = a \cdot b^x$

Geogebra bzw. GTR liefert:

$$
y = 19,64 \cdot 0,5^x
$$

Wenn für die **Basis** der Exponentialfunktion gilt: $0 < b < 1$, dann liegt eine **exponentielle Abnahme** vor.

---

### Exponentielle Zunahme

| Messtabelle | | | | | | | | | | |
|---------------------------------------------------------------------|
| x | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 
| y | 2,0 | 2,8 | 3,9 | 5,5 | 7,7 | 10,7| 15,0| 21,1| 29,5| 41,3|

![](analyse_07.svg?classes=caption "Abbildung 7")

!!!! **Funktionsterm:** $\:\:\: y = k \cdot b^x$

!!! **Rechnerisch überprüfbare Eigenschaft:**   
!!! Die **exponentielle Zunahme** hat die Eigenschaft, dass sich der Bestand in gleichen Intervallen um den gleichen Anteil vergrößert. 

Intervall $[0;1]$: $\frac{2,8}{2} = 1,40 = 140 \%$  
Intervall $[2;3]$: $\frac{5,5}{3,9} = 1,41 = 141 \%$  
Intervall $[6;7]$: $\frac{21,1}{15,0} = 1,41 = 141 \%$  
...

In jedem Intervall der Breite $1$ vergrößert sich der Bestand um etwa 40%.

!!! **Geeignete Regressionsmethode:**   
!!! **Wachstum-Regression** (Geogebra) bzw. **ExpReg** (GTR) mit $\:\:\: y = a \cdot b^x$

Geogebra bzw. GTR liefert:

$$
y = 2 \cdot 1,4^x
$$

Wenn für die **Basis** der Exponentialfunktion gilt: $b > 1$, dann liegt eine **exponentielle Zunahme** vor.

---
