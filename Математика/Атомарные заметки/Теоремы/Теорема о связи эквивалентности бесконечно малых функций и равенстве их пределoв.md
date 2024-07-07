> [!info]
> Тэги: #Теорема #Математический_анализ   
> 
> Использует: [[Определение бесконечно малой функции в окрестности точки]]
> Примеры: *-*
> 
> Ссылки: *-*
> 
> Эквивалентности: *-*
> Обобщения: *-*

> [!theorem]+ Теорема о связи эквивалентности бесконечно малых функций и равенстве их пределoв
> Рассмотрим две бесконечно малые функции $y = \alpha(x):X_1 \subset \mathbb{R^{\pm\infty}}\rightarrow Y_1 \subset \mathbb{R^{\pm\infty}}$ и $y = \beta(x):X_2 \subset \mathbb{R^{\pm\infty}}\rightarrow Y_2 \subset \mathbb{R^{\pm\infty}}$ и действительное число $t$. Пусть $\displaystyle\lim_{x \to x_0}\alpha(x) = \lim_{x \to x_0}\beta(x) = 0$. Тогда предел $\displaystyle\frac{t}{\alpha(x)}$ равен пределу $\displaystyle\frac{t}{\beta(x)}$. $$\alpha(x) \sim \beta(x) \Rightarrow \lim_{x \to x_0}\frac{t}{\alpha(x)} = \lim_{x \to x_0}\frac{t}{\beta(x)}$$
> > [!proof]- Доказательство
> > 1. Сравним две бесконечно малые величины $\beta(x)$ и $\alpha(x)$:  $$\frac{\displaystyle\lim_{x \to x_0}\beta(x)}{\displaystyle\lim_{x \to x_0}\alpha(x)} = \displaystyle\lim_{x \to x_0}\frac{\beta(x)}{\alpha(x)} = 1$$
> > 2. Выразим выражение: $$\displaystyle\lim_{x \to x_0} \frac{t}{\alpha(x)} = \displaystyle\lim_{x \to x_0}\frac{t  \beta(x)}{\alpha(x)\beta(x)} = \displaystyle\lim_{x \to x_0}\frac{t}{\beta(x)} \displaystyle\lim_{x \to x_0}\frac{ \beta(x)}{\alpha(x)} = \displaystyle\lim_{x \to x_0}\frac{t}{\beta(x)}$$
