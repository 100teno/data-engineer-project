# 📊 Projeto de Pipeline de Dados com Python – Bronze, Silver e Gold

Este repositório contém um projeto prático de engenharia de dados desenvolvido em Python, com foco em consolidar conhecimentos fundamentais na trilha de Analytics Engineer.

A proposta é simular uma arquitetura em camadas (Bronze → Silver → Gold), realizando ingestão, tratamento, organização e análise de dados públicos, utilizando bibliotecas como `pandas`, `numpy`, `matplotlib`, entre outras.

---

## 🚀 Objetivo do Projeto

Criar um pipeline simples e eficiente que:
- Replique boas práticas de engenharia de dados
- Organize os dados de forma estruturada por camadas
- Produza insights prontos para visualização e análise
- Sirva como base para projetos futuros e portfólio

---

## 🧱 Estrutura em Camadas

| Camada     | Descrição |
|------------|-----------|
| **Bronze** | Ingestão dos dados brutos diretamente da fonte, sem alterações |
| **Silver** | Limpeza, padronização e enriquecimento dos dados |
| **Gold**   | Geração de indicadores, agregações e visualizações |

---

## 🛠️ Tecnologias Utilizadas

- Python 3.10+
- pandas
- numpy
- matplotlib / seaborn / plotly
- uuid / datetime / os
- (opcional) feather, parquet ou SQLite

---

## 🗂️ Organização do Repositório

```
projeto_pipeline_analytics/
│
├── data/               # Armazena os dados das 3 camadas
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── notebooks/          # Notebooks Jupyter para cada etapa do pipeline
│   ├── ingestao_bronze.ipynb
│   ├── tratamento_silver.ipynb
│   └── agregacoes_gold.ipynb
│
├── src/                # Funções auxiliares e scripts reutilizáveis
│   └── funcoes_tratamento.py
│
├── README.md
└── requirements.txt    # Dependências do projeto
```

---

## 📈 Etapas do Pipeline

1. **Ingestão dos dados brutos** (camada Bronze)
2. **Limpeza e padronização** (camada Silver)
3. **Criação de métricas e indicadores** (camada Gold)
4. **Geração de gráficos e análise exploratória**
5. (opcional) Exportação dos dados finais

---

## 🧠 Aprendizados Esperados

- Boas práticas com pandas e organização de dados
- Tratamento e estruturação de datasets em múltiplas camadas
- Escrita de código reutilizável e documentado
- Documentação de processo e criação de portfólio
- Simulação de ambiente de engenharia de dados local

---

## ✍️ Autor

Gabriel Centeno  
Estudante de Engenharia de Dados | Trilha Analytics Engineer  
[LinkedIn](https://www.linkedin.com/in/seu-usuario)  
[Portfólio](https://github.com/seu-usuario)

---

> 💡 *Este projeto é parte de uma trilha prática de aprendizado, com foco em desenvolver habilidades reais para atuar no mercado como Analytics Engineer.*
