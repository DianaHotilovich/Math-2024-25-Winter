# Znalezienie równania płaszczyzny przechodzącej przez trzy punkty

Dane są punkty \( A(1, 2, 3) \), \( B(3, 4, 5) \) oraz \( C(2, 1, 4) \). Chcemy znaleźć równanie płaszczyzny przechodzącej przez te punkty.

## 1. Wyznaczenie wektorów
Na podstawie punktów obliczamy dwa wektory:
$$
\vec{AB} = B - A = (3-1, 4-2, 5-3) = (2, 2, 2)
$$
$$
\vec{AC} = C - A = (2-1, 1-2, 4-3) = (1, -1, 1)
$$

## 2. Wektor normalny płaszczyzny
Obliczamy iloczyn wektorowy \( \vec{AB} \times \vec{AC} \), który jest wektorem normalnym do płaszczyzny:
$$
\vec{n} = \vec{AB} \times \vec{AC} =
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
2 & 2 & 2 \\
1 & -1 & 1 \\
\end{vmatrix}
$$

Rozwijamy wyznacznik:
$$
\vec{n} = \mathbf{i} \cdot (2 \cdot 1 - 2 \cdot (-1)) - \mathbf{j} \cdot (2 \cdot 1 - 2 \cdot 1) + \mathbf{k} \cdot (2 \cdot (-1) - 2 \cdot 1)
$$
$$
\vec{n} = \mathbf{i} \cdot 4 - \mathbf{j} \cdot 0 + \mathbf{k} \cdot (-4)
$$
$$
\vec{n} = (4, 0, -4)
$$

## 3. Równanie płaszczyzny
Równanie płaszczyzny ma postać:
$$
n_1(x - x_0) + n_2(y - y_0) + n_3(z - z_0) = 0
$$
gdzie \( (x_0, y_0, z_0) \) to dowolny punkt należący do płaszczyzny (np. \( A(1, 2, 3) \)), a \( \vec{n} = (4, 0, -4) \).

Podstawiając wartości:
$$
4(x - 1) + 0(y - 2) - 4(z - 3) = 0
$$
$$
4x - 4 - 4z + 12 = 0
$$
$$
4x - 4z + 8 = 0
$$
Dzieląc przez 4:
$$
x - z + 2 = 0
$$

## Ostateczne równanie płaszczyzny
$$
x - z + 2 = 0
$$
