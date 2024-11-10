# Case_beAnalytic
Este projeto resolve o problema proposto no processo seletivo da beAnalytic para Engenheiro de Dados
# SteamDB Sales Data Extraction Project

Este projeto foi desenvolvido como parte de um processo seletivo para uma vaga de Engenheiro de Dados Júnior na beAnalytic. Ele consiste em extrair dados de jogos em promoção na [SteamDB](https://steamdb.info/sales/), processá-los e carregá-los no Google BigQuery, com uma conexão pública para visualização no Google Sheets.

## Descrição do Projeto

A automação captura informações sobre jogos em promoção na SteamDB, incluindo:
- Nome do Jogo
- Preço
- Percentual de Desconto

Esses dados são processados e carregados em uma tabela no Google BigQuery, que é conectada a uma planilha pública no Google Sheets, permitindo a visualização dos dados de forma organizada e acessível.

## Estrutura do Projeto

- **data_extraction.py**: Script principal que utiliza Selenium para coletar dados diretamente da SteamDB.
- **README.md**: Documentação do projeto.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Selenium**: Para automação de coleta de dados diretamente da página da SteamDB.
- **Google BigQuery**: Para armazenamento dos dados coletados.
- **Google Sheets**: Para visualização pública dos dados. (https://docs.google.com/spreadsheets/d/1GPMU4_Q76Y-4Kv9_LFUyxC4sWSZJnu_keqzxk23_yT0/edit?usp=sharing)

## Instruções de Execução

1. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/steamdb-sales-extraction.git
   cd steamdb-sales-extraction
