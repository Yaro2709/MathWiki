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

> [!theorem]+ Теорема об эквивалентности бесконечно малой функции в степени $-n$
> Рассмотрим две бесконечно малые функции $y=\alpha(x):X_1 \subset \mathbb{R^{\pm\infty}}\rightarrow Y_1 \subset \mathbb{R^{\pm\infty}}$ и $y=\beta(x):X_2 \subset \mathbb{R^{\pm\infty}}\rightarrow Y_2 \subset \mathbb{R^{\pm\infty}}$. Пусть $y=\alpha(x) = \sqrt[n]{1+x} - 1$ и $y=\beta(x) = \displaystyle\frac{x}{n}$. Тогда $\sqrt[n]{1+x} - 1$ эквивалентно $\displaystyle\frac{x}{n}$.
> $$\sqrt[n]{1+x} - 1 \sim \frac{x}{n}$$
> > [!proof]- Доказательство
> > 1. Воспользуемся формулой $e^{\ln a} = a$: $$\sqrt[n]{1+x} - 1 = e ^{\frac{1}{n} \ln(1+x)} - 1$$
> > 2. Воспользуемся сравнением бесконечно малых функций: $$\lim_{x \to x_0} e ^{\frac{1}{n} \ln(1+x)} - 1 = $$
> > 3. Как видим, мы получили знакомое отношение на $e^x-1 \sim x$: $$=\frac{1}{n} \ln (1+x) \sim$$
> > 4. Воспользуемся $\ln (1+x) \sim x$, тогда: $$\sim \frac{x}{n}$$
