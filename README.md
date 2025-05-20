# OlistDataset

# 🚀 Desafio Técnico de Análise de Dados – Triggo

Este repositório contém a solução completa para o desafio técnico proposto pela Triggo, utilizando Python, SQL e bibliotecas de visualização de dados.

## 🧠 Objetivo

Analisar dados de um e-commerce brasileiro (base Olist) a fim de responder a questões analíticas e de negócio, envolvendo:
- Preparação de dados
- Modelagem relacional
- Análise exploratória
- Predição
- Segmentação de clientes
- Visualizações e dashboards

- 🛠️ Tecnologias Utilizadas
	•	Python (pandas, numpy, matplotlib, seaborn, plotly)
	•	SQL com SQLite3 (via pandas + SQLite)
	•	Jupyter Notebook
	•	Conda / Miniconda para ambiente virtual

## 📦 Etapas do Projeto

# 1. Preparação dos Dados
	•	Leitura dos arquivos CSV
	•	Tratamento de valores nulos e duplicados
	•	Normalização de colunas (strings, datas, valores numéricos)
	•	Diagnóstico automatizado por coluna
	•	Criação de modelo relacional via SQL
	•	Junção de tabelas em uma base unificada: base_geral

# 2. Análise Exploratória de Dados (EDA)
	•	Volume de pedidos por mês (com análise de sazonalidade)
	•	Distribuição do tempo de entrega
	•	Relação entre frete e distância
	•	Categorias de produtos com maior faturamento
	•	Estados com maior ticket médio

# 3. Soluções de Negócio
	•	Análise de Retenção: cálculo de clientes recorrentes
	•	Predição de Atraso: modelo de classificação simples (Random Forest)
	•	Segmentação de Clientes: usando KMeans
	•	Análise de Satisfação: relação entre nota, categoria, tempo e valor

# 4. Visualizações e Dashboards
	•	Evolução de vendas por mês
	•	Faturamento por estado
	•	Avaliação x tempo de entrega
	•	Desempenho de vendedores (vendas, avaliações, entrega)
 
# 📊 Principais Resultados
	•	Identificação de sazonalidade nas vendas
	•	Descoberta de relação entre frete e distância
	•	Mapeamento dos melhores estados e categorias por receita
	•	Insight sobre atraso e impacto na satisfação do cliente
	•	Segmentos de clientes com comportamentos distintos
 
# 📌 Observações
	•	Todos os dados utilizados são públicos e provenientes do Kaggle:
     Olist Brazilian E-Commerce Dataset
	•	A base foi unificada em SQL dentro do próprio notebook com uso de SQLite via pandas.
 

