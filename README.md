# Trabalho Prático - Banco de Dados Geogtáficos

## Integrantes

* João Lucas Lage Gonçalves - 2020054552
* João Vítor Bicalho da Silva - 2020054579
* Pedro Renato Ferreira da Silva - 2020054757

## Introdução

Este trabalho tem como objetivo colocar em prática conceitos e princípios discutidos ao longo da disciplina usando dados de votação, mantidos pelo Tribunal Superior Eleitoral.

Nosso grupo ficou responsável por analisar os dados de votação para Deputados Federias das eleições de 2022, no estado do Ceará, e relacioná-los com dados geográficos do estado.

A primeira etapa desse trabalho foi feita usando o [Github](https://github.com/JoaoLucas23/BDG) para armazenamento dos arquivos e engenharia de dados, e o [...](https://) para a construção do Banco de Dados Geográficos.

## Metodologia

### 1. Aquisição de dados

Nessa etapa realizamos a coleta dos dados necessários para as análises.Foram coletados os seguintes dados:

* [Dados de votação para Deputados Federais no estado do Ceará, nas eleições de 2022, disponíveis no site do TSE.](https://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1/repositorio-de-dados-eleitorais)
* [Dados do Censo de 2022, disponíveis no site do IBGE.](https://www.ibge.gov.br/estatisticas/sociais/populacao/22827-censo-demografico-2022.html?edicao=39499&t=resultados)
* [Dados do IDH municipal no ano de 2010, disponíveis no site da Fundação João Pinheiro.](http://www.atlasbrasil.org.br/consulta/planilha)
* [Dados geográficos do estado do Ceará disponíveis no site do IPEA.](https://basedosdados.org/dataset/49ace9c8-ae2d-454b-bed9-9b9492a3a642?table=830ed269-41f9-461d-96f1-6a54b2e574ac)
* [Dados de furtos no estado do Ceará entre 2013 e 2022, disponíveis no site da SSP-CE.](https://www.sspds.ce.gov.br/indicadores-de-seguranca-publica/)

Os dados foram coletados em formato CSV e estão disponíveis na pasta `dados`.

### 2. Construção do BDG e Engenharia de Dados

Essa etapa foi dividida em duas partes: a Engenharia de Dados e a construção do Banco de Dados Geográficos.

#### Engenharia de Dados

A engenharia de dados foi realizada no arquivo `tratamento_de_dados.ipynb`. Nesse arquivo, realizamos a limpeza e transformação dos dados de votação, censo, IDH e furtos, para que eles pudessem ser inseridos no Banco de Dados Geográficos. Além disso foi feita uma análise exploratória inicial dos dados a fim de verificar as estatísticas básicas sobre os dados.

1. Carregamento dos dados
2. Padronização de nomes e tipos de dados das colunas
3. Filtragem dos dados
4. Agregação dos dados
5. Exploração dos dados

#### Banco de Dados Geográficos

### 3. Análises

pendente...

### 4. Visualização

pendente...
