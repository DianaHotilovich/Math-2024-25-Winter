## Limits of Sequences

1. Calculate:
   - $\displaystyle \lim_{n \to \infty} \frac{n^2 + 3n}{2 n^2 - 2n}$

   - $\displaystyle \lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1}$

2. Prove using the squeeze theorem:
   - $\displaystyle\lim_{n \to \infty} \frac{\sin(n)}{n}$

4. Find the limit of the sequence:
   - $a_n = (1+\frac{1}{n})^n$

---

### **№1**
## Rozwiązanie zadania

Obliczmy granicę:

$\lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n}$.



### Krok 1: Podzielmy licznik i mianownik przez $n^2$

Dzielimy licznik i mianownik przez $n^2$:

$\frac{n^2 + 3n}{2n^2 - 2n} = \frac{\frac{n^2}{n^2} + \frac{3n}{n^2}}{\frac{2n^2}{n^2} - \frac{2n}{n^2}}$.

Obliczamy poszczególne elementy:

$\frac{n^2}{n^2} = 1, \quad \frac{3n}{n^2} = \frac{3}{n}, \quad \frac{2n^2}{n^2} = 2, \quad \frac{2n}{n^2} = \frac{2}{n}$.

Otrzymujemy:

$\frac{n^2 + 3n}{2n^2 - 2n} = \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}}$.



### Krok 2: Obliczamy granicę, gdy $n \to \infty$

Analizujemy granicę, gdy $n \to \infty$:

- $\frac{3}{n} \to 0$,
- $\frac{2}{n} \to 0$.

Otrzymujemy:

$\lim_{n \to \infty} \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}} = \frac{1}{2}$.


### Odpowiedź:

$\lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n} = \frac{1}{2}$.


---


- $$\lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1}$$

### Rozwiązanie:

1. **Rozwiń licznik:**

   Licznik można rozwinąć za pomocą wzoru na sześcian sumy:

   $$ (2n+3)^3 = 8n^3 + 36n^2 + 54n + 27 $$

2. **Rozważmy ułamek:**

   Teraz nasz ułamek wygląda tak:

   $$ \frac{8n^3 + 36n^2 + 54n + 27}{n^3 - 1} $$

3. **Podzielmy licznik i mianownik przez $n^3$:**

   Podzielimy zarówno licznik, jak i mianownik przez $n^3$:

   $$ \frac{\frac{8n^3}{n^3} + \frac{36n^2}{n^3} + \frac{54n}{n^3} + \frac{27}{n^3}}{\frac{n^3}{n^3} - \frac{1}{n^3}} $$

4. **Uprośćmy ułamek:**

   Po podzieleniu otrzymujemy:

   $$ \frac{8 + \frac{36}{n} + \frac{54}{n^2} + \frac{27}{n^3}}{1 - \frac{1}{n^3}} $$

5. **Obliczamy granicę, gdy $n \to \infty$:**

   Gdy $n \to \infty$:

   - $\frac{36}{n} \to 0$,
   - $\frac{54}{n^2} \to 0$,
   - $\frac{27}{n^3} \to 0$,
   - $\frac{1}{n^3} \to 0$.

   Dlatego granica przybiera postać:

   $$ \frac{8}{1} = 8 $$

### Odpowiedź:

- $$\lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1} = 8$$

---
***№2***
Prove using the squeeze theorem:
- $\displaystyle\lim_{n \to \infty} \frac{\sin(n)}{n}$

## Dowód za pomocą twierdzenia ściskania

Należy udowodnić, że:  

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$  

z wykorzystaniem **twierdzenia ściskania (Squeeze Theorem)**.



### 1. Własności funkcji \( \sin(n) \)

Funkcja $ \sin(n) $ jest ograniczona w całej swojej dziedzinie za pomocą następującej nierówności:  

$$
-1 \leq \sin(n) \leq 1
$$

Ta nierówność będzie podstawą do zastosowania twierdzenia ściskania.



### 2. Ustalanie nierówności

Teraz z własności $ -1 \leq \sin(n) \leq 1 $ uzyskujemy:  

$$
-1 \leq \sin(n) \leq 1
$$

Dzielimy teraz wszystkie człony przez $ n > 0 $:

$$
-\frac{1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}
$$



### 3. Zastosowanie twierdzenia ściskania

Teraz mamy nierówność:

$$
-\frac{1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}
$$

Obliczamy teraz granice krańców dla \( n \to \infty \):

- **Lewy kraniec:**  

$$
\lim_{n \to \infty} -\frac{1}{n} = 0
$$

- **Prawy kraniec:**  

$$
\lim_{n \to \infty} \frac{1}{n} = 0
$$



### 4. Wniosek

Z twierdzenia ściskania wynika, że jeśli funkcja jest ściskana między dwiema innymi funkcjami, które zbliżają się do tego samego granicy, to sama funkcja również musi zbliżać się do tego samego wyniku.  

W związku z tym:  

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$



### Odpowiedź:

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$



***№3***

Find the limit of the sequence:
   - $a_n = (1+\frac{1}{n})^n$


## Rozwiązanie:

1. **Krok 1: Przypomnijmy definicję liczby matematycznej $ e $:**

   Liczba \( e \) (przybliżona wartość to \( 2,718 \)) jest definiowana za pomocą następującej granicy:

   $$
   e = \lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n
   $$

2. **Krok 2: Porównanie zadania z definicją liczby $ e $:**

   Nasze zadanie jest przedstawione w następującej formie:

   $$
   a_n = \left(1 + \frac{1}{n}\right)^n
   $$

   To wyrażenie jest dokładnie równoważne definicji liczby $ e $.

3. **Krok 3: Wniosek:**

   Na podstawie tego można stwierdzić, że:

   $$
   \lim_{n \to \infty} a_n = e
   $$

---

## Odpowiedź:

Granica danej sekwencji jest równa:

$$
\lim_{n \to \infty} a_n = e
$$