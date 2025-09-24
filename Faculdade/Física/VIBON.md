15/09/2025

MHS->SHO - simple harmonic oscillation

applying external forces -> forced motion

applying internla forces -> damped motion

$x(t)=A\sin\left( \frac{2\pi}{T}t+c \right)$
A -> Amplitude
T -> Período
c -> desfasamento

$A - \sin = 1, c=\frac{\pi}{2}$
$-A - \sin = -1, c=-\frac{\pi}{2}$

quanto t=T, $w_{o}=\frac{2\pi}{T}$

$x(t)=A\sin(w_{o}t+\phi_{0})$

$x'(t)=v(t)$
$x'(t)=Aw_{o}\cos(w_{o}t+\phi_{o})$

$x''(t)=a(t)$
$x'(t)=-Aw_{o}^2\sin(w_{o}t+\phi_{o}) = -w_{o}^2x(t)$

x(t) -> x''(t)
fase=180º

$\vec{F}=-K\vec{x}$
$a_{x}=-\frac{k}{m}x$
$w_{o}=\sqrt{ \frac{k}{m}}$
$x''(t)+\frac{k}{m}x=0$ -> Eq. Dif. Mov.

22/09/2025

$x(t)=A\sin( \sqrt{ \frac{k}{m}}+\phi_{o})$
$\phi_{o}$, depende das condições iniciais
$\sqrt{\frac{k}{m}}$, depende das características do oscilador
A, depende das condições iniciais

$F=-kx$
$W_{AB}=\int_{x_{A}}^{x_{B}}\vec{F}*d\vec{r}=-\int_{x_{A}}^{x_{B}}kxî*dxî=-\int_{x_{A}}^{x_{B}}kxdx=-k[\frac{x^2}{2}]_{x_{A}}^{x_{B}}=-k\frac{x_{B}^2}{2}+k\frac{x_{A}^2}{2}$
î -> versor xx
^j -> versor yy
^z -> versor zz
$W_{AB}=\frac{1}{2}k(x_{A}^2-x_{B}^2)$


Como $W_{AB}$, trabalho, não depende do caminho percorrido mas sim das posições inicial e final, podemos dizer que **o campo de forças é conservativo.**

$E_{p}(A)=\frac{1}{2}kx_{A}^2$

$E_{c}=\frac{1}{2}mv^2$
$E_{c}=\frac{1}{2}k[A^2-x^2]$

$\frac{1}{2}mw_{o}^2A^2=E_{p}(x=A)$

$E_{p}+E_{c}=\frac{1}{2}kx^2+\frac{1}{2}k(A^2-x^2)=\frac{1}{2}kA^2$ (constante)

$E_{c}=\frac{1}{2}mv^2$
$E_{p}=\frac{1}{2}kx^2$

Pendulo simples

$\alpha = -\frac{g}{L}\theta$
$\alpha=-\omega^2x$
$\omega=\sqrt{\frac{g}{L}}$

$-mg\sin \theta=ma_{t}$
$a_{t}=L\alpha=L\frac{d^2\theta}{dt^2}=L\theta''$
$-g\sin \theta=L\theta''==\theta''+\frac{g}{L}\sin \theta=0$
$\theta''+\frac{g}{L}=0$
$\theta(t)=\theta_{máx}\sin(\omega_{o}t+\phi_{o})$
$T=\frac{2\pi}{\omega_{o}}=2\pi\sqrt{\frac{L}{g}}$
$\theta(t)=\theta_{máx}\sin\left( \sqrt{\frac{g}{L}}t+\phi_{o} \right)$

Pendulo Composto

$\sum \vec{M_{O}}(\vec{F})=I_{O}\vec{\alpha}$

$\vec{M_{O}}(\vec{F})=\vec{r_{O}}*\vec{F} \implies M_{O}=-r_{O}mg\sin \theta$
$-r_{O}mg\sin \theta=I_{O}\theta$

$\theta''+\frac{mgr_{O}}{I_{O}}\theta=0$

$\theta(t)=\theta_{máx}\sin(\omega_{o}t+\phi_{o})$
$\omega_{o}=\sqrt\frac{mgr_{O}}{I_{O}}$
$T=\frac{2\pi}{\omega_{o}}=2\pi \sqrt{}$