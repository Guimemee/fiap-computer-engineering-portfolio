# Modelagem Técnica e Justificativa de Engenharia

**Projeto:** Challenge Hospital Alemão Oswaldo Cruz (HAOC)
**Empresa Parceira:** Hospital Alemão Oswaldo Cruz
**Ano Letivo:** 2022 | **Turma:** 1ECB
**Fase:** Sprint 1

### Especificação do Desafio
Dimensionar a viabilidade econômico-financeira para implantação de uma frota de 4 robôs autônomos de transporte de medicamentos no Hospital Alemão Oswaldo Cruz. O investimento inicial de hardware e sensores é CAPEX = R$ 180.000,00 e custo operacional de energia/manutenção OPEX = R$ 2.400,00/mês. A operação manual atual demanda 6 maqueiros/mensageiros com custo mensal de R$ 4.200,00 cada. Determinar o Ponto de Equilíbrio (Break-Even Point em meses) e o VPL em 3 anos a uma TMA de 10% a.a.

### Formulação Matemática e Física
$$\text{Break-Even} = \frac{\text{CAPEX}}{\Delta\text{OPEX}_{\text{mensal}}}, \quad \text{VPL} = -I_0 + \sum_{t=1}^{3} \frac{\text{Fluxo}_t}{(1 + \text{TMA})^t}$$
