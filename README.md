# 🚀 Análise de Estratégias de Comissionamento - iFood

## 📋 **Sobre o Projeto**

Este projeto foi desenvolvido para otimizar a estratégia de comissionamento do iFood, com foco em **reduzir taxas para parceiros de alto AOV (Average Order Value) no Full Service** e aumentar a competitividade da plataforma.

### 🎯 **Objetivo Principal**

Desenvolver estratégias para:

- Reduzir comissões de parceiros premium (Alto AOV + Full Service)
- Incentivar migração de Marketplace → Full Service
- Manter neutralidade de receita
- Aumentar satisfação dos parceiros estratégicos

---

## 📁 **Estrutura dos Arquivos**

### 📊 **Dados**

- **`Base de Dados.xlsx`** - Dataset principal com dados de restaurantes, comissões, AOV e performance
- **`Case Analista.pdf`** - Briefing original do case com objetivos e contexto

### 📓 **Notebooks de Análise**

#### 🔍 **`analise_historica.ipynb`** - Análise Exploratória

**Objetivo:** Entender o cenário atual e identificar oportunidades

**Principais Análises:**

- 📈 **Distribuição AOV:** Segmentação de restaurantes por valor do ticket
- 🏪 **Análise de Penetração:** 77.3% Marketplace vs 22.7% Full Service
- 💰 **Rentabilidade por Segmento:** Performance financeira detalhada
- 📊 **Análise Pareto:** 20% dos restaurantes geram 80% da receita
- 🔄 **Padrões Sazonais:** Tendências temporais de receita e comissões

**Key Insights:**

- Alto AOV tem apenas **16.6% de penetração FS** (grande oportunidade)
- Segmento premium representa **33.6% da base total**
- **7.103 restaurantes MP** de Alto AOV podem migrar para FS

#### ⚙️ **`estrategias.ipynb`** - Desenvolvimento de Estratégias

**Objetivo:** Criar e otimizar 4 estratégias de comissionamento

**Estratégias Desenvolvidas:**

1. **🎯 Hierárquica (AOV x Volume)**

   - Foca em crescimento e escala
   - Prioriza alto volume + alto AOV

2. **⚡ Custo-Benefício (AOV x Eficiência Operacional)**

   - Otimiza margem operacional
   - Considera custos de delivery e ocorrências

3. **💎 Rentabilidade Líquida (Receita x Margem)**

   - Maximiza lucratividade real
   - Foca em valor sustentável

4. **🏆 AOV x Rentabilidade (RECOMENDADA)**
   - Combina alto ticket com rentabilidade
   - Atende diretamente ao objetivo do case

**Metodologia Técnica:**

- **Otimização Matemática:** Algoritmos de convergência para neutralidade de receita
- **Cenários Múltiplos:** Conservador, Moderado e Agressivo para cada estratégia
- **Segmentação Inteligente:** 9 perfis baseados em AOV x Rentabilidade (P1-P9)
- **Validação Rigorosa:** Simulações com dados reais de comissão

---

## 🛠️ **Tecnologias Utilizadas**

### 📚 **Bibliotecas Python**

```python
# Análise de Dados
pandas, numpy

# Visualização
matplotlib, seaborn, plotly

# Otimização Matemática
scipy

# Análise Estatística
statsmodels
```

## 🚀 **Como Executar**

### 📋 **Pré-requisitos**

```bash
# Instalar dependências
pip install pandas numpy matplotlib seaborn plotly scipy statsmodels scikit-learn openpyxl
```

### ▶️ **Ordem de Execução**

1. **Abrir `analise_historica.ipynb`**

   - Executar todas as células para análise exploratória
   - Gerar insights e identificar oportunidades

2. **Abrir `estrategias.ipynb`**
   - Executar desenvolvimento das 4 estratégias

### 📊 **Outputs Esperados**

- Dashboards comparativos das estratégias
- Heatmaps de taxas otimizadas
- Tabelas executivas de KPIs
- Simulações de migração validadas

---

## 🎯 **Próximos Passos**

### 📋 **Implementação Recomendada**

1. **Fase Piloto (3 meses)**

   - Teste A/B com 10% da base Alto AOV
   - Monitoramento de métricas-chave

2. **Expansão Moderada (6 meses)**

   - Rollout para Médio AOV
   - Ajustes baseados em resultados

3. **Implementação Completa (12 meses)**
   - Estratégia total em todos segmentos
   - Monitoramento contínuo de performance

### 📈 **KPIs de Acompanhamento**

- Taxa de migração MP → FS
- AOV médio por segmento
- NPS dos parceiros
- Receita total consolidada
- Penetração FS por categoria AOV

## 📄 **Licença**

Todos os dados utilizados são ficcionais e criados especificamente para este case.