# Projeto de Análise de Vendas com Python

## Sobre o projeto

Este é um projeto inicial de análise de dados desenvolvido com Python. A proposta foi construir uma base sintética de vendas e, a partir dela, realizar etapas de exploração, checagem de qualidade, engenharia de atributos e análises descritivas com visualizações gráficas.

---

## Objetivo

O objetivo deste projeto foi praticar, de forma autoral, um fluxo básico de análise de dados, incluindo:

- geração de dados sintéticos
- organização da base
- exploração inicial do DataFrame
- checagem de qualidade dos dados
- criação de variáveis derivadas
- análises descritivas com apoio de gráficos

---

## Problema de negócio

Considerei o cenário de uma loja fictícia que deseja entender melhor seu desempenho comercial ao longo do ano de 2025.

A análise busca responder perguntas iniciais como:

- quais produtos tiveram maior e menor volume de vendas
- quais categorias concentraram maior faturamento
- como o faturamento variou ao longo dos meses
- quais regiões apresentaram maior participação no faturamento

---

## Etapas do projeto

- Importação de bibliotecas
- Geração de dados sintéticos
- Criação do DataFrame
- Exploração inicial dos dados
- Checagem de qualidade da base
- Engenharia de atributos
- Análise 1 - Desempenho de Vendas por Produto
- Análise 2 - Faturamento por Categoria
- Análise 3 - Evolução Mensal do Faturamento
- Análise 4 - Faturamento por Região

---

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git
- GitHub

---

## Estrutura da base

A base sintética foi construída com as seguintes variáveis:

- `ID_Pedido`
- `Data_Pedido`
- `Nome_Produto`
- `Categoria`
- `Preco_unitario`
- `Quantidade`
- `Estado`
- `UF`

Além disso, foram criadas variáveis derivadas para enriquecer a análise:

- `Faturamento`
- `Regiao`
- `Ano_Mes`

---

## Análises realizadas

### 1. Desempenho de Vendas por Produto
Comparação entre os produtos com maior e menor volume vendido, com base na soma da quantidade vendida por item.

### 2. Faturamento por Categoria
Análise da participação das categorias no faturamento total da base.

### 3. Evolução Mensal do Faturamento
Visualização da variação do faturamento ao longo dos meses de 2025.

### 4. Faturamento por Região
Comparação do faturamento entre as regiões geográficas representadas no conjunto de dados.

---

## Principais resultados

- Foi possível identificar diferenças de desempenho entre os produtos em termos de quantidade vendida.
- Algumas categorias concentraram parcela maior do faturamento total.
- O faturamento apresentou oscilações ao longo dos meses analisados.
- Houve diferença de faturamento entre as regiões presentes na base.

---

## Limitações do projeto

- Os dados utilizados são sintéticos e não representam um negócio real.
- A base foi construída com regras simplificadas de geração.
- As análises têm caráter descritivo e introdutório.
- O projeto não inclui variáveis como cliente, canal de venda, custo, margem de lucro ou estoque real.
- Os resultados devem ser interpretados como parte de um cenário simulado para fins de aprendizado.

---

## Próximos passos

- Trabalhar com datasets reais
- Aprofundar as análises com novas métricas
- Explorar indicadores como ticket médio e participação percentual
- Melhorar o storytelling analítico
- Desenvolver projetos mais robustos com bases reais e perguntas de negócio mais analíticas.

---

## Como executar o projeto

1. Clone este repositório
2. Abra o notebook no Jupyter Notebook
3. Execute as células em ordem para reproduzir a geração da base e as análises

---

## Arquivo do projeto

O desenvolvimento foi feito no notebook:

- `projeto_analise_vendas.ipynb`
