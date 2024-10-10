
# Congruencia

## Ecuaciones de congruencias

* $a \equiv b \pmod{m}$
* $k.a \equiv k.a \pmod{b} \Leftrightarrow k \perp b$
* $ka \equiv kb \pmod{km} \Leftrightarrow a \equiv b \pmod{m}$
* $a^{n} \equiv 0 \pmod{p} \Leftrightarrow a \equiv 0 \pmod{p}$


* $n \equiv x_{0} \pmod{m} \Leftrightarrow \begin{cases} n \equiv x_{1} \pmod{p_{0}} \\ n \equiv x_{2} \pmod{p_{1}} \\ ... \\ n \equiv x_{m} \pmod{p_{n}} \end{cases}$



* $ax \equiv b \pmod{m} \text{  } \Rightarrow \text{  } ax + my = b \text{  } \stackrel{\text{tiene solucion}}{\Leftrightarrow} (a : m) | b$


### Ecuaciones Diofanticas

Sea $\ ax + by = c \stackrel{\text{tiene solucion}}{\Leftrightarrow} (a : b) | c$

$\Rightarrow ax + bx =  c \stackrel{\text{coprimizar}}{\Leftrightarrow} \frac{a}{(a:b)}x + \frac{b}{(a:b)}x = \frac{c}{(a:b)} \stackrel{\text{}}{\Leftrightarrow} a{'}x + b{'}x =  c{'}$


busco solucion particular: 

$a{'}x + b{'}x =  c{'} \text{ } \Rightarrow \text{ } a{'}(s) + b{'}(t) =  c{'}$

$\Rightarrow s_{0} = (x_{0},y_{0})=(s,t)$


busco solucion general:

$(a,b) = k(b{'},-a{'})+(x_{0},y_{0}) = ({b'}k + x_{0},-{a'}k + y_{0})$



### TCR

sean $a \perp b \perp c$

$\begin{cases} n \equiv x_{1} \pmod{a} \\ n \equiv x_{2} \pmod{b} \\ n \equiv x_{3} \pmod{c}  \end{cases}$

por TCR $\exists! \ solucion \ x_{0} : n \equiv  x_{0} \pmod{a.b.c}$

### PTF 

Sea $p \text{ primo } \land p \not | a$ :

* $a^{p} \equiv a \pmod{p}$
* $a^{p-1} \equiv 1 \pmod{p}$
* $a^{n} \equiv a^{r_{p-1}n} \pmod{p}$


