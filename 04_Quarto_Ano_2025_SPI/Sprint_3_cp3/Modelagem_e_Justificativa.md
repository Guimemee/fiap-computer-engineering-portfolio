# Modelagem Técnica e Justificativa de Engenharia

**Projeto:** SPI / Metaindústria - Smart Robotics & Gêmeo Digital
**Empresa Parceira:** SPI / Metaindústria Smart Robotics
**Ano Letivo:** 2025 | **Turma:** 4ECS
**Fase:** Sprint 3

### Especificação do Desafio
Construir a simulação dinâmica de alta fidelidade e comissionamento virtual (Virtual Commissioning) do Gêmeo Digital em ambiente fotorrealístico 3D acoplado ao controlador em malha fechada (Software-in-the-Loop - SIL). Integrar modelo de visão computacional na borda para inspeção automática de peças montadas detectando falhas geométricas com tolerância inferior a 0,5 mm.

### Formulação Matemática e Física
$$\text{Erro Geom.} = \sqrt{\Delta x^2 + \Delta y^2 + \Delta z^2} \le 0,5 \text{ mm}, \quad \text{Taxa Falso Rejeito} \le 0,2\%$$
