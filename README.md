# Sales-Analytics-Dashboard
Análise de dados de vendas e dashboard financeiro utilizando Python (Pandas) para tratamento e Power BI para visualização.

## 💡 Solução Implementada

Para resolver o problema de desorganização e falta de clareza, foi desenvolvido um pipeline de dados em duas etapas:

1. **Processamento de Dados (Python/Pandas):**
   - Ingestão e limpeza da base bruta (`.csv`).
   - Tratamento de tipos de dados (conversão de strings para datetime).
   - Engenharia de atributos: Criação da coluna `Faturamento_Total` para análise financeira.

2. **Dashboard Interativo (Power BI):**
   - Criação de um painel dinâmico focado em KPIs de Vendas e Financeiro.
   - **Segmentação e Filtragem:** Implementação de filtros temporais (Timeline) e geográficos (Mapas), permitindo ao usuário "fatiar" os dados para visualizar faixas específicas de vendas (ex: apenas Q1 de 2024 ou apenas Estado de SP).
   - **Cross-filtering:** Interatividade total entre os visuais para análises de profundidade.
  
   - ## 🛠️ Tecnologias Utilizadas

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

* **Python:** Utilizado para processamento de dados e engenharia de atributos.
* **Pandas:** Biblioteca principal para manipulação e limpeza dos dados (`data cleaning`).
* **Microsoft Power BI:** Ferramenta de Business Intelligence para construção do dashboard interativo e storytelling de dados.
