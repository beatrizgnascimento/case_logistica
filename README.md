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

### 📁 **Apresentação**

- **`Case iFood Logística.pdf`** - Slides de apresentação para líderes de negócio
- **`grafico.ipynb`** - Gráfico de radar e de barras usado no slide

### 📓 **Notebooks de Análise**

#### 🔍 **`analise_historica.ipynb`** - Análise Exploratória

**Objetivo:** Entender o cenário atual e identificar oportunidades

**Principais Análises:**

- 📈 **Distribuição AOV:** Segmentação de restaurantes por valor do ticket
- 🏪 **Análise de Penetração:** 77.3% Marketplace vs 22.7% Full Service
- 💰 **Rentabilidade por Segmento:** Performance financeira detalhada
- 📊 **Análise Pareto:** 20% dos restaurantes geram 80% da receita
- 🔄 **Padrões Sazonais:** Tendências temporais de receita e comissões

#### ⚙️ **`estrategias.ipynb`** - Desenvolvimento de Estratégias

**Objetivo:** Criar e otimizar 4 estratégias de comissionamento

**Estratégias Desenvolvidas:**

1. **🎯 Hierárquica (AOV x Volume)**

   - Foca em crescimento e escala
   - Prioriza alto volume + alto AOV

2. **⚡ Custo-Benefício (AOV x Eficiência Operacional)**

   - Otimiza margem operacional
   - Considera custos de ocorrências

3. **💎 Rentabilidade Líquida (Receita x Margem)**

   - Maximiza lucratividade real
   - Foca em valor sustentável
   - Não utiliza o AOV

4. **🏆 AOV x Rentabilidade (RECOMENDADA)**
   - Combina alto AOV com rentabilidade
   - É a estratégia de rentabilidade líquida mas combinando com o AOV

**Metodologia Técnica:**

- **Otimização Matemática:** Algoritmos de convergência para neutralidade de receita de comissões (não mudar e, se mudar, que seja só um pouco maior)
- **Cenários Múltiplos:** Conservador, Moderado e Agressivo para cada estratégia
- **Segmentação:** 9 perfis baseados em AOV x Rentabilidade (P1-P9)

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

## 📄 **Licença**

Todos os dados utilizados são ficcionais e criados especificamente para este case.
