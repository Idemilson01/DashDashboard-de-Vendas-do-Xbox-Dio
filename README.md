# Desafio: Dashboard de Vendas no Excel

Projeto desenvolvido como parte de um desafio com o objetivo de criar um dashboard de vendas interativo no Microsoft Excel, transformando dados brutos em insights visuais.

## 🎯 Objetivo do Projeto

O objetivo principal era organizar uma base de dados de vendas e construir um painel visual que permitisse a análise de performance através de indicadores chave (KPIs) e gráficos dinâmicos, facilitando a tomada de decisões estratégicas.

## 📊 Dados Utilizados

A fonte de dados foi o arquivo `base.xlsx`, contendo registros de vendas com as seguintes informações:
* ID-Venda
* Data da Venda
* Loja
* Produto
* Quantidade Vendida
* Preço Unitário

Foi criada uma coluna adicional, **"Faturamento Total"**, calculada pela multiplicação da `Quantidade` pelo `Preço Unitário`.

## 🛠️ Ferramentas e Técnicas Utilizadas

* **Microsoft Excel**
    * **Formatação como Tabela:** Para estruturar os dados e garantir a atualização dinâmica.
    * **Tabelas Dinâmicas (Pivot Tables):** Para sumarizar os dados e servir como base para os gráficos.
    * **Gráficos Dinâmicos:** Para a visualização dos dados (Gráficos de Barras, Linha e Anel).
    * **Segmentação de Dados (Slicers):** Para criar filtros interativos que afetam todo o dashboard.
    * **Fórmulas:** Para criação da coluna calculada de faturamento.

## 📈 Análises Apresentadas no Dashboard

O dashboard finalizado (`seu_nome_de_arquivo.xlsx`) inclui as seguintes análises:

1.  **KPI de Faturamento Total:** Um cartão com o valor total de vendas no período selecionado.
2.  **Faturamento por Loja:** Um gráfico de barras comparando o desempenho de cada loja.
3.  **Faturamento por Produto:** Um gráfico de anel mostrando a contribuição de cada produto para o faturamento.
4.  **Evolução do Faturamento no Tempo:** Um gráfico de linha mostrando as vendas ao longo dos meses.

## 🚀 Como Utilizar

1.  Faça o download do arquivo `.xlsx` deste repositório.
2.  Abra o arquivo no Microsoft Excel.
3.  Navegue até a aba **"Dashboard"**.
4.  Utilize os filtros de **Loja** e **Produto** no lado esquerdo para interagir com os dados e ver os gráficos se atualizarem em tempo real.
