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

> [!theorem]+ Теорема эквивалентности определений инфимума через $i'$ и $\varepsilon$
> Рассмотрим действительную прямую $\mathbb{R}$ и его подмножество $X$. Тогда определения инфимума являются эквивалентными. 
> $$\begin{gather*} \forall x \in X:  \Big( \left(x \geq i \right) \wedge \left(\forall i' > i \; \exists x \in X: i' > x \right) \Big) \Leftrightarrow \\ \Leftrightarrow \forall x \in X:  \Big( \left(x \geq i \right) \wedge \left(\forall \varepsilon > 0 \; \exists x \in X: x < s + \varepsilon \right) \Big) \Leftrightarrow \\ \Leftrightarrow i = \inf X\end{gather*}$$
> > [!proof]- Доказательство
> > 1. Докажем, что если число $i$ является инфимумом по $1$ определению, то оно также является пределом и по $2$ определению.
> > 	* Рассмотрим первое определение: $$i = \inf X \Leftrightarrow \forall x \in X:  \Big( \left(x \geq i \right) \wedge \left(\forall i' > i \; \exists x \in X: i' > x \right) \Big)$$
> > 	* Пусть $i'$ и $i$ связанны равенством $i' = i + \varepsilon$. Тогда определения равносильны: $$i = \inf X \Leftrightarrow \forall x \in X:  \Big( \left(x \geq i \right) \wedge \left(\forall \varepsilon > 0 \; \exists x \in X: x < s + \varepsilon \right) \Big)$$
> > 2. Докажем, что если число $i$ является инфимумом по $2$ определению, то оно также является пределом и по $1$ определению.
> > 	* Рассмотрим второе определение: $$i = \inf X \Leftrightarrow \forall x \in X:  \Big( \left(x \geq i \right) \wedge \left(\forall \varepsilon > 0 \; \exists x \in X: x < s + \varepsilon \right) \Big)$$
> > 	* Так как $\varepsilon$ - произвольное число, то пусть $i' = i + \varepsilon$. Тогда определения равносильны: $$i = \inf X \Leftrightarrow \forall x \in X:  \Big( \left(x \geq i \right) \wedge \left(\forall i' > i \; \exists x \in X: i' > x \right) \Big)$$
>  