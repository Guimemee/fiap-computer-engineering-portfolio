# Modelagem Técnica e Justificativa de Engenharia

**Projeto:** Smart Industry & Assistive Systems (Exo Upper Limb)
**Empresa Parceira:** Smart Industry, Startups & Assistive Systems
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Fase:** Sprint 3

### Especificação do Desafio
Implementar a malha de controle de impedância mecânica virtual (Massa-Mola-Amortecedor) parametrizando rigidez K e amortecimento B variáveis dinamicamente de acordo com a fadiga do usuário. Integrar a Google Gemini API na borda conectada via ESP32/Wi-Fi para monitorar métricas biométricas ao longo da jornada de trabalho e sugerir pausas preventivas e ajustes ergonômicos automáticos.

### Formulação Matemática e Física
$$\tau_{\text{motor}} = M_d(\ddot{\theta}_d - \ddot{\theta}) + B_d(\dot{\theta}_d - \dot{\theta}) + K_d(\theta_d - \theta)$$
