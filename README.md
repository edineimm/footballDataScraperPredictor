# ⚽ Football Data Scraper & Predictor

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white)

Este projeto é uma ferramenta completa de **Web Scraping** e **Processamento de Dados** focada na Premier League (e expansível para outras ligas). Ele automatiza a coleta de estatísticas históricas detalhadas e a captura de confrontos futuros (fixtures), servindo como base para modelos de Machine Learning e análise de performance.

## 🚀 Funcionalidades

-   **Extração Histórica:** Coleta de resultados, posse de bola, chutes a gol e métricas avançadas de temporadas passadas.
-   **Agenda de Futuros Jogos:** Script dedicado para buscar as próximas partidas e preparar o dataset de predição.
-   **Limpeza de Dados Automatizada:** Pipeline que transforma HTML bruto em DataFrames organizados e prontos para análise.
-   **Exportação Flexível:** Salve seus dados em formatos amigáveis como `.csv` ou `.json`.

## 🛠️ Tecnologias Utilizadas

-   **Python:** Linguagem base do projeto.
-   **Pandas:** Manipulação e estruturação de dados.
-   **BeautifulSoup4 / Requests:** Para raspagem eficiente das páginas web.
-   **Jupyter Notebook:** Para exploração visual e prototipagem rápida.

## 📁 Estrutura do Projeto

```text
footballDataScraperPredictor/
├── data/                   # Pasta para armazenamento dos CSVs gerados
├── notebooks/
│   └── premier_league.ipynb # Script principal de scraping e análise
├── .gitignore              # Arquivos ignorados (ex: venv, caches)
└── README.md
