## [[Formulas]]
## Resumo da Aula

![[Elementos de Máquina/Excalidraw/Aula 1.excalidraw|700]]
## Compreensão dos parâmetros de Carga

$\large\sigma_{max}$ : Tensão Máxima
$\large\sigma_{min}$ : Tensão Mínima 
$$\sigma_a (alternada) :\frac{\sigma_{\max }-\sigma_{\min }}{2}$$
$$\sigma_m (média):\frac{\sigma_{\max }+\sigma_{\min }}{2}$$
$$
\text { Intervalo de tensões: } \quad \Delta \sigma=\sigma_{\max }-\sigma_{\min }
$$
$$
\text { Razão de tensão e amplitude: } R=\frac{\sigma_{\text {min }}}{\sigma_{\text {max }}} \quad A=\frac{\sigma_a}{\sigma_{\mathrm{m}}}
$$
## Resistência à fadiga teórica $S_f'$ e limite de fadiga teórico $S_e'$ estimados
$$
\text { Aços }
\left {\begin{array}{lc}
S_e^{\prime}=0.5 \cdot S_{u t} & \text { para } S_{u t}<1400 \mathrm{MPa}  \\
S_e^{\prime} \cong 700 \mathrm{MPa} & \text { para } S_{u t} \geq 1400 \mathrm{MP}
\end{array}\right.
$$

$$
\text{Alumínio}
\left {\begin{array}{cc}
S_{f-5 e 8}{ }^{\prime}=0.4 \cdot S_{u t} & \text { para } S_{u t}<330 \mathrm{MPa} \\
S_{f-5 e 8}{ }^{\prime} \cong 130 \mathrm{MPa} & \text { para } S_{u t} \geq 1400 \mathrm{MP}
\end{array}\right.
$$

## Fatores de correção para resistência à fadiga e limite de fadiga teóricos

para ajustar as diferenças físicas dos corpos de prova e a peça real, utiliza-se fatores para definir a operação real:

- Carregamento
- Tamanho
- Superfície
- Temperatura
- Confiabilidade

$$
S_e=C_{c a r} \cdot C_{t a m} \cdot C_{\text {sup }} \cdot C_{t e m} \cdot C_{c o n f} \cdot S_e^{\prime}
$$

$$\begin{align*}
S_f &= C_{\text{car}}\cdot C_{\text{tam}}\cdot C_{\text{sup}}\cdot C_{\text{tem}}\cdot C_{\text{conf}}\cdot S'_f
\end{align*}$$
### Efeito do Carregamento

- Flexão: $$C_{car}=1$$
- Força Normal: $$C_{car} = 0.7$$
