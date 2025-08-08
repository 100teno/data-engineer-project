# 📊 Pipeline de Análise de Desastres Naturais (1970–2021)

Projeto desenvolvido com foco em práticas reais de Engenharia de Dados e Analytics Engineer, utilizando PySpark e Databricks Workflows para orquestração. A proposta envolve o processamento, tratamento e modelagem de dados históricos sobre desastres naturais, com o objetivo de construir uma base analítica confiável para exploração e geração de insights.

---

## 🎯 Objetivo

Construir um pipeline completo de ingestão e transformação de dados históricos sobre desastres naturais, visando a criação de camadas estruturadas (bronze, silver, gold) que permitam análises temporais, geográficas e temáticas.

---

## 🛠️ Tecnologias e Ferramentas

- **Plataforma:** Databricks (Free Edition)
- **Linguagem:** PySpark (Python)
- **Orquestração:** Databricks Workflows
- **Armazenamento:** Delta Lake (camadas bronze, silver, gold)
- **Visualização:** Databricks Notebooks

---

## 🧱 Arquitetura do Pipeline

```
Ingestão (Bronze) → Limpeza e Padronização (Silver) → Modelagem Analítica (Gold)
```

- **Bronze:** ingestão bruta do arquivo `.xlsx`, sem transformações.
- **Silver:** limpeza, padronização de campos, conversão de tipos e normalização dos dados.
- **Gold:** agregações por país, tipo de desastre, década e geração de indicadores analíticos.

---

## 📁 Estrutura de Diretórios

```
/notebooks
│   ├── 01_bronze_ingestao.py
│   ├── 02_silver_tratamento.py
│   ├── 03_gold_analytics.py
│   └── 04_visualizacao.ipynb
/data
│   └── /bronze
│   └── /silver
│   └── /gold
/workflows
│   └── pipeline.json
```

---

## 📊 Métricas Geradas

- Total de desastres por país e ano
- Número de mortes, feridos e desabrigados por tipo de desastre
- Valor estimado de danos econômicos
- Análise de tendências ao longo das décadas
- Ranking de países mais afetados

---

## 📚 Fontes de Dados

- [EM-DAT: Emergency Events Database (1970–2021)](https://www.emdat.be/)
- Arquivos em formato `.xlsx`, contendo registros globais de desastres naturais, com classificação por tipo, país, ano e impacto.

---

## 🧑‍💻 Autor

Gabriel Centeno  
Analytics Engineer | Engenharia de Dados  

---