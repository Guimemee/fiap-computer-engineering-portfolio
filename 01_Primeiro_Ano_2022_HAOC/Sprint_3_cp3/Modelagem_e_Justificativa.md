# Modelagem Técnica e Justificativa de Engenharia

**Projeto:** Challenge Hospital Alemão Oswaldo Cruz (HAOC)
**Empresa Parceira:** Hospital Alemão Oswaldo Cruz
**Ano Letivo:** 2022 | **Turma:** 1ECB
**Fase:** Sprint 3

### Especificação do Desafio
Projetar a arquitetura eletrônica de potência e sensoriamento de desvio de obstáculos para navegação em corredores hospitalares com fluxo de pessoas. Dimensionar o banco de baterias de Lítio Ferro Fosfato (LiFePO4) de 24 V para sustentar autonomia mínima de 12 horas contínuas de operação considerando potência média consumida de 95 W e profundidade máxima de descarga (DoD) de 80%.

### Formulação Matemática e Física
$$E_{\text{requerida}} = \frac{P_{\text{médio}} \cdot t}{\text{DoD} \cdot \eta_{\text{conv}}}, \quad C_{\text{Ah}} = \frac{E_{\text{Wh}}}{V_{\text{nom}}}$$
