# Modelagem Técnica e Justificativa de Engenharia

**Projeto:** Challenge Hospital Alemão Oswaldo Cruz (HAOC)
**Empresa Parceira:** Hospital Alemão Oswaldo Cruz
**Ano Letivo:** 2022 | **Turma:** 1ECB
**Fase:** Sprint 4

### Especificação do Desafio
Implementar o algoritmo de menor caminho (Dijkstra com Fila de Prioridade) sobre o grafo topológico da planta do Hospital Alemão Oswaldo Cruz contendo 42 nós (enfermarias, UTI, farmácia central, elevadores e postos de enfermagem). Avaliar a latência de cálculo de rota, a segurança de tráfego em corredores compartilhados e a integração com o banco de dados do prontuário eletrônico via API REST.

### Formulação Matemática e Física
$$d(v) = \min_{(u,v) \in E} \{d(u) + w(u,v)\}, \quad \text{Complexidade} = O((V + E) \log V)$$
