
# Conjuntos [OK]

### Cojunto de Partes

$P(A)=\{ X :  \subset A \} \lor x \in P(A)$ 


### Operaciones entre conjuntos :



__Complemento__ :

Sea $A \subseteq U$

$A^{c} = \{ x \in U : x \not\in A \}$

__propiedades__ :

* $\empty ^{c} = U$
* $U^{c} = \empty$
* $(A^{c})^{c}=A$


__Union__: 

$\text{Sea }  A,B \subseteq U$

$A \cup B = \{ x \in U : x \in A \lor x \in B \}$

__propiedades__ :

* $A \cup \empty$
* $A \cup U = U$
* $A \in B = B \in A$
* $A \in B = U$ 

__Interseccion__: 

$\text{Sea }  A,B \subseteq U$

$A \cup B = \{ x \in U : x \in A \lor x \in B \}$

__propiedades__ :

* $A \cap B = B \cap A$
* $A \cap U = A$
* $A \cap \empty = \empty$
* $A \cap A^{c} = \empty$
* conjuntos disjuntos :
    * $A \in B = \empty$


__diferencia__ :

Sea $A,B \subseteq U$

$A-B = \{ x \in U : x \in A \land X \not\in B  \}$

__propiedades__ :

* $A-B \neq B-A$
* $A - \empty = A$
* $A - \empty = A$
* $A^{c} = U - A$
* $A-A^{c}=A$
* $A-A= \empty$


__diferencia simetrica__ :

Sea $A,B \subseteq U$

$A-B = \{ x \in U : x \in A \land X \not\in B  \}$


### Propiedades Importantes:

__conmutativa__ :  $\begin{cases} A \cup B  = B \cup A \\  A \cap B = B \cap A \end{cases}$

__asociativa__ :  $\begin{cases} A \cup (B \cup C)  = (A \cup B)  \cup C \\A \cap (B \cap C)  = (A \cap B)  \cup C \end{cases}$ * __las exp tiene la misma operacion__


__Idempotencia__: $\begin{cases} A \cup A  = A \\ A \cap A  = A  \end{cases}$

__Elem neutro__ : $\begin{cases} A \cup \varnothing  = A \\ A \cap \varnothing = \varnothing \end{cases}$

__distributiva__ : $\begin{cases}  A \cup (B \cap C)  = (A \cup B) \cap (A \cup C)  \\ A \cap (B \cup C)  = (A \cap B) \cup (A \cap C) \end{cases}$ * __las exp tiene la distintas operaciones__

__ley de absorcion__ : $\begin{cases} A \cup (A \cap B) = A \\ A \cap (A \cup B) = A \end{cases}$

__ley de absorcion II__ : $\begin{cases} A^{c} \cup (A \cap B) = A^{c} \cup B \\ A^{c} \cap (A \cup B) = A^{c} \cap B \end{cases}$ * __caso especial__

__ley de morgan__ : $\begin{cases} (A \cup B)^{c} = A^{c} \cap B^{c} \\  (A \cap B)^{c} = A^{c} \cup B^{c} \end{cases}$

* $A-B= A \cap B^{C}$

* $A \Delta B = (A \cup B) - (A \cap B) \\ A \Delta B  = (A-B) \cup (B-A) \\  A \Delta B  =  (A \cap B^{c}) \cup (B \cap A^{c})$
