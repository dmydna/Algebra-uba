
# Numeros Complejos [Ok]


sea $z \in \mathbb{C} , a,b \in \mathbb{Z}$ :

$z=a+bi$ 

$Re(z)=a$
$Im(z)=b$

* __conjugado__ : $\bar{z}=a-bi$

* __modulo__ : $|z|=\sqrt{a^{2}+b^{2}}$

* __argumento__: $arg(z)=\theta \Leftrightarrow 0\leq \theta \leq 2 \pi$

* __inverso__ : $z^{-1} = \frac{\bar{z}}{|z|^{2}}$


### Argumento :

sea $\theta = Arg(z) \Rightarrow 0\leq \theta \leq 2 \pi$ 

$a = Re(z), b = Im(z)$ 

* $cos \theta = \frac{a}{|z|} \Rightarrow \theta = cos^{-1} (\frac{a}{|z|})$ 
* $sen \theta = \frac{b}{|z|} \Rightarrow \theta = sen^{-1} (\frac{b}{|z|})$ 

Sea $w,z \in \mathbb{C}$:

* $Arg(z^n)= n*Arg(z)$ 
* $Arg(z.w)= Arg(z)+Arg(w)$

### Operaciones

sea $z_{\alpha},w_{\theta} \in \mathbb{C} , a,b \in \mathbb{Z}$

$z=a+bi$ 
$w=c+di$ 

* __suma__ : $z+w = Re(z) + Re(z) + i( Im(z) + Im(w) )$ 

* __resta__ : $z-w = Re(z) - Re(z) - i( Im(z) - Im(w) )$ 

* __division__ : $\frac{z}{w} =\frac{|z|}{|w|} ( cos ( \alpha - \theta ) + isen ( \alpha - \theta ) )$ 

* __producto__ : ${z}*{w} ={|z|}*{|w|} ( cos ( \alpha + \theta ) + isen ( \alpha + \theta ) )$ 


### Forma de Moivre


sea $z = |z|e^{\theta i}$

* __division__ : $\frac{z}{w} =\frac{|z|}{|w|} |z|e^{(\alpha - \theta)i}$ 

* __producto__ : ${z}*{w} ={|z|}{|w|} e^{(\alpha + \theta)i}$ 

* __potencia__ : $z^{n} = |z|^{n} e^{ n(\theta)i }$


## Igualdad de Complejos:


sea $w_{\theta},z_{\alpha} \in \mathbb{C}, z=W$

$$ \Leftrightarrow
\begin{cases}
 |z| = |w|\\
 arg(z)= arg(w) \\ 
\end{cases}.
 \Leftrightarrow 
\begin{cases}
 |z| = |w|\\
 \alpha = \theta \\ 
\end{cases}$$


## Raices n-esimas:

sea $z_{\alpha} \in \mathbb{C}$ y sea $w_{\theta}$ una __raiz n-esima__ de $z$:

busco $w_{ \theta } \in \mathbb{C}: w^{n} = z$

$$\Leftrightarrow 
\begin{cases}
 |w|^{n} = |z|\\
 n*arg(w)= arg(z) \\
\end{cases}
 \Leftrightarrow 
\begin{cases}
 |w| = \sqrt[n]{|z|}\\
 \theta = \frac{ \alpha + 2k \pi}{n} \\ 
\end{cases}$$

<br>

$\Rightarrow w = w_{k} = \sqrt[n]{|z|} e^{\frac{ \theta + 2k \pi}{n}} \ con \ k \in \{ 0,..,n-1 \}$

#### __Raices de la unidad__:

sea $w_{k}$ una __raiz n-esima__ de la unidad:
* $w_{k} = e^{\frac{2k\pi}{n}} \ \ , \ \ k \in \{ 1,2,...n-1 \}$

sea $w \in G_{n} \Rightarrow w^{n}=1$
*  $w^{k}=w^{r_{n}(k)}, k \in \mathbb{Z}$

__nota__: observar que $w_{k}$ es lo mismo que $w^{k}$ y que si $w \in G_{n}$ entonces es una raiz n-esima de unidad! 



## Grupo $G_{n}$

Sea $w \in G_{n} \Rightarrow w^{n} = 1$

* $w \in G_{n} \Rightarrow w^{m} = w^{r_{n}m}$
* $w \in G_{n} \Rightarrow |w|=1$
* $w \in G_{n} \Rightarrow \bar{w} \in G_{n} \wedge \bar{w}=w^{-1}$
* $w \in G_{n} \Rightarrow \bar{w}=w^{-1}$

Sean $n,m \in \mathbb{N}$,

* $n|m \Rightarrow G_{n} \subset G_{m}.$
* $G_{n} \cap G_{m} = G_{(m:n)}.$
* $G_{n} \subset G_{m} \Leftrightarrow n|m$


## Propiedades importantes

sea $z \in \mathbb{C}$:

* $i^{2}=-1$
* $z. \bar{z} = |z|^{2}$
* $\bar{z} = z \Leftrightarrow z \in \mathbb{R}$
* $z + \bar{z} = 2Re(z)$
* $z - \bar{z} = 2Im(z)i$
* $|Re(z)| \leq |z|$
* $|Im(z)| \leq |z|$

sea $w,z \in \mathbb{C}$:

* $\overline{z+w} = \bar{z} + \bar{w}$  
* $\overline{z.w} = \bar{z} . \bar{w}$
* $si \ z \neq 0 \Rightarrow  \overline{z^{-1}} = \overline{z}^{-1}$
* $si \ z \neq 0 \Rightarrow  \overline{z^{k}} = \overline{z}^{k} ,\forall k \in \mathbb{Z}$

* $|{z+w}| \leq |{z}| + |{w}|$
* $|{z.w}| \leq |{z}| . |{w}|$
* $si \ z \neq 0 \Rightarrow  |z^{-1}| = |{z}|^{-1}$
* $si \ z \neq 0 \Rightarrow  |z^{k}| = |{z}|^{k} , \forall k \in \mathbb{Z}$

#

#### Tabla de sen & cos


|$\alpha$|$0$|$\frac{\pi}{6}$|$\frac{\pi}{4}$|$\frac{\pi}{3}$|$\frac{\pi}{2}$|
|--|--|--|--|--|--|
|sen $\alpha$|$\frac{ \sqrt{0} }{2}$|$\frac{ \sqrt{1} }{2}$|$\frac{ \sqrt{2} }{2}$|$\frac{ \sqrt{3} }{2}$|$\frac{ \sqrt{4} }{2}$|
|cos $\alpha$|$\frac{ \sqrt{4} }{2}$|$\frac{ \sqrt{3} }{2}$|$\frac{ \sqrt{2} }{2}$|$\frac{ \sqrt{1} }{2}$|$\frac{ \sqrt{0} }{2}$|



