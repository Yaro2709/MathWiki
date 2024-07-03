> [!info]
> Тэги: #Теорема #Математический_анализ   
> 
> Использует: *-*
> Примеры: *-*
> 
> Ссылки: *-*
> 
> Эквивалентности: *-*
> Обобщения: *-*

> [!theorem]+ Теорема о cумме пределов функций
> Рассмотрим две функции $y = f(x):X_1 \subset \mathbb{R^{\pm\infty}}\rightarrow Y_1 \subset \mathbb{R^{\pm\infty}}$ и $y= g(x):X_2 \subset \mathbb{R^{\pm\infty}}\rightarrow Y_2 \subset \mathbb{R^{\pm\infty}}$. Пусть $\displaystyle\lim_{x\to x_0}f(x) = a$ и $\displaystyle\lim_{x\to x_0}g(x) = b$. Тогда предел суммы $f(x)$ и $g(x)$ равен сумме пределов $f(x)$ и $g(x)$
> $$\lim_{x\to x_0}\Big(f(x) + g(x)\Big) = \lim_{x\to x_0}f(x) + \lim_{x\to x_0}g(x) = a+b$$
> > [!proof]- Доказательство
> > 1. По теореме о связи предела и бесконечно малой: $$\begin{gather*} \lim_{x \to x_0}f(x) = a \Leftrightarrow f(x) = a + \alpha(x) \Rightarrow \lim_{x \to x_0}\alpha(x) = 0 \\ \lim_{x \to x_0}g(x) = b \Leftrightarrow g(x) = b + \beta(x) \Rightarrow \lim_{x \to x_0}\beta(x) = 0\end{gather*}$$
> > 2. Сложим $f(x)$ и $g(x)$: $$\begin{aligned} \lim_{x \to x_0}\Big(f(x) + g(x)\Big) = \\ = \lim_{x \to x_0}\Big(a + \alpha(x) + b + \beta(x) \Big) = && \textrm{Подставляем $f(x)$ и $g(x)$ из п. 1} \\  = \lim_{x \to x_0}\Big((a + b) + (\alpha(x) + \beta(x)) \Big) && \textrm{Группируем бесконечно малые} \\ = \lim_{x \to x_0}\Big((a + b) + \gamma(x) \Big) =  && \textrm{По свойству суммы бесконечно малых} \\ = a + b  && \textrm{По теореме о связи предела и бесконечно малой} \end{aligned}$$
