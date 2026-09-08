---
comments: true
tags: ["1 семестр"]
---

## Преобразования 1 рода

!!! abstract "Определение"
    Преобразованием 1 рода называют умножение какой либо строки матрицы на число $\lambda$, не равное нулю

    $$
    \begin{pmatrix}
    a_{11} & a_{12} & a_{13} \\
    a_{21} & a_{22} & a_{23} \\
    a_{31} & a_{32} & a_{33} \\
    \end{pmatrix}
    \sim
    \begin{pmatrix}
    a_{11} & a_{12} & a_{13} \\
    a_{21}\times \lambda & a_{22}\times \lambda & a_{23}\times \lambda \\
    a_{31} & a_{32} & a_{33} \\
    \end{pmatrix}
    $$

## Преобразования 2 рода

!!! abstract "Определение"
    Преобразованием 2 рода называют операцию при которой к одной строке (или столбцу) матрицы прибавляется другая строка (или столбец), умноженная на некоторое число $\lambda$. Остальные строки при этом не меняются

    $$
    \begin{pmatrix}
    a_{11} & a_{12} & a_{13} \\
    a_{21} & a_{22} & a_{23} \\
    a_{31} & a_{32} & a_{33} \\
    \end{pmatrix} \\
    \sim \\
    \begin{pmatrix}
    a_{11} & a_{12} & a_{13} \\
    a_{21} + a_{11} \times \lambda & a_{22} + a_{12} \times \lambda & a_{23} + a_{13} \times \lambda \\
    a_{31} & a_{32} & a_{33} \\
    \end{pmatrix}
    $$

## Преобразования 3 рода

!!! abstract "Определение"
    Преобразованием 3 рода называют перестановку 2-х строк матрицы местами

    $$
    \begin{pmatrix}
    \textcolor{red}{a_{11}} & \textcolor{red}{a_{12}} & \textcolor{red}{a_{13}} \\
    \textcolor{blue}{a_{21}} & \textcolor{blue}{a_{22}} & \textcolor{blue}{a_{23}} \\
    a_{31} & a_{32} & a_{33} \\
    \end{pmatrix}
    \sim
    \begin{pmatrix}
    \textcolor{blue}{a_{21}} & \textcolor{blue}{a_{22}} & \textcolor{blue}{a_{23}} \\
    \textcolor{red}{a_{11}} & \textcolor{red}{a_{12}} & \textcolor{red}{a_{13}} \\
    a_{31} & a_{32} & a_{33} \\
    \end{pmatrix}
    $$
