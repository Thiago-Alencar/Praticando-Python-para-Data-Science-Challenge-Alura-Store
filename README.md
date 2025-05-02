# Praticando-Python-para-Data-Science-Challenge-Alura-Store
Com a resolução do desafio Alura Store, você experimentará diretamente o papel de um analista de dados no cotidiano, solucionando problemas com Python e visualização de dados através do Matplotlib. 



# Análise de Dados das Lojas - Relatório

## Propósito da Análise

Este relatório apresenta uma análise detalhada dos dados de vendas de quatro lojas, com o objetivo de auxiliar na decisão de venda de uma das unidades. A análise abrange o faturamento, categorias de produtos, avaliações de clientes, produtos mais/menos vendidos e custos de frete, comparando as lojas com e sem a presença de outliers.

## Estrutura do Projeto e Organização dos Arquivos

O projeto consiste neste único notebook Jupyter, que contém todo o código de importação, limpeza, análise e visualização de dados. Os dados originais das quatro lojas são importados diretamente de URLs do GitHub.  O DataFrame final consolidado é salvo em um arquivo CSV chamado 'lojas.csv' (no mesmo diretório onde o notebook é executado).

## Exemplos de Gráficos e Insights

O relatório inclui diversos gráficos para facilitar a interpretação dos resultados:

* **Gráfico de Barras:**  Exibe o faturamento total de cada loja, com e sem outliers, evidenciando como valores atípicos podem distorcer a percepção da performance.
* **Gráfico de Barras Agrupadas:** Mostra a distribuição das categorias de produtos vendidas em cada loja.
* **Gráfico de Dispersão:** Representa a média das avaliações de clientes em cada loja, também com e sem a consideração de outliers de preço.
* **Gráfico de Barras Horizontais:** Apresenta os produtos mais e menos vendidos em cada loja, permitindo uma comparação visual rápida.

Insights importantes obtidos:

* A Loja 4 apresenta o menor faturamento ajustado (sem outliers) e o menor custo médio de frete.
* A categoria 'moveis' é a mais popular em todas as lojas.
* A média de avaliações dos clientes é similar em todas as lojas.
* A Loja 4 apresenta um perfil de vendas de produtos diferente das outras três.

## Instruções para Executar o Notebook

1. **Ambiente:** Google Colaboratory ou Jupyter Notebook com as bibliotecas pandas, matplotlib e seaborn instaladas.
2. **Dados:** As URLs dos arquivos CSV são configuradas no início do notebook. Certifique-se de que essas URLs estejam corretas e que os arquivos CSV correspondentes estejam acessíveis.
3. **Execução:** Execute cada célula do notebook sequencialmente.
4. **Observação:** O código salva o DataFrame consolidado em um arquivo 'lojas.csv'. A localização deste arquivo depende de onde o notebook foi executado.


