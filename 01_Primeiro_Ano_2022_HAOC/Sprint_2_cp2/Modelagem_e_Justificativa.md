# Modelagem Técnica e Justificativa de Engenharia

**Projeto:** Challenge Hospital Alemão Oswaldo Cruz (HAOC)
**Empresa Parceira:** Hospital Alemão Oswaldo Cruz
**Ano Letivo:** 2022 | **Turma:** 1ECB
**Fase:** Sprint 2

### Especificação do Desafio
Dimensionar o trem de força e o torque requerido nos motores de corrente contínua para um robô hospitalar móvel com tração diferencial de massa total M = 60 kg (estrutura + carga de soros/medicamentos). O robô deve acelerar de 0 a v_max = 1,2 m/s em t = 1,5 s superando rampa hospitalar de inclinação θ = 5° com coeficiente de atrito de rolamento μ_r = 0,02 e raio das rodas R = 0,08 m.

### Formulação Matemática e Física
$$F_{\text{total}} = M \cdot a + M \cdot g \cdot \sin\theta + M \cdot g \cdot \mu_r \cdot \cos\theta, \quad \tau_{\text{motor}} = \frac{F_{\text{total}} \cdot R}{2 \cdot \eta}$$
