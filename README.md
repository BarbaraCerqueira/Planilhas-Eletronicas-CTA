# Planilhas-Eletronicas-CTA
Este repositório foi criado para armazenar os arquivos do trabalho "Avaliação 01: Uso de Planilhas Eletrônicas para CTA de dados", da cadeira de Top Esp em Engenharia de Dados, UFRJ 2024.2.

## Descrição
Este projeto realiza a análise de dois conjuntos de dados públicos utilizando o Microsoft Excel, com foco nas tarefas de carga, transformação e análise de dados. Os datasets analisados são:

- Perfil do Eleitorado - Eleições Municipais  (TSE): Comparação entre os perfis de eleitores de dois estados brasileiros, RO e RR.

- Dados Meteorológicos (INMET): Comparação dos dados de 2003 e 2004 da estação A807.

O objetivo do projeto é aplicar técnicas de manipulação de dados, visualização gráfica e geração de insights com base em dados reais, desenvolvendo habilidades de análise com MS-Excele Power Query.

## Estrutura do Projeto
``Dataset 1:`` Perfil do Eleitorado (TSE)
Analisamos dados do eleitorado para as eleições municipais de RO e RR, utilizando as seguintes colunas:

- NM_MUNICIPIO
- CD_GENERO / DS_GENERO
- CD_ESTADO_CIVIL / DS_ESTADO_CIVIL
- CD_FAIXA_ETARIA / DS_FAIXA_ETARIA
- CD_GRAU_ESCOLARIDADE / DS_GRAU_ESCOLARIDADE
- QT_ELEITORES_PERFIL

As tarefas envolveram projeção (eliminação de colunas), filtragem de dados, cálculo de estatísticas básicas e uso de tabelas dinâmicas para responder perguntas específicas sobre o perfil eleitoral dos municípios selecionados.

``Dataset 2:`` Dados Meteorológicos (INMET)
Comparação entre os dados meteorológicos de dois anos consecutivos de uma única estação automática, com foco nas seguintes variáveis:

- DATA
- HORA
- Precipitação Total
- Pressão Atmosférica
- Temperatura Máxima, Mínima e Média

A análise inclui filtragem de dados, eliminação de outliers, estatísticas básicas e uso de tabelas dinâmicas para agrupar e visualizar os dados por período (mensal, trimestral, etc.).