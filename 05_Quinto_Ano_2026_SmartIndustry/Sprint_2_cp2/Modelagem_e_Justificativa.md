# Modelagem Técnica e Justificativa de Engenharia

**Projeto:** Smart Industry & Assistive Systems (Exo Upper Limb)
**Empresa Parceira:** Smart Industry, Startups & Assistive Systems
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Fase:** Sprint 2

### Especificação do Desafio
Projetar o circuito de instrumentação biomédica para captura de sinais de Eletromiografia de Superfície (sEMG) com amplificador de instrumentação de alto CMRR (> 110 dB). Implementar a filtragem passa-banda analógica de 20 a 450 Hz, retificação de onda completa, cálculo de envelope RMS e predição de intenção de movimento com Filtro de Kalman discreto executando sob o kernel FreeRTOS a 200 Hz.

### Formulação Matemática e Física
$$\text{RMS}(t) = \sqrt{\frac{1}{W} \int_{t-W}^{t} s^2(\tau) d\tau}, \quad \text{Latência Intenção} \le 15 \text{ ms}$$
