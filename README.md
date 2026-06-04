

Projeto de iniciação científica voltado à análise de práticas de **Maximum Extractable Value (MEV)** e seus impactos sobre transações em exchanges descentralizadas (DEXs).

O trabalho investiga a ocorrência de **reordering slippage**, ataques **sandwich** e outros fenômenos relacionados ao MEV em redes Layer-2, utilizando dados históricos de swaps extraídos diretamente da blockchain e técnicas de análise quantitativa em Python.

## Objetivo

Avaliar quantitativamente o comportamento do slippage em redes Layer-2 e comparar os resultados com estudos realizados na Ethereum Mainnet, buscando compreender:

* A magnitude do reordering slippage em redes L2;
* O impacto econômico de atividades relacionadas ao MEV;
* A ocorrência de slippage adversário e slippage benigno;
* Diferenças entre ativos consolidados e ativos de alta volatilidade;
* Possíveis estratégias de mitigação para proteção dos usuários.

## Metodologia

### Coleta de Dados

Extração de dados históricos de swaps realizados em DEXs por meio de APIs públicas e indexadores blockchain.

### Processamento dos Dados

Tratamento, limpeza e análise dos dados utilizando Python e bibliotecas voltadas para ciência de dados.

### Análise Quantitativa

Cálculo de métricas relacionadas a:

* Preço de execução;
* Reordering Slippage;
* Impacto da ordenação das transações dentro dos blocos;
* Distribuição de eventos potencialmente associados a atividades MEV.

## Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Web3.py
* Blockchain Ethereum
* Polygon
* APIs RPC
* The Graph

## Resultados Esperados

* Quantificação do reordering slippage em redes Layer-2;
* Comparação com resultados observados na Ethereum Mainnet;
* Identificação de padrões associados a atividades MEV;
* Produção de métricas que contribuam para pesquisas futuras sobre segurança e eficiência econômica em DEXs.

## Licença

Este projeto possui fins acadêmicos e de pesquisa.
