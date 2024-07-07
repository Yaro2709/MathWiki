> [!info]
> Тэги: #Теорема #Математический_анализ   
> 
> Использует: [[Определение бесконечно большой последовательности]]
> Примеры: *-*
> 
> Ссылки: *-*
> 
> Эквивалентности: *-*
> Обобщения: *-*

> [!theorem]+ Теоремa о связи эквивалентности бесконечно больших последовательностей и равенстве их пределов
> Рассмотрим две бесконечно большие последовательности $(\alpha_n)_{n=1}^{\mathbb N}$ и $(\beta_n)_{n=1}^{\mathbb N}$ и действительное число $t$. Пусть $\displaystyle\lim_{n \to \infty}\alpha_n = \lim_{n \to \infty}\beta_n = \infty$. Тогда предел $\displaystyle\frac{t}{\alpha_n}$ равен пределу $\displaystyle\frac{t}{\beta_n}$. $$\alpha_n \sim \beta_n \Rightarrow \lim_{n \to \infty}\frac{t}{\alpha_n} = \lim_{n \to \infty}\frac{t}{\beta_n}$$
> > [!proof]- Доказательство
> > 1. Сравним две бесконечно большие величины $\beta_n$ и $\alpha_n$:  $$\frac{\displaystyle\lim_{n \to \infty}\beta_n}{\displaystyle\lim_{n \to \infty}\alpha_n} = \displaystyle\lim_{n \to \infty}\frac{\beta_n}{\alpha_n} = 1$$
> > 2. Выразим выражение: $$\displaystyle\lim_{n \to \infty} \frac{t}{\alpha_n} = \displaystyle\lim_{n \to \infty}\frac{t  \beta_n}{\alpha_n\beta_n} = \displaystyle\lim_{n \to \infty}\frac{t}{\beta_n} \displaystyle\lim_{n \to \infty}\frac{ \beta_n}{\alpha_n} = \displaystyle\lim_{n \to \infty}\frac{t}{\beta_n}$$
