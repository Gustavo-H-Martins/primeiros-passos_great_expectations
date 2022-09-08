# Primeiros passos com o tutorial Great Expectations - API v3 (Batch Request)
Este repositório contém a versão final do tutorial "Introdução ao Great Expectations" na documentação do Great Expectations. Este repositório pode ser usado como uma demonstração e para explorar uma implantação completa do Great Expectations.

## **ESTA VERSÃO FOI CRIADA COM A API V3 (BATCH REQUEST) GREAT EXPECTATIONS** , que está disponível na versão Great Expectations 0.13.xe superior.

## 1. Como percorrer o tutorial
[Por favor, siga o tutorial em nossos documentos para obter instruções!]((https://docs.greatexpectations.io/en/latest/guides/tutorials/getting_started_v3_api.html))

## 2. Como usar este repositório para explorar e demonstrar Great Expectations
### O 'data' diretório
Os arquivos CSV no diretório de dados são dados de viagem de táxi amarelo que foram baixados do site de dados de táxi de Nova York:

* [Dados de registro de viagem TLC*](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
* [Dicionário de dados](https://www1.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

Criamos 10.000 amostras de linha (usando a função ''sample'' Pandas) dos arquivos CSV originais por conveniência e adicionamos manualmente algumas alterações importantes (0s na coluna Contagem_passageiro) para demonstrar possíveis problemas de dados.


O diretório 'great_expectations'
Atualmente, esta demonstração contém o seguinte:

* Um arquivo 'great_expectations.yml' configurado para usar o diretório de nível superior datacomo uma fonte de dados. Você não precisará configurar nada para fazê-lo funcionar.
* Um único conjunto de expectativas, 'taxi.demo', contendo um punhado de expectativas simples
* Um ponto de verificação 'my_chk' configurado para executar o conjunto no conjunto de dados de fevereiro

####	Local
* [link do exemplo](file:///C:/Users/gusta/ge_tutorials/great_expectations/uncommitted/data_docs/local_site/expectations/primeiros_passos_great-expectation-suite-taxi/demo.html#section-1)