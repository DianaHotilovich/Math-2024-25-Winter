## Przykłady obliczania pochodnych

### Przykład 1  
**Funkcja:**  
$y(x) = -3x + 3$  

**Reguła:**  
Pochodna funkcji liniowej:  
$$ \frac{d}{dx}[ax + b] = a $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = -3 $$  

---

### Przykład 2  
**Funkcja:**  
$y(x) = \pi x + \sin(1)$  

**Reguła:**  
Pochodna funkcji liniowej i stałej:  
$$ \frac{d}{dx}[ax + b] = a $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = \pi $$  

---

### Przykład 3  
**Funkcja:**  
$y(x) = 4 + \sin(2)$  

**Reguła:**  
Pochodna stałej:  
$$ \frac{d}{dx}[C] = 0 $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = 0 $$  

---

### Przykład 4  
**Funkcja:**  
$y(x) = 2x^3 - 3x^2 + 8x - 9$  

**Reguła:**  
Pochodna funkcji potęgowej:  
$$ \frac{d}{dx}[x^n] = n \cdot x^{n-1} $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = 6x^2 - 6x + 8 $$  

---

### Przykład 5  
**Funkcja:**  
$y(x) = 6x^{1/3}$  

**Reguła:**  
Pochodna funkcji potęgowej:  
$$ \frac{d}{dx}[x^n] = n \cdot x^{n-1} $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = 2x^{-2/3} = \frac{2}{\sqrt[3]{x^2}} $$  

---

### Przykład 6  
**Funkcja:**  
$y(x) = \sqrt{x}$  

**Reguła:**  
Pochodna pierwiastka:  
$$ \frac{d}{dx}[\sqrt{x}] = \frac{1}{2\sqrt{x}} $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = \frac{1}{2\sqrt{x}} $$  

---

### Przykład 7  
**Funkcja:**  
$y(x) = \cos(x) + \sin(x)$  

**Reguła:**  
Pochodne funkcji trygonometrycznych:  
$$ \frac{d}{dx}[\sin(x)] = \cos(x), \quad \frac{d}{dx}[\cos(x)] = -\sin(x) $$  

**Rozwiązanie:**  
$$ \frac{dy}{dx} = -\sin(x) + \cos(x) $$  

---

### Przykład 8  
**Funkcja:**  
$y(x) = 2\sin(x)\cos(x)$  

**Reguła:**  
Pochodna iloczynu dwóch funkcji (reguła Leibniza):  
$$ \frac{d}{dx}[u \cdot v] = u'v + uv' $$  

**Rozwiązanie:**  
Niech $u = 2\sin(x)$, $v = \cos(x)$:  
$$ \frac{du}{dx} = 2\cos(x), \quad \frac{dv}{dx} = -\sin(x) $$  
$$ \frac{dy}{dx} = 2\cos(x)\cos(x) + 2\sin(x)(-\sin(x)) $$  
$$ \frac{dy}{dx} = 2\cos^2(x) - 2\sin^2(x) $$  

---

### Przykład 9  
**Funkcja:**  
$y(x) = x\sin(x)$  

**Reguła:**  
Pochodna iloczynu dwóch funkcji (reguła Leibniza):  
$$ \frac{d}{dx}[u \cdot v] = u'v + uv' $$  

**Rozwiązanie:**  
Niech $u = x$, $v = \sin(x)$:  
$$ \frac{du}{dx} = 1, \quad \frac{dv}{dx} = \cos(x) $$  
$$ \frac{dy}{dx} = 1 \cdot \sin(x) + x \cdot \cos(x) $$  
$$ \frac{dy}{dx} = \sin(x) + x\cos(x) $$  

---

### Przykład 10  
**Funkcja:**  
$y(x) = (x+1)(x+1)$  

**Reguła:**  
Pochodna iloczynu dwóch funkcji:  
$$ \frac{d}{dx}[u \cdot v] = u'v + uv' $$  

**Rozwiązanie:**  
Niech $u = (x+1)$, $v = (x+1)$:  
$$ \frac{du}{dx} = 1, \quad \frac{dv}{dx} = 1 $$  
$$ \frac{dy}{dx} = 1 \cdot (x+1) + (x+1) \cdot 1 $$  
$$ \frac{dy}{dx} = 2(x+1) $$  

---

### Przykład 11  
**Funkcja:**  
$y(x) = \frac{x}{x+1}$  

**Reguła:**  
Pochodna funkcji ułamkowej:  
$$ \frac{d}{dx}\left(\frac{f(x)}{g(x)}\right) = \frac{f'(x)g(x) - f(x)g'(x)}{g^2(x)} $$  

**Rozwiązanie:**  
Niech $f(x) = x$, $g(x) = x+1$:  
$$ f'(x) = 1, \quad g'(x) = 1 $$  
$$ \frac{dy}{dx} = \frac{1 \cdot (x+1) - x \cdot 1}{(x+1)^2} $$  
$$ \frac{dy}{dx} = \frac{1}{(x+1)^2} $$  

## Obliczanie pochodnych dla podanych funkcji

### Przykład 12  
**Funkcja:**  
$y(x) = (x+1)\exp(x)$  

**Reguła:**  
Pochodna iloczynu funkcji (reguła Leibniza):  
$$ \frac{d}{dx}[u \cdot v] = u'v + uv' $$  

**Rozwiązanie:**  
Niech $u = (x+1)$, $v = \exp(x)$:  
$$ \frac{du}{dx} = 1, \quad \frac{dv}{dx} = \exp(x) $$  
$$ \frac{dy}{dx} = 1 \cdot \exp(x) + (x+1) \cdot \exp(x) $$  
$$ \frac{dy}{dx} = \exp(x)(x+2) $$  

---

### Przykład 13  
**Funkcja:**  
$y(x) = \sin(x^2)$  

**Reguła:**  
Pochodna funkcji złożonej:  
$$ \frac{d}{dx}[\sin(u)] = \cos(u) \cdot \frac{du}{dx} $$  

**Rozwiązanie:**  
Niech $u = x^2$, wtedy $\frac{du}{dx} = 2x$:  
$$ \frac{dy}{dx} = \cos(x^2) \cdot 2x $$  
$$ \frac{dy}{dx} = 2x\cos(x^2) $$  

---

### Przykład 14  
**Funkcja:**  
$y(x) = \exp(-2x)$  

**Reguła:**  
Pochodna funkcji wykładniczej:  
$$ \frac{d}{dx}[\exp(u)] = \exp(u) \cdot \frac{du}{dx} $$  

**Rozwiązание:**  
Niech $u = -2x$, wtedy $\frac{du}{dx} = -2$:  
$$ \frac{dy}{dx} = \exp(-2x) \cdot (-2) $$  
$$ \frac{dy}{dx} = -2\exp(-2x) $$  

---

### Przykład 15  
**Funkcja:**  
$y(x) = \frac{1}{\sin(x+1)}$  

**Reguła:**  
Pochodna funkcji ułamkowej:  
$$ \frac{d}{dx}\left(\frac{1}{f(x)}\right) = -\frac{f'(x)}{[f(x)]^2} $$  

**Rozwiązanie:**  
Niech $f(x) = \sin(x+1)$, wtedy:  
$$ \frac{d}{dx}[f(x)] = \cos(x+1) \cdot 1 = \cos(x+1) $$  
$$ \frac{dy}{dx} = -\frac{\cos(x+1)}{\sin^2(x+1)} $$  

---

### Przykład 16  
**Funkcja:**  
$y(x) = \sqrt{2x+1}$  

**Reguła:**  
Pochodna funkcji pierwiastkowej:  
$$ \frac{d}{dx}[\sqrt{f(x)}] = \frac{1}{2\sqrt{f(x)}} \cdot f'(x) $$  

**Rozwiązanie:**  
Niech $f(x) = 2x+1$, wtedy $\frac{d}{dx}[f(x)] = 2$:  
$$ \frac{dy}{dx} = \frac{1}{2\sqrt{2x+1}} \cdot 2 $$  
$$ \frac{dy}{dx} = \frac{2}{2\sqrt{2x+1}} $$  
$$ \frac{dy}{dx} = \frac{1}{\sqrt{2x+1}} $$

***№2***

## Dowód:  
Należy udowodnić, że:  

$$
\frac{d}{dx} (\ln(\sin(x))) = \cot(x)
$$  

---

### Rozwiązanie  

#### 1. Stosujemy regułę łańcuchową  
Używamy reguły różniczkowania funkcji złożonych. Zgodnie z regułą łańcuchową:  

Jeżeli \( y = \ln(f(x)) \), to  

$$
\frac{dy}{dx} = \frac{1}{f(x)} \cdot \frac{d}{dx}[f(x)]
$$  

W naszym przypadku \( f(x) = \sin(x) \). Wtedy:  

$$
\frac{d}{dx} [\ln(\sin(x))] = \frac{1}{\sin(x)} \cdot \frac{d}{dx} [\sin(x)]
$$  

---

#### 2. Obliczamy pochodną funkcji \( \sin(x) \)  
Pochodna funkcji \( \sin(x) \) względem \( x \) wynosi:  

$$
\frac{d}{dx} [\sin(x)] = \cos(x)
$$  

---

#### 3. Podstawiamy do wzoru  
Podstawiając obliczoną pochodną do reguły łańcuchowej, otrzymujemy:  

$$
\frac{d}{dx} [\ln(\sin(x))] = \frac{1}{\sin(x)} \cdot \cos(x)
$$  

Uprościmy wyrażenie:  

$$
\frac{\cos(x)}{\sin(x)} = \cot(x)
$$  

---

### Odpowiedź:  

W związku z tym:  

$$
\frac{d}{dx} (\ln(\sin(x))) = \cot(x)
$$


***№3***

## Sprawdzenie drugiej pochodnej:

Dana funkcja: \( f(x) = \cos(x) \). Należy sprawdzić, czy \( f''(x) = -f(x) \).



### Krok 1: Obliczamy pierwszą pochodną \( f'(x) \)

Zgodnie z podstawowymi wzorami różniczkowania funkcji cosinus:

$$
f'(x) = \frac{d}{dx} [\cos(x)] = -\sin(x).
$$



### Krok 2: Obliczamy drugą pochodną \( f''(x) \)

Teraz różniczkujemy pierwszą pochodną:

$$
f''(x) = \frac{d}{dx} [-\sin(x)] = -\cos(x).
$$



### Krok 3: Sprawdzanie równości

Zauważamy, że:

$$
f(x) = \cos(x).
$$

Dlatego:

$$
f''(x) = -\cos(x) = -f(x).
$$

***№4***
## Oblicz nieoznaczony granicę, stosując regułę de L'Hospitala

Obliczmy granicę:

$$
\lim_{x \to 0} \frac{\sin(x)}{x}.
$$


### Krok 1: Sprawdzanie formy

Gdy \( x \to 0 \):

- \( \sin(x) \to 0 \),
- \( x \to 0 \).

Wyrażenie ma formę \( \frac{0}{0} \), dlatego można zastosować **regułę de L'Hospitala**.


### Krok 2: Stosujemy regułę de L'Hospitala

Reguła de L'Hospitala mówi:

Jeśli granica wyrażenia ma formę \( \frac{0}{0} \) lub \( \frac{\pm\infty}{\pm\infty} \), to:

$$
\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)},
$$

gdzie \( f(x) \) i \( g(x) \) to funkcje, a \( f'(x), g'(x) \) to ich pochodne.

W naszym przypadku:

- \( f(x) = \sin(x) \),
- \( g(x) = x \).

Obliczamy pochodne:

1. Pochodna licznika:

   $$
   f'(x) = \cos(x).
   $$

2. Pochodna mianownika:

   $$
   g'(x) = 1.
   $$

Stosujemy teraz regułę de L'Hospitala:

$$
\lim_{x \to 0} \frac{\sin(x)}{x} = \lim_{x \to 0} \frac{\cos(x)}{1}.
$$



### Krok 3: Obliczamy granicę

Obliczamy teraz:

$$
\lim_{x \to 0} \cos(x).
$$

Funkcja \( \cos(x) \) jest ciągła, a gdy \( x \to 0 \):

$$
\cos(0) = 1.
$$

W związku z tym:

$$
\lim_{x \to 0} \cos(x) = 1.
$$



### Ostateczna odpowiedź:

Ostatecznie:

$$
\lim_{x \to 0} \frac{\sin(x)}{x} = 1.
$$

---

## Rozwiązanie zadania po polsku

Obliczamy granicę:

$$
\lim_{x \to \infty} \frac{\ln(x)}{x}.
$$

do tego celu zastosujemy **twierdzenie de L'Hospitala**.



### Krok 1: Sprawdzanie formy

Gdy \( x \to \infty \):

- \( \ln(x) \to \infty \),
- \( x \to \infty \).

Wyrażenie ma formę \( \frac{\infty}{\infty} \), dlatego możemy zastosować **twierdzenie de L'Hospitala**.



### Krok 2: Stosowanie twierdzenia de L'Hospitala

**Twierdzenie de L'Hospitala** mówi:

Jeżeli wyrażenie ma formę \( \frac{\infty}{\infty} \) lub \( \frac{0}{0} \), to:

$$
\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)},
$$

gdzie \( f(x) \) i \( g(x) \) to funkcje, a \( f'(x), g'(x) \) to ich pochodne.

W naszym przypadku:

- \( f(x) = \ln(x) \),
- \( g(x) = x \).

Obliczamy ich pochodne:

1. Pochodna licznika \( f(x) = \ln(x) \):

   $$
   f'(x) = \frac{1}{x}.
   $$

2. Pochodna mianownika \( g(x) = x \):

   $$
   g'(x) = 1.
   $$

Stosujemy twierdzenie de L'Hospitala:

$$
\lim_{x \to \infty} \frac{\ln(x)}{x} = \lim_{x \to \infty} \frac{\frac{1}{x}}{1} = \lim_{x \to \infty} \frac{1}{x}.
$$



### Krok 3: Obliczenie granicy

Teraz obliczamy:

$$
\lim_{x \to \infty} \frac{1}{x}.
$$

Gdy \( x \to \infty \), wyrażenie \( \frac{1}{x} \to 0 \).



### Odpowiedź końcowa:

W związku z tym:

$$
\lim_{x \to \infty} \frac{\ln(x)}{x} = 0.
$$


## Rozwiązanie zadania z użyciem reguły de L'Hospitala

Obliczamy granicę:

$$
\lim_{x \to \infty} \frac{\exp(x)}{x}.
$$


### Krok 1: Sprawdzanie formy

Gdy \( x \to \infty \):

- \( \exp(x) \to \infty \),
- \( x \to \infty \).

Wyrażenie przyjmuje formę \( \frac{\infty}{\infty} \), dlatego można zastosować **regułę de L'Hospitala**.



### Krok 2: Stosowanie reguły de L'Hospitala

**Reguła de L'Hospitala** mówi, że jeśli wyrażenie przyjmuje formę \( \frac{\infty}{\infty} \) lub \( \frac{0}{0} \), to:

$$
\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)},
$$

gdzie \( f(x) \) i \( g(x) \) to funkcje, a \( f'(x) \), \( g'(x) \) są ich pochodnymi.

W naszym przypadku:

- \( f(x) = \exp(x) \),
- \( g(x) = x \).

Obliczamy pochodne:

1. Pochodna licznika \( f(x) = \exp(x) \):

   $$
   f'(x) = \exp(x).
   $$

2. Pochodna mianownika \( g(x) = x \):

   $$
   g'(x) = 1.
   $$

Stosujemy regułę de L'Hospitala:

$$
\lim_{x \to \infty} \frac{\exp(x)}{x} = \lim_{x \to \infty} \frac{\exp(x)}{1} = \lim_{x \to \infty} \exp(x).
$$



### Krok 3: Obliczamy granicę

Funkcja \( \exp(x) \) (funkcja wykładnicza) rośnie w sposób ścisły dla \( x \to \infty \), co oznacza, że:

$$
\lim_{x \to \infty} \exp(x) = \infty.
$$



### Odpowiedź:

W związku z tym:

$$
\lim_{x \to \infty} \frac{\exp(x)}{x} = \infty.
$$

***№5***

Dane: położenie cząstki opisane jest funkcją:  

$$
x(t) = 3t^2 - 6t + 1.
$$  

Należy znaleźć:  
1. **Prędkość cząstki**, \( V(t) = x'(t) \), czyli pierwszą pochodną funkcji \( x(t) \),  
2. **Przyspieszenie cząstki**, \( a(t) = V'(t) = x''(t) \), czyli drugą pochodną funkcji \( x(t) \),  
   oraz obliczyć te wartości w chwili \( t = 2 \).



### Rozwiązanie:

#### 1. Znajdźmy prędkość \( V(t) = x'(t) \)

Najpierw znajdźmy pierwszą pochodną funkcji \( x(t) \):

$$
x(t) = 3t^2 - 6t + 1.
$$

Pochodna względem zmiennej \( t \):

$$
x'(t) = \frac{d}{dt}[3t^2 - 6t + 1].
$$

Stosujemy standardowe zasady różniczkowania:

$$
\frac{d}{dt}[3t^2] = 6t, \quad \frac{d}{dt}[-6t] = -6, \quad \frac{d}{dt}[1] = 0.
$$

Zatem:

$$
V(t) = x'(t) = 6t - 6.
$$

Teraz obliczamy \( V(2) \):

$$
V(2) = 6(2) - 6 = 12 - 6 = 6.
$$



#### 2. Znajdźmy przyspieszenie \( a(t) = x''(t) \)

Teraz znajdźmy drugą pochodną \( x''(t) \):

$$
x''(t) = \frac{d}{dt}[x'(t)] = \frac{d}{dt}[6t - 6].
$$

Pochodna względem \( t \):

$$
\frac{d}{dt}[6t] = 6, \quad \frac{d}{dt}[-6] = 0.
$$

Zatem:

$$
x''(t) = 6.
$$

Oznacza to, że przyspieszenie \( a(t) \) nie zależy od czasu i zawsze wynosi \( 6 \).

Teraz obliczamy \( a(2) \):

$$
a(2) = 6.
$$



### Odpowiedź:

1. Prędkość w chwili \( t = 2 \):  
   $$
   V(2) = 6
   $$

2. Przyspieszenie w chwili \( t = 2 \):  
   $$
   a(2) = 6
   $$