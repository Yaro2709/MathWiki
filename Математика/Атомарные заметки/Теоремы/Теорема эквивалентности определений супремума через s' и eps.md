> [!info]
> Тэги: #Теорема #Топология  
> 
> Использует: *-*
> Примеры: *-*
> 
> Ссылки: *-*
> 
> Эквивалентности: *-*
> Обобщения: *-*

> [!theorem]+ Теорема эквивалентности определений супремума через $s'$ и $\varepsilon$
> Рассмотрим действительную прямую $\mathbb{R}$ и его подмножество $X$. Тогда определения супремума являются эквивалентными. 
> 
> $$\begin{gather*} \forall x \in X:  \Big( \left(x \leq s \right) \wedge \left(\forall s' < s \; \exists x \in X: s' < x \right) \Big) \Leftrightarrow \\ \Leftrightarrow \forall x \in X:  \Big( \left(x \leq s \right) \wedge \left(\forall \varepsilon > 0 \; \exists x \in X: x > s - \varepsilon \right) \Big) \Leftrightarrow \\ \Leftrightarrow s = \sup X \end{gather*}$$
> 
> > [!proof]- Доказательство
> > 1. Докажем, что если число $s$ является супремумом по $1$ определению, то оно также является пределом и по $2$ определению.
> > 	* Рассмотрим первое определение: $$s = \sup X \Leftrightarrow \forall x \in X:  \Big( \left(x \leq s \right) \wedge \left(\forall s' < s \; \exists x \in X: s' < x \right) \Big)$$
> > 	* Пусть $s'$ и $s$ связанны равенством $s' = s - \varepsilon$. Тогда определения равносильны: $$s = \sup X \Leftrightarrow \forall x \in X:  \Big( \left(x \leq s \right) \wedge \left(\forall \varepsilon > 0 \; \exists x \in X: x > s - \varepsilon \right) \Big)$$
> > 2. Докажем, что если число $s$ является супремумом по $2$ определению, то оно также является пределом и по $1$ определению.
> > 	* Рассмотрим второе определение: $$s = \sup X \Leftrightarrow \forall x \in X:  \Big( \left(x \leq s \right) \wedge \left(\forall \varepsilon > 0 \; \exists x \in X: x > s - \varepsilon \right) \Big)$$
> > 	* Так как $\varepsilon$ - произвольное число, то пусть $s' = s - \varepsilon$. Тогда определения равносильны: $$s = \sup X \Leftrightarrow \forall x \in X:  \Big( \left(x \leq s \right) \wedge \left(\forall s' < s \; \exists x \in X: s' < x \right) \Big)$$
>  