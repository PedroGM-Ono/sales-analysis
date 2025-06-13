# 📊 Sales Analysis

Este projeto simula um pipeline completo de dados de vendas, desde a geração de uma base fictícia com inconsistências até a limpeza, análise exploratória e construção de um relatório final orientado ao negócio.

## 🎯 Objetivo

Demonstrar habilidades em criação, manipulação, limpeza e análise de dados com foco em resultados de negócio. O projeto foi desenvolvido como um case para uma vaga de emprego (com dados e nomes genéricos, sem vinculação à empresa original).

## 🧱 Estrutura do Projeto

O repositório está dividido em duas etapas principais:

1. **Geração de Dados Fictícios**  
   - Criação de base sintética de vendas  
   - Inclusão proposital de inconsistências e valores ausentes  
   - Exportação da base em formato `.xlsx`

2. **Análise de Dados e Relatório**  
   - Importação e limpeza dos dados  
   - Cálculo de KPIs (faturamento, ticket médio, variação percentual etc.)  
   - Visualizações com gráficos de linha, barras, pizza e mapas de calor  
   - Construção de relatório de negócios com hipóteses e recomendações

## 🛠️ Tecnologias e Bibliotecas

- Python 3.13.3
- Jupyter Notebooks  
- pandas  
- numpy  
- matplotlib  
- seaborn

## 📁 Arquivos Principais

- `GenerateMockData.ipynb` — Gera os dados fictícios
- `sales_mock_case.ipynb` — Realiza a limpeza, análise e visualizações
- `Relatório de Vendas.pdf` — Apresentação com insights para o negócio
- `requirements.txt` — Bibliotecas utilizadas

## 🖼️ Exemplos de Visualizações

Inclui:

- Gráfico de linha com faturamento mensal  
- Gráfico de barras empilhadas por categoria e produto  
- Mapa de calor de vendas por região  
- Ranking dos principais clientes por valor de compra  

*(ver slides da apresentação ou outputs do notebook)*

## 🚨 Alertas e Insights

- Produtos de maior valor unitário concentram o maior faturamento  
- Cancelamentos se concentram nas categorias de Esportes e Eletrodomésticos na Região Norte  
- Sugestão de ações comerciais e logísticas baseadas na análise regional e por categoria

## 🧪 Como Executar

Crie um ambiente virtual e instale as dependências:

```bash
python3 -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt 
```

Abra os notebooks com JupyterLab ou Jupyter Notebook.

## 📌 Observações

Os dados são totalmente fictícios e foram gerados para fins educacionais.

Este projeto é voltado tanto a profissionais técnicos (análise) quanto à tomada de decisão de negócio (relatório final).
