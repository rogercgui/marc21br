---
layout: default
title: Apresentação
nav_order: 000
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---




# Apresentação


Com objetivo de associar o uso dos campos do MARC21 às regras de catalogação, este material foi organizado seguindo a ordem numérica dos campos do MARC21, com conceitos, observações e exemplos. Os exemplos foram extraídos do livro de Antonia Motta de Castro Memória Ribeiro. Catalogação de recursos bibliográficos: AACR2 em MARC 21. 6. ed. Brasília: Três em Um, 2015.

{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


## Visão geral

O MARC (**MA**chine **R**eadable **C**ataloging) – Registro Catalográfico Legível por Máquina foi desenvolvido na década de 60 pela Library of Congress com o propósito de:

- padronizar a representação descritiva automatizada dos registros bibliográficos
- permitir a troca das informações bibliográficas entre bibliotecas
- possibilitar a catalogação cooperativa

## Formato MARC21
 
- 1965 – Projeto piloto – Library of Congress e mais 16 bibliotecas
- 1967 – OCLC (Ohio College Library Center) – 1o. Banco de dados bibliográfico
- 1983 – o LC Marc se transformou em USMARC

No final dos anos 90 – unificação do USMARC com o CANMARC formando o MARC 21.


# Conceitos básicos
Base de dados: Conjunto estruturado de dados armazenados em meio legível por computador, no qual o nível de padronização de dados é alto.

- **Registro**: Conjunto de todas as informações relativas a um item de uma base de dados.

- **Campo**: Espaço definido para cada unidade de informação de um registro. É uma área definida na qual o mesmo tipo de informação é cadastrada consistentemente.

- **Subcampo**: Subdivisão do campo. Subcampos são as menores unidades lógicas de informação em um campo variável. Representam o nível inferior de designação de conteúdo no MARC. Códigos de subcampos (letras ou números) identificam subcampos e são precedidos por delimitadores de subcampos (/).

- **Indicador**: Valor associado a um campo, sinalizando que o dado contido no campo necessita de algum processamento especial. Os indicadores contêm informações sobre o campo para indexação, produção de fichas, ou outras funções do sistema. Os números em posições de indicadores têm significados pré-determinados.

- **Campo ou subcampo repetitivos**: É o campo que pode ocorrer mais de uma vez no mesmo registro, ou o subcampo que pode ocorrer mais de uma vez no mesmo campo.

- **Campo ou subcampo obrigatório**: É o campo ou subcampo cujo preenchimento é necessário e obrigatório para consistência dos dados.

- **Campos fixos**: Campos que possuem tamanho (ou largura) fixo. O primeiro campo no registro é o campo fixo. Etiquetas mnemônicas identificam os elementos que contêm informações codificadas descrevendo o item e o próprio registro.

- **Campos variáveis**: Campos que possuem tamanho (ou largura) variável. O tamanho está de acordo com o dado contido no campo.

- **ISO 2709**: Norma que define a estrutura do arquivo físico que permite o intercâmbio de informações. É um formato padrão de comunicação para registros bibliográficos, utilizado para intercâmbio de registros em meio magnético de um sistema para outro.

- **Z39.50**: Protocolo de comunicação entre servidores de bases de dados.

## Etiquetas

As etiquetas identificam os campos variáveis e são agrupadas numericamente por função. XX indica um valor numérico entre 00 e 99.

- **0XX** = Números de controle bibliográfico e informações codificadas

- **1XX** = Entrada principal

- **2XX** = Área de títulos e indicação de responsabilidade; edição, imprenta

- **3XX** = Área de descrição física etc

- **4XX** = Área de série

- **5XX** = Área de notas

- **6XX** = Entradas secundárias de assunto

- **7XX** = Outras entradas secundárias; campos de ligação ou relacionados

- **8XX** = Entradas secundárias de série

- **9XX** = Livre para cada biblioteca definir conforme suas necessidades

Dentro dos blocos 1XX, 4XX, 6XX, 7XX e 8XX, algumas indicações de conteúdo se repetem. Os dois caracteres finais nestes blocos possuem os seguintes significados.

- **X00** = Nomes pessoais

- **X10** = Nomes corporativos

- **X11** = Nomes de eventos

- **X30** = Títulos uniformes

- **X40** = Títulos bibliográficos

- **X50** = Termos tópicos

- **X51** = Nomes geográficos

