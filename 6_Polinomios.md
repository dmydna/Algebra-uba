---
output: html_notebook
editor_options: 
  chunk_output_type: inline
---

# Polinomios [OK]


## <u>__Raices Multiples__</u>:

sea $f$ un polinomio cualquiera

$\ f \in \mathbb{K[X]} \ tiene \ raices \ multiples \Leftrightarrow \exists \alpha : {f(\alpha)=0} \wedge {f'(\alpha)=0}$

#### __Multiplicidad__ 

* ${f'}(x)=0 \Longrightarrow mult(x, f)=2 \Leftrightarrow$ ${f''(x)} \neq 0$
* ${f''}(x)=0 \Longrightarrow mult(x, f)=3 \Leftrightarrow$ ${f'''(x)} \neq 0$

En general : 
* ${f^m}(x)=0 \Longrightarrow mult(x, f)=m+1 \Leftrightarrow$ ${f^{m+1}(x)} \neq 0$

<br>

## <u>__MCD de Polinomios__</u>:

sean ${f,g}$ polinomios cualquieras

$\ f,g \in \mathbb{K[X]}$ 

* $(f:g)=d  \Rightarrow d | f  \wedge d | g$
* $(f:{f}^{'})=d  \Rightarrow d | {f}^{'} \wedge  d | f \Leftrightarrow d^{2}|f$ 
* $(f:{f}^{''})=d  \Rightarrow d | {f}^{''}  \wedge d | f \Leftrightarrow d^{3}|f$

En  general : 
* $(f:{f}^{n})=d  \Rightarrow d | {f}^{n} \wedge d | f \Leftrightarrow d^{n+1}|f$

#### __Raices y MCD__

sean ${f,g}$ polinomios cualquiera

$\ f,g \in \mathbb{K[X]}$
* $si \ \exists \alpha \in \mathbb{K} : f(\alpha)=0 \wedge g(\alpha)=0 \\ \Rightarrow (f:g)(\alpha)=0 \\ \Rightarrow (x-{\alpha})|(f:g)$

<br>


## <u>__Raices en__ $\mathbb{Q[X]}$ </u>:

sea ${f}$ un polinomio cualquiera

$f \in \mathbb{Q} \ con  \ a,b,c \in  \mathbb{Z}$ :
* $f(a + b \sqrt{c})=0 \Rightarrow  f(a-b\sqrt{c})=0$

* $(x - a + b\sqrt{c}) | f \Rightarrow (x - a - b\sqrt{c})|f$

<br>

   __Teorema de Gauss__:

$\ si \  \exists \alpha  \in \mathbb{Z} : f(\alpha) = 0 \Rightarrow \alpha \in \{ \frac{div(ci)}{div(cp)}\}$

<br>

## <u>__Raice en__ $\mathbb{C[X]}$</u> :

sea ${f}$ un polinomio cualquiera y un numero complejo $z$ 

$f \in \mathbb{C} \ con \ \  coeficientes \in  \mathbb{R}$  y $z \in \mathbb{C}$  :
* $f(z)=0 \rightarrow  f(\bar{z})=0$ 

* $(x-z)(x-\bar{z})= x^{2}-2Re(z)x+ \left | z \right |^{2}$

<br>



#### __Raices de la unidad__:

sea $w_{k}$ una __raiz n-esima__ de la unidad:
* $w_{k} = e^{\frac{2k\pi}{n}} \ \ , \ \ k \in \{ 1,2,...n-1 \}$

sea $w \in G_{n} \Rightarrow w^{n}=1$
*  $w^{k}=w^{r_{n}(k)}, k \in \mathbb{Z}$

__nota__: observar que $w_{k}$ es lo mismo que $w^{k}$ y que si $w \in G_{n}$ entonces es una raiz n-esima de unidad! 


## Polinomios en $\mathbb{Z} / {k}\mathbb{Z[X]}$


#### Polinomios cuadraticos:

sea $p$ un polinomio cualquiera talque $p \in \mathbb{Z} / {k}\mathbb{Z[X]}$ 

$p = ax^{2} + bx + c$ es __reducible__ en  $\mathbb{Z} / {k}\mathbb{Z[X]}$

$\Leftrightarrow  x = \frac{-b \pm \sqrt{ b^{2}-4ac }}{2a} \in \mathbb{Q}  \Leftrightarrow \sqrt{ b^{2}-4ac } \in \mathbb{Z} \Leftrightarrow \Delta \geq 0$

que es lo mismo que decir que el discriminante $\Delta =  b^{2}-4ac$  es un __cuadrado__  en $\mathbb{Z} / {k}\mathbb{Z[X]}$

#### Factorizacion de polinomios

sea $p \in \mathbb{Z} / {2}\mathbb{Z[X]}$ 

$p = x^{4} - 1$  y   $\mathbb{Z} / {5}\mathbb{Z[X]} = \{\bar{0},\bar{1},\bar{2},\bar{3},\bar{4} \}$

$busco \ \ \bar{k} \in \mathbb{Z} / {5}\mathbb{Z[X]} \Rightarrow p(\bar{k}) = \bar{0}$

$p(\bar{0}) = \bar{0}^{4} - 1 = \bar{4} \neq \bar{0}$ 
$p(\bar{1}) = \bar{1}^{4} - 1 = \bar{0}$
$p(\bar{2}) = \bar{2}^{4} - 1 = \bar{0}$
$p(\bar{3}) = \bar{3}^{4} - 1 = \bar{0}$
$p(\bar{4}) = \bar{4}^{4} - 1 = \bar{0}$

$\Rightarrow p = (x-\bar{1})(x-\bar{2})(x-\bar{3})(x-\bar{4})$

<br><br>

En general en $\mathbb{Z} / {k}\mathbb{Z[X]}$:

sea ${f}$ un polinomio cualquiera

* $busco \ \ \bar{a} \Rightarrow p(\bar{a}) = \bar{0}$ con $a \in \{\bar{0},..,\overline{k-1} \}$

$\Rightarrow f=(x- \bar{a_{0}})(x- \bar{a_{1}})...(x- \bar{a_{n}})$




