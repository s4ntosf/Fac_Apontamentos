Nesta U.C os sinais que serão estudados são Sinais Elementares.

Estes podem aparecer como:

- Sinal Sinusoidal
$$
	x(t)=A.cos(2\pi f_0 t+\phi)
$$
- Sinal Exponencial Complexo
$$
x(t)=A.e^j(2\pi f_{0}t+\phi)
$$
- Degrau Unitário ou de *Heaviside*
$$
u(t)=\begin{cases}
1 &  t>0 \\
0 &  t<0
\end{cases}
$$
- Impulso retangular (Pedestal)
$$
\Pi(t)=\begin{cases} 1 & -\frac{\tau}{2}<t<\frac{\tau}{2} \\
0 & t<-\frac{\tau}{2},t>\frac{\tau}{2}
\end{cases}
$$
- Impulso triangular
$$
\Lambda(t)=\begin{cases}
\frac{2}{\tau}+1 & -\frac{\tau}{2}<t<0 \\
-\frac{2}{\tau}+1 & 0<t<\frac{\tau}{2} \\
0 & |t|>\frac{\tau}{2}
\end{cases}
$$
- Seno Cardinal - *Sinc*
$$
Sinc(t)=\frac{Sin(\pi t)}{\pi t}
$$
- Impulso Dirac - $\delta$(t) [[Impulsos Dirac]]
$$
\delta(t)=\lim_{ \tau \to 0 }\frac{1}{\tau}\Pi(\frac{t}{\tau})
$$
