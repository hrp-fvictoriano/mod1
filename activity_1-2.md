# Activity 1.2

## P3

Using the Newton-Raphson Method $\left(x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}\right)$

$$
\begin{aligned}
f(x) = x^4 - x - 10 \\
f'(x) = 4x^3 - 1 \\
x_0 = 1 \\
x_0 = 2 \\
x_0 = 100 \\
\end{aligned}
$$

For $x_0 = 1$,

$$
\begin{aligned}
x_1 = 1 - \frac{f(1)}{f'(1)} \approx 4.3333 \\
x_2 = 4.3333 - \frac{f(4.3333)}{f'(4.3333)} \approx 3.2908 \\
x_3 = 3.2908 - \frac{f(3.2908)}{f'(3.2908)} \approx 2.5562 \\
x_4 = 2.5562 - \frac{f(2.5562)}{f'(2.5562)} \approx 2.0982 \\
x_5 = 2.0982 - \frac{f(2.0982)}{f'(2.0982)} \approx 1.8956 \\
f(x_5) \approx 1.0162
\end{aligned}
$$

For $x_0 = 2$,

$$
\begin{aligned}
x_1 = 2 - \frac{f(2)}{f'(2)} \approx 1.8710 \\
x_2 = 1.8710 - \frac{f(1.8710)}{f'(1.8710)} \approx 1.8558 \\
x_3 = 1.8558 - \frac{f(1.8558)}{f'(1.8558)} \approx 1.8556 \\
x_4 = 1.8556 - \frac{f(1.8556)}{f'(1.8556)} \approx 1.8556 \\
x_5 = 1.8556 \\
f(x_5) \approx 3.7993\times10^{-4}
\end{aligned}
$$

For $x_0 = 100$,

$$
\begin{aligned}
x_1 = 100 - \frac{f(100)}{f'(100)} \approx 75 \\
x_2 = 75 - \frac{f(75)}{f'(75)} \approx 56.25 \\
x_3 = 56.25 - \frac{f(56.25)}{f'(56.25)} \approx 42.1876 \\
x_4 = 42.1876 - \frac{f(42.1876)}{f'(42.1876)} \approx 31.6408 \\
x_5 = 31.6408 - \frac{f(31.6408)}{f'(31.6408)} \approx 23.7309 \\
f(x_5) = 3.1711\times10^5
\end{aligned}
$$
