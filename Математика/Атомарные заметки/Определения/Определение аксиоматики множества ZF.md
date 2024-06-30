> [!info]
> Тэги: #Определение #Теория_множеств 
> 
> Использует: [[Концепция множества]], [[Аксиомa объемности]], [[Аксиомa пустого множества]], [[Аксиомa пары]], [[Аксиомa объединения]], [[Аксиомa бесконечности]], [[Схема выделения]], [[Аксиомa множества подмножеств]], [[Схема подстановки]], [[Аксиомa основания]]
> Примеры: *-*
> 
> Типы: *-*
> Свойства: *-*
> Конструкции: *-*
> 
> Эквивалентности: *-*
> Обобщения: *-*

> [!definition]+ Определение аксиоматики множества $ZF$
> 1. **Аксиомы ZF**
> 	* $\text{I}_{1}: \forall a \forall b \ (\forall c \ (c \in a \Leftrightarrow c \in b) \Rightarrow a = b)$
> 	* $\text{I}_{2}:\exists e\colon \forall a \ (a \notin e)$
> 	* $\text{I}_{3}: \forall a \forall b \exists c \forall d \ \bigl(d \in c \Leftrightarrow (d = a \ \lor \ d = b)\bigr)$
> 	* $\text{I}_{4}: \forall a\ \exists b\ \forall c \ \bigl(c \in b \Leftrightarrow \exists d \ (d \in a \ \land \ c \in d) \bigr)$
> 	* $\text{I}_{5}: \exists w\colon \bigl(\varnothing \in w \ \land \ \forall x \ (x \in w \Rightarrow x \cup \{x\} \in w) \bigr)$
> 	* $\text{I}_{6}: \forall a\ \exists b\ \forall c \ \bigl(c \in b \Leftrightarrow c \in a \ \land \ \varphi(c)  \bigr)$
> 	* $\text{I}_{7}: \forall a \exists b \forall c \ (c \in b \leftrightarrow d \subseteq a)$
> 	* $\text{I}_{8}: \forall x\ \exists ! y \ \varphi[x,y] \Rightarrow \forall a\ \exists b\ \forall c \ \bigl(c \in b \Leftrightarrow \exists d \ (d \in a \ \land \ \varphi[d,c]) \bigr)$
> 	* $\text{I}_{9}: \forall s \ \Bigl(s \ne \varnothing \Rightarrow \exists a \ \bigl(a \in s \ \land \ \forall c \ (c \in b \Rightarrow c \notin s) \bigr) \Bigr)$