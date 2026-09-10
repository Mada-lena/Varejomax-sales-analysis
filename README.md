# Varejomax-sales-analysis
# 📊 Dashboard de Performance Comercial — VarejoMax
**Case Study:** Análise de Vendas Multicanal e Multi-filial  
**Ferramentas:** Power BI | DAX | Modelagem de Dados

---

## 🎯 1. O Problema de Negócio
A **VarejoMax** é uma distribuidora com 4 filiais e 3 canais de venda (Loja Física, Televendas e E-commerce) atendidos por 7 vendedores. 

Devido ao rápido crescimento sem profissionalização da análise de dados, a gestão comercial enfrentava falta de visibilidade sobre:
- Qual filial realmente puxava o faturamento;
- A performance individual da equipa de vendas;
- A evolução dos canais de distribuição ao longo do tempo.

O objetivo deste projeto foi transformar dados brutos em **respostas estratégicas** para dar suporte à tomada de decisão.

---

## 🛠️ 2. Ferramentas e Abordagem
Antes da criação dos visuais no Power BI, o projeto iniciou-se pela **mapeação das perguntas de negócio**:
1. **Modelagem de Dados:** Estruturação da base de dados de vendas por filial, canal e vendedor.
2. **Criação de Medidas em DAX:** Desenvolvimento de métricas como *Receita Total*, *Ticket Médio*, *Participação Percentual (%) por Canal e Região*.
3. **Construção de Dashboard Visual:** KPIs no topo, série temporal de vendas, doughnut chart por canal e ranking de vendedores.

---

## 🖼️ 3. Visualização dos Dados (Dashboard)
*(Insere aqui a captura de ecrã do dashboard do Power BI)*

---

## 🔍 4. Principais Descobertas (Insights)

* **Desempenho por Filial:** A *Loja Centro* lidera com **30,71%** do faturamento total (R$ 4,66 Mi), seguida da Norte (25,12%), Leste (22,54%) e Sul (21,64%). A distribuição é relativamente equilibrada.
* **Ranking de Vendedores:** Diogo Almeida lidera as vendas com **R$ 3,42 Mi**, seguido por Elaine Rocha e Ana Souza (ambas com R$ 2,33 Mi).
* **Mudança Estrutural no Mix de Canais (2024–2026):**
  - **E-commerce:** Quase dobrou a sua participação no mix de vendas, saltando de **15,59% para 30,60%** (+15,01 p.p.).
  - **Loja Física:** Sofreu um declínio contínuo, caindo de **54,59% para 44,12%** (-10,47 p.p.).
  - **Televendas:** Também reduziu a representatividade de **29,83% para 25,81%** (-4,02 p.p.).

---

## ⚠️ 5. Limitações Identificadas na Base de Dados
Uma entrega analítica completa exige reconhecer o que o painel **ainda não responde**:
1. **Falta de Causabilidade:** O dashboard mostra *o que* está a acontecer (queda da Loja Física e crescimento do E-commerce), mas **não explica *o porquê***. Faltam variáveis comportamentais do cliente.
2. **Ponto Cego na Equipa de Vendas:** O painel inicial apresenta apenas o *Top 3*, deixando 4 vendedores sem acompanhamento no relatório.
3. **Métricas Faltantes:** Ausência de *Ticket Médio individual por vendedor* e *série temporal desagregada por filial/canal*.

---

## 💡 6. Recomendações Estratégicas & Próximos Passos

### 🚀 Ações de Negócio Imediatas:
- **Priorizar Investimentos no E-commerce:** Canal com trajetória de crescimento consistente e sustentado.
- **Acompanhamento Integral da Força de Vendas:** Expandir a visibilidade do painel para os 7 vendedores com inclusão do Ticket Médio individual.

### 🔬 Plano de Investigação de Dados (Análise Diagnóstica):
Para responder à causa da perda de representatividade da Loja Física e Televendas, propõe-se o cruzamento de novas bases:
- **Análise de Omnicanalidade (ID do Cliente):** Verificar se os clientes físicos migraram para o e-commerce (migração saudável) ou se o e-commerce atraiu novos clientes enquanto a loja física sofreu *churn* (perda).
- **Métricas Qualitativas (NPS e Atendimento):** Recolher dados de satisfação e motivos de desistência no canal presencial/televendas.
- **Auditoria de Preço e Stock:** Avaliar se campanhas exclusivas ou ruturas de stock no canal presencial forçaram a migração para o digital.
