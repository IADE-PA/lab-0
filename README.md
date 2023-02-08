# Programação e Algoritmos 2022 2023 - [IADE UE](https://www.iade.europeia.pt/)

## Laboratório 0

Este laboratório pretende recuperar a prática de programação em C, e motivar a discussão sobre complexidade algorítmica.

Objetivo é construir uma aplicação que analisa o comportamento do preço da [Bitcoin](https://en.wikipedia.org/wiki/Bitcoin) no último ano.

Os dados de mercado a utilizar estão disponíveis no ficheiro [btc.csv](btc.csv) [Fonte: [coinmarketcap](https://coinmarketcap.com/currencies/bitcoin/historical-data/)].

# Tarefas 

## Tarefa 1

Defina um tipo de dados (`struct`) para representar a informação relativa a um dia de negociação, de acordo com as dimensões do ficheiro de dados.

## Tarefa 2

Efetue a leitura da informação para um *array*.

## Tarefa 3

Calcule e mostre as seguintes estatísticas:

- Média de preço de fecho no último ano;
- Os cinco dias com maior/menor preço de fecho no ano;
- Os cinco dias com maior diferença entre preço de abertura e de fecho no ano;
- O mês com maior valorização, i.e., diferença entre os preços de fecho entre o último e o primeiro dia.

## Tarefa 4

Construa uma série de rendibilidades diárias.

A rendibilidade diária é definida como o rácio entre o preço de fecho atual e o anterior.

## Tarefa 5

Escreva a série de rendibilidades diárias num ficheiro csv.

## Extra

Construa testes unitários para cada função implementada.
