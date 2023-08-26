---
title: 常用线性代数公式
index_img: /img/pages/LinearAlgebraFormulas.jpeg
tags: [线性代数, MathJax]
categories:
- [学习, 线性代数]
--- 

![来自：Bing 的 AI 创建（ Prompt： 2个矩阵相乘 ）](/img/pages/LinearAlgebraFormulas.jpeg)

#### 矩阵变换

$$
\left[ \begin{matrix}
a & b \\\\ c & d
\end{matrix} \right]
\left[ \begin{matrix}
x \\\\
y
\end{matrix} \right] = x
\left[ \begin{matrix}
a \\\\
c
\end{matrix} \right] + y
\left[ \begin{matrix}
b \\\\
d
\end{matrix} \right] =
\left[ \begin{matrix}
a x + b y \\\\
c x + d y
\end{matrix} \right]
$$

#### 加法（Addition）

$$
A+B=B+A，(A+B)+C=A+(B+C)
$$

#### 数乘（Scalar multiplication）
$$
k(A+B)=kA+kB，(k+l)A=kA+lA1
$$

#### 乘法（Multiplication）
$$
A(B+C)=AB+AC，(AB)C=A(BC)
$$

#### 叉积

$$\mathbf {a} \times \mathbf {b} = \begin{vmatrix}\mathbf {i} &\mathbf {j} &\mathbf {k} \\\\ a_{1}&a_{2}&a_{3} \\\\b_{1}&b_{2}&b_{3} \end{vmatrix}$$


#### 行列式（Determinant）
##### **二阶矩阵的行列式**
$$
det\begin{pmatrix}
a & b \\\\
c & d
\end{pmatrix} = 
\begin{vmatrix}
a & b \\\\
c & d
\end{vmatrix} = ad - bc
$$

##### **三阶矩阵的行列式**
$$
\begin{vmatrix}
a & b & c \\\\
d & e & f \\\\
g & h & i
\end{vmatrix} = a (ei - fh) - b (di - fg) + c (dh - eg)
$$

##### **拉普拉斯展开定理**
对一个 $n$ 阶的行列式 $M$，去掉 $M$ 的第 $i$ 行第 $j$ 列后形成的 $n−1$ 阶的行列式叫做 $M$ 关于元素 ${\displaystyle m_{ij}}$ 的余因式。记作 $M_{ij}$

$$
M_{ij}={\begin{vmatrix}m_{1,1}&\dots &m_{1,j-1}&m_{1,j+1}&\dots &m_{1,n}\\\\ \vdots &&\vdots &\vdots &&\vdots \\\\ m_{i-1,1}&\dots &m_{i-1,j-1}&m_{i-1,j+1}&\dots &m_{i-1,n}\\\\ m_{i+1,1}&\dots &m_{i+1,j-1}&m_{i+1,j+1}&\dots &m_{i+1,n}\\\\ \vdots &&\vdots &\vdots &&\vdots \\\\ m_{n,1}&\dots &m_{n,j-1}&m_{n,j+1}&\dots &m_{n,n} \end{vmatrix}}
$$

$M$ 关于元素 ${\displaystyle m_{ij}}$ 的代数余子式记作 $C_{ij}$。$C_{ij}=(-1)^{(i+j)}\cdot M_{ij}$

一个 $n$ 阶的行列式 $M$ 可以写成一行（或一列）的元素与对应的代数余子式的乘积之和，叫作行列式按一行（或一列）的展开。

$$
\det {M} = \sum_{i=1}^{n}m_{i;j}C_{i,j}
$$

$$
\det {M} = \sum_{j=1}^{n}m_{i;j}C_{i,j}
$$

#### 转置（Transpose）

$$
(\mathbf A + \mathbf B)^T = \mathbf A^T + \mathbf B^T
$$

$$
(\mathbf A \mathbf B)^T = \mathbf B^T \mathbf A^T
$$

#### 逆（Inverse）
$$
(\mathbf A \mathbf B)^{-1} = \mathbf B^{-1} \mathbf A^{-1}
$$

$$
(\mathbf A^T)^{-1} = (\mathbf A^{-1})^T
$$

