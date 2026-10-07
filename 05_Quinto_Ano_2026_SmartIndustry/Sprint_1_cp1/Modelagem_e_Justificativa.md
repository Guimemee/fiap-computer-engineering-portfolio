# Modelagem Técnica e Justificativa de Engenharia

**Projeto:** Smart Industry & Assistive Systems (Exo Upper Limb)
**Empresa Parceira:** Smart Industry, Startups & Assistive Systems
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Fase:** Sprint 1

### Especificação do Desafio
Modelar as forças dinâmicas articulares e momentos musculares no membro superior humano durante tarefas repetitivas de elevação e sustentação de ferramentas pesadas na indústria automotiva. Dimensionar a estrutura cinemática em fibra de carbono e os redutores de velocidade de engrenagem harmônica (Harmonic Drive) para entrega de torque assistivo de até 22 N·m com peso estrutural inferior a 2,2 kg acoplado ao corpo.

### Formulação Matemática e Física
$$\tau_{\text{assist}} = \beta \cdot \tau_{\text{biomecânico}}, \quad \beta \in [0,70; 0,85], \quad \sigma_{\text{vonMises}} \le \frac{S_y}{\text{FS}}$$
