
# Combinatoria [OK]


## Numero Combinatorio 

Cantidad de forma de elegir k elementos de un total de n elementos:
$$\binom{n}{k} = \frac{n!}{k!(n-k)!}$$




## Binomio de Newton


$$(a+b)^{n} = \sum_{k=0}^{n} \binom{n}{k}a^{k}b^{n-k}, \forall n \in \mathbb{N_{0}}$$




## Anagramas 

La __cantidad de anagramas__ que se pueden formar de una palabra:

$$\frac{ cantidadTotalLetras! }{repeticiones!}$$


cantidad de anagramas de _PALABRA_:

$$P A_{1} L A_{2} B R A_{3}$$
$$\frac{7!}{3!}$$

cantidad de anagramas de _HELICOPTERO_:

$$H E_{1} L I C O_{1} P T E_{2} R O_{2}$$
$$\frac{11!}{2!2!}$$

## Combinatoria de Funciones



## Funciones (repaso):

sea $f : A \rightarrow B$

* __Funciones Inyectivas__: 
  * $\# A \leq  \# B$
  * $\forall a,b \in A, f(a)=f(b) \Rightarrow a = b$
  * $\forall a,b \in A, f(a) \neq f(b) \Rightarrow a \neq b$



* __Funciones Sobreyectivas__ : 
  * $\# A \geq \# B$
  * $\forall b \in B, \exist  a \in A : f(a)=b \Rightarrow im(f)= \forall B$



* __Funciones Biyectivas__ : 
   * $\# A = \# B$
   * $\forall a,b \in A, f(a)=f(b) \Rightarrow a = b$
   * $\forall b \in B, \exist  a \in A : f(a)=b \Rightarrow im(f)= \forall B$


## Cantidad de Relaciones

Sea $f$ una funcion $f:A\rightarrow B, \ \ A=\{a_{1},...a_{m} \} \  y  \ B=\{b_{1},...a_{n}\}$
donde   $\#A = m \wedge \ \# B = m$  

Entonces la __cantidad de relaciones__ que hay de $A_{n} \ en \ B_{m}$ es:
$$2^{n.m}$$ 



### Cantidad de Funciones



La __cantidad total__ de funciones  $f : A_{n} \rightarrow B_{m}$ que hay: 
$$\# B^{\# A}  = m^{n}$$

<br>

* #### Funciones Inyectivas:

Sea $n \leq m$: 
La cantidad de __funciones inyectivas__ $f : A_{n} \rightarrow B_{m}$ que hay:



$$\binom{m}{n}n! = \frac{m!}{(m-n)!}$$


<br>

  * #### Funciones Sobreyectivas:

La cantidad de __funciones biyectivas__ $f : A_{n} \rightarrow B_{m}$ que hay:
  
si ${m > n}$ :


$$\sum_{k=0}^{n}(-1)^{k}(n-k)^{m}$$


si ${m < n}$ :
$$
 (n)^{m}
$$

si ${m = n}$ :
$$
 n!
$$
**nota**: observar si $m=n$ el unico caso posible es que las funciones sean __inyectivas__ y __biyectivas__.


