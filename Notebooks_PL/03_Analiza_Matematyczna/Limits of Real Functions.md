## Limits of Real Functions

1. Compute:
   - $\displaystyle\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}$

2. Find:
   
   - $\displaystyle \lim_{x \to 0} \frac{\sin(3x)}{2x+1}$.

3. Find the asymptotes of the function:
  
   - $f(x) = \frac{x^2 - 1}{x^2 + 1}$
   - $g(x) = \frac{\sin(x)}{x^2+1}$

***№1***

Aby obliczyć:

$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}
$$

### Rozwiązanie 

1. **Zidentyfikować stopnie licznika i mianownika:**
   - Licznik: $ x^3 + 2x^2 $ (stopień = 3),
   - Mianownik: $ x^4 - 3x^3 $ (stopień = 4).

   Ponieważ stopień licznika jest mniejszy niż stopień mianownika, granica powinna zmierzać do 0.

2. **Podzielić licznik i mianownik przez najwyższą potęgę $ x $ w mianowniku $ x^4 $:**

   Przekształć wyrażenie:

   $$
   \frac{x^3 + 2x^2}{x^4 - 3x^3} = \frac{\frac{x^3}{x^4} + \frac{2x^2}{x^4}}{1 - \frac{3x^3}{x^4}}.
   $$

   Upraszczając poszczególne wyrażenia:

   $$
   \frac{x^3 + 2x^2}{x^4 - 3x^3} = \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}}.
   $$

3. **Obliczyć granicę dla $ x \to \infty $:**

   Gdy $ x \to \infty $:
   - $ \frac{1}{x} \to 0 $,
   - $ \frac{2}{x^2} \to 0 $,
   - $ \frac{3}{x} \to 0 $.

   Podstawiając te wartości do wyrażenia:

   $$
   \lim_{x \to \infty} \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}} = \frac{0 + 0}{1 - 0} = 0.
   $$

### Wynik

Granica wynosi:

$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3} = 0.
$$

***№2***

Znajdź granicę:
$$
\lim_{x \to 0} \frac{\sin(3x)}{2x + 1}.
$$

### Rozwiązanie

#### Analiza zachowania licznika i mianownika
- Licznik $\sin(3x)$ dąży do $\sin(0) = 0$, gdy $x \to 0$.
- Mianownik $2x + 1$ dąży do $1$, gdy $x \to 0$.

Zatem wyrażenie przyjmuje postać:
$$
\frac{0}{1}.
$$

#### Podstawienie

Podstawiając $x = 0$:
$$
\frac{\sin(3 \cdot 0)}{2 \cdot 0 + 1} = \frac{0}{1} = 0.
$$

### Odpowiedź końcowa
$$
\lim_{x \to 0} \frac{\sin(3x)}{2x + 1} = 0.
$$


***№3***
### Znajdź asymptoty funkcji $ f(x) = \frac{x^2 - 1}{x^2 + 1} $

#### 1. Asymptoty poziome
Asymptoty poziome ustalamy analizując granicę funkcji, gdy $ x \to \pm \infty $.

Dla funkcji:
$$
f(x) = \frac{x^2 - 1}{x^2 + 1},
$$
dzielimy licznik i mianownik przez \( x^2 \):
$$
f(x) = \frac{1 - \frac{1}{x^2}}{1 + \frac{1}{x^2}}.
$$

Gdy $ x \to \pm \infty $, człony z $ \frac{1}{x^2} \to 0 $. Dlatego:
$$
\lim_{x \to \pm \infty} f(x) = \frac{1 - 0}{1 + 0} = 1.
$$

W związku z tym, pozioma asymptota to:
$$
y = 1.
$$



#### 2. Asymptoty pionowe
Asymptoty pionowe występują tam, gdzie mianownik jest równy zero, a licznik nie jest równy zero. Можем заметить, что при подставлении любого числа результатк не будет давать ноль, поэтому у нас не будет вертикальных асимптот

Rozważmy mianownik $ x^2 + 1 = 0 $:
$$
x^2 = -1.
$$

Nie istnieją żadne rozwiązania tego równania w zbiorze liczb rzeczywistych. W związku z tym asymptoty pionowe **nie istnieją**.



#### 3. Asymptoty skośne
Ponieważ stopień licznika jest równy stopniowi mianownika, asymptoty skośne również **nie istnieją**. Это можно объяснить и другим способом, когда отдельно считаем k, потому что именно с помощью него будет понятно, есть ли у нас вертикальные асимптоты. Мы должны имеющееся выражение разделить на х, чтобы понять это. У нас в итоге получится $\frac{1}{x}$, а это значит, что в итоге выражение будет принимать вид $y = 0x + b$, что указывает на отсуствие вертикатикальных асимптот.
Można to wyjaśnić w inny sposób, obliczając oddzielnie $k$, ponieważ to właśnie dzięki niemu można zrozumieć, czy mamy do czynienia z asymptotami pionowymi. Musimy podzielić istniejące wyrażenie przez x, aby to zrozumieć. Ostatecznie otrzymamy $\frac{1}{x}$, co oznacza, że wyrażenie przyjmie postać $y = 0x + b$, co wskazuje na brak asymptot pionowych.



### Odpowiedź:
1. **Pozioma asymptota:** $ y = 1 $.  
2. **Asymptoty pionowe:** brak.  
3. **Asymptoty skośne:** brak.



## Znajdź asymptoty funkcji  

### Dana funkcja:  

$$
g(x) = \frac{\sin(x)}{x^2 + 1}
$$

---

## Rozwiązanie  

### 1. Asymptoty poziome  

Asymptoty poziome sprawdzamy, gdy $x \to \infty$ lub $x \to -\infty$:  

Obliczamy granicę:  

$$
\lim_{x \to \pm \infty} g(x) = \lim_{x \to \pm \infty} \frac{\sin(x)}{x^2 + 1}.
$$

#### Własności funkcji $\sin(x)$:  

Jest znane, że:  

$$
|\sin(x)| \leq 1 \text{ dla każdego } x.
$$

Zatem możemy napisać:  

$$
|g(x)| = \frac{-1}{x^2 + 1} \leq \left| \frac{\sin(x)}{x^2 + 1} \right| \leq \frac{1}{x^2 + 1}.
$$

#### Obliczamy granicę:  

Gdy $x \to \pm \infty$, mianownik $x^2 + 1 \to \infty$. Zatem:  

$$
\lim_{x \to \pm \infty} \frac{1}{x^2 + 1} = 0.
$$

#### Odpowiedź:  

W związku z tym:  

$$
\lim_{x \to \pm \infty} g(x) = 0.
$$

Oznacza to, że **pozioma asymptota** funkcji $g(x)$ to:  

$$
y = 0.
$$



### 2. Asymptoty pionowe  

Asymptoty pionowe występują, gdy mianownik dąży do $0$. Sprawdźmy mianownik:  

$$
x^2 + 1.
$$

Zauważamy, że:  

$$
x^2 + 1 > 0 \text{ dla każdego } x.
$$

Oznacza to, że mianownik **nigdy nie jest równy 0**, co oznacza brak asymptot pionowych.



### 3. Asymptoty ukośne  

Asymptoty ukośne pojawiają się, jeśli stopień licznika jest wyższy niż stopień mianownika. W naszym przypadku:  

- Licznik $\sin(x)$ **nie rośnie w nieskończoność**, ponieważ funkcja $\sin(x)$ jest ograniczona przedziałem od $-1$ do $1$.  
- Mianownik $x^2 + 1$ rośnie szybciej przy dużych wartościach $|x|$.

W związku z tym, asymptoty ukośne również nie występują.
Здесь применим то же самое, можем взять k и посчитать его, у нас выйдет $\frac{0}{1} = 0$



## Odpowiedź:  

1. **Asymptota pozioma:** $y = 0$ (dla $x \to \pm \infty$).  
2. **Asymptoty pionowe:** brak.  
3. **Asymptoty skośne:** brak.