## Komplex számok, polinomok
### 1 | Algebrai alak
*Definició:* \
A $z$ komplex szám algebrai alakja a $z = x + i*y$, ahol $x, y \in \mathbb{R}$ és $i = \sqrt{-1}$. \
*( Az $x$ a komplex szám valós, $y$ a komplex szám képletes része. $Re(z) = x$ és $Im(z) = y$. )*

### 2 | Trigonometrikus alak
*Definició:* \
A $z$ komplex szám trigonometrikus alkja $z = r*(cos(\theta) + i*sin(\theta))$, ahol $r \geq 0$ az abszolút érték, $\theta \in [0,2\pi)$. 

### 3 | Exponenciális alak
*Definició:* \
Az Euler egyenlet alapján, $z$ komplex szám exponenciális alkja $z = r*e^{i*\theta}$, ahol $r \geq 0$ az abszolút érték, $\theta \in [0,2\pi)$. 

### 4 | Euler egyenlet
*Tétel:* \
$e^{i*\theta} = cos(\theta) + i*sin(\theta)$

### 5 | Műveletek komplex számokkal
#### 5.1 | Algebrai alakban
Legyen $z_1 = x_1 + i*y_1$ és $z_2 = x_2 + i*y_2$.

##### 5.1.1 | Összeadás és kivonás
$z_1 \plusmn z_2 = x_1 \plusmn x_2 + i * (y_1 \plusmn y_2)$.

##### 5.1.2 | Szorzás
$z_1 * z_2 = x_1 * x_2 + i * (y_1 * y_2)$.

##### 5.1.3 | Osztás
$\frac{z_1}{z_2} = \frac{z_1 * \overline{z_2}}{z_2 * \overline{z_2}} = \frac{(x_1 + i * y_1)(x_2 - i * y_2)}{(x_2 + i * y_2)(x_2 - i * y_2)}$

#### 5.2 | Trigonometrikus és exponenciális alakban
Legyen $z_1 = r_1*(cos(\theta_1) + i*sin(\theta_1))$ és $z_2 = r_2*(cos(\theta_2) + i*sin(\theta_2))$ és $n \in \mathbb{Z}^+ $.

##### 5.2.1 | Szorzás
$z_1 * z_2 = r_1*r_2*e^{i*(\theta_1 + \theta_2)}$

##### 5.1.3 | Osztás
$\frac{z_1}{z_2} = \frac{r_1}{r_2}* e^{i*(\theta_1 + \theta_2)}$

##### 5.1.3 | Hatványozás
$z_1^{n} = r ^ {n} * e ^ {i(n * \theta)}$

$\sqrt[n]{z}$
