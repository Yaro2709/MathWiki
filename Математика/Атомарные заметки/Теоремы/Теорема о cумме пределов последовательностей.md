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

> [!theorem]+ Теорема о cумме пределов последовательностей
> Рассмотрим две последовательности $(x_n)_{n=1}^{\mathbb N}$ и $(y_n)_{n=1}^{\mathbb N}$. Пусть $\displaystyle\lim_{n\to \infty} x_n = a$ и $\displaystyle\lim_{n\to \infty} y_n = b$. Тогда предел суммы $(x_n)_{n=1}^{\mathbb N}$ и $(y_n)_{n=1}^{\mathbb N}$ равен сумме пределов $(x_n)_{n=1}^{\mathbb N}$ и $(y_n)_{n=1}^{\mathbb N}$
> $$\lim_{n\to \infty}\Big(x_n + y_n\Big) = \lim_{n\to \infty}x_n + \lim_{n\to \infty}y_n = a+b$$
> > [!proof]- Доказательство
> > 1. По теореме о связи предела и бесконечно малой: $$\begin{gather*} \lim_{n \to \infty}x_n = a \Leftrightarrow x_n = a + \alpha_n \Rightarrow \lim_{n \to \infty}\alpha_n = 0 \\ \lim_{n \to \infty}y_n = b \Leftrightarrow y_n = b + \beta_n \Rightarrow \lim_{n \to \infty}\beta_n = 0\end{gather*}$$
> > 2. Сложим $x_n$ и $y_n$: $$\begin{aligned} \lim_{n\to \infty}\Big(x_n + y_n\Big) = \\ = \lim_{n\to \infty}\Big(a + \alpha_n + b + \beta_n \Big) = && \textrm{Подставляем $x_n$ и $y_n$ из п. 1} \\  = \lim_{n\to \infty}\Big((a + b) + (\alpha_n + \beta_n) \Big) && \textrm{Группируем бесконечно малые} \\ = \lim_{n\to \infty}\Big((a + b) + \gamma_n \Big) =  && \textrm{По свойству суммы бесконечно малых} \\ = a + b  && \textrm{По теореме о связи предела и бесконечно малой} \end{aligned}$$
