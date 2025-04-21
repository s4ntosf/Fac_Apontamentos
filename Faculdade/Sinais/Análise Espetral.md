Seja *x(t)* a representação um sinal elétrico, ao aplicar a Transformada e Fourier de maneira a obter *X(f)*, essa função passa a representar as amplitudes do espetro na frequência.

# Densidade Espectral

O desenvolvimento $|X(f)|^2$ é designado por Densidade Espectral do espetro *X(f)* e representa a densidade do espetro em função da frequência,
- Caso *x(t)* seja um ==tipo energia==, então, $|X(f)|^2=G_{x}(f) [JHz^{-1}]$ e $G_{x}(f)$ designa-se por ==Densidade Espectral de Energia==.
- Caso *x(t)* seja um ==tipo potência==, então, $|X(f)|^2=S_{x}(f) [WHz^{-1}]$ e $S_{x}(f)$ designa-se por ==Densidade Espectral de Potência==.

# Correlação Cruzada

Semelhança entre **dois sinais** enquanto que é aplicado um **atraso ($\tau)$** a cada um.
Utilizado para encontrar **padrões comuns entre dois sinais**, por exemplo, saber se um sinal está contido dentro de outro.

$$
R_{xy}(\tau)=x(\tau)*y^*(-\tau)=\int_{-\infty}^{+\infty}x(t)y^*(t-\tau) dt
$$
- $x(t)$ e $y(t)$: sinais no tempo;
- $y^*(t-\tau)$: conjugado complexo de $y$, deslocado por $\tau$;
- O integral mede a sobreposição dos sinais à medida que um é deslocado no tempo.

# Autocorrelação

Correlação Cruzado de um sinal com ele próprio.
Esta operação pode ser utilizada para encontrar padrões repetitivos, como a presença de um sinal periódico mascarado pelo ruído.

$$
R_{x}(\tau)=x(\tau)*x^*(-\tau)=\int_{t=-\infty}^{t=+\infty}x(t)x^*(t-\tau) dt
$$
Relação entre a função **Autocorrelação** e **Densidade Espectral**:
$F[R_{x}(\tau)=X(f).X^*(f)=|X(f)|^2]$        $R_{x}(\tau)=F^-1|X(f)|^2$