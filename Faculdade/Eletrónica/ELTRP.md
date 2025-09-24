
$X_{m}=\frac{1}{T}\int _{0}^T x(t)dt$ -> Valor médio


$X_{ef}=\sqrt{ \frac{1}{T}*\int_{0}^T x^2(t)dt }$ -> Valor eficaz


$P=\frac{1}{T}\int_{0}^T p(t)dt=\frac{1}{T}\int_{0}^Tv(t)i(t)dt$ -> Potência ativa=Potência média=Potência útil

$P=RI_{ef}^2$ -> Carga RL

$P=RI_{ef}^2+EI_{médio}$ -> Carga RLE

$S=V_{ef}I_{ef}$ -> Potência aparente, potência debitada pela fonte

$FP=\frac{P}{S}$ -> Fator de Potência, deve ser o mais próximo possível de 1


Tensão e corrente são funções sinusoidais, $FP=\frac{P}{S}=\cos(\phi)$,$\phi$->desfasamento entre as duas funções

Tensão sinusoidal e corrente não sinusoidal:
$FP=\frac{p}{S}=\frac{\frac{1}{T}*\int_{0}^Tv(t)i(t)dt}{V_{ef}I_{ef}}$ ou $FP=\frac{I_{1}\cos(\phi_{1})}{I_{ef}}$ $\phi_{1}$ - desfasamento entre a função tensão e componente fundamental da corrente

**Componentes harmónicas** são correntes **sinusoidais** com uma frequência múltipla da frequência fundamental

$i(t)=i_{1}(t)+\sum_{n=2}^{\infty}i_{n(t)}$

**Qualquer onda (tensão ou corrente) não sinusoidal tem harmônicos**

$y(t)=\frac{4}{\pi}( \sin(2\pi f_{1}t)+0+\frac{1}{3}\sin(2\pi3f_{1}t)+0+\frac{1}{5}\sin(2\pi5f_{1}t)+\dots)$
harmônica fundamental -> corrente ->$i_{1}$

harmônicas múltiplas -> $i_{n}$

valor eficaz:

$I_{ef}=\sqrt{ \frac{1}{T}\int_{0}^{T}i^2(t)dt}=\sqrt{I_{1}^2+\sum_{n=2}^{\infty}I_{n}^{2}}$


Taxa de Distorção Harmónica:

$TDH=\frac{\sqrt{\sum_{n=2}^{\infty}I_{n}^{2}}}{I_{1}}$

$P=\frac{1}{T}\int_{0}^{T}v(t)i(t)dt=\frac{1}{T}\int_{0}^{T}\sqrt{2V_{ef}}\sin(wt)\sqrt{2I_{1}}\sin(wt-\phi_{1})dt=V_{ef}I_{1}\cos(\phi_{1})$
$\phi_{1}$ -> desfasamento entre tensão e componente fundamental da corrente

$FP=\frac{P}{S}=\frac{V_{ef}I_{1}\cos(\phi_{1})}{V_{ef}I_{1}}$ **ou** $FP=\frac{\cos(\phi_{1})}{\sqrt{1+TDH^{2}}}$


Condensador
$W=\frac{1}{2}CV^{2}$

Bobine
$V=N\frac{d\phi}{dt}=L\frac{di}{dt}$
$W=\frac{1}{2}Li^2$


![[Pasted image 20250924164751.png]]

$v_{L}(t)=L\frac{di_{L}(t)}{dt}$

$[t_{1},t_{2}]$: bobine armazena energia $\frac{di_{L}(t)}{dt}>0$
$[t_{2},t_{1}+T]$: bobine libera energia $\frac{di_{L}(t)}{dt}>0$

![[Pasted image 20250924165023.png]]

$i_{C}=C\frac{dv_{C}(t)}{dt}$

$[t_{1},t_{2}]$: condensador liberta energia $\frac{dv_{C}(t)}{dt}<0$
$[t_{2},t_{1}+T]$: condensador armazena energia $\frac{dv_{C}(t)}{dt}>0$
