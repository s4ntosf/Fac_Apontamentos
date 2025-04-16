- Ferramenta que modeliza fenómenos de curta duração
- Função atípica que não é caracterizada na amplitude mas pela área constante
Características da função:
- Se *v(t)* é contínua em $t_d$ , então 
$$v(t_{d})=\int_{-\infty}^{+\infty}v(t)\delta(t-t_{d})dt$$

- Área unitária
$$
\int_{-\infty}^{+\infty}\delta(t)dt=\lim_{ \varepsilon \to 0 } \int_{-\varepsilon}^{+\varepsilon}\delta(t)dt=1
$$
$$
\delta(t)=\begin{cases} +\infty & 0^-<t<0^+ \\
0 & t<0^-,t>0^+
\end{cases}
$$
- Amostragem
$$
v(t)\delta(t-t_{d})=v(t_{d})\delta(t-t_{d})
$$

- Mudança de escala, para $\alpha \neq{0}$
$$
\delta(\alpha t)=\frac{1}{|\alpha|}\delta(t-t_{d})
$$
- Relação com a função Degrau
$$
\delta(t)=\frac{d}{dt}u(t)
$$
