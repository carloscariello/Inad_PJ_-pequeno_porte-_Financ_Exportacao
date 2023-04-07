# Análise da Taxa de Inadimplência de Pessoa Jurídica - Pequeno Porte - Recursos Livres - Financiamento à Exportação

Este projeto tem como objetivo analisar a taxa de inadimplência de pessoa jurídica por origem dos recursos e modalidade de crédito para pequeno porte, com foco nos recursos livres e financiamento à exportação. Os dados são provenientes do Sistema de Informações de Crédito.

## Fonte dos Dados

Os dados utilizados neste projeto são fornecidos pelo Banco Central do Brasil através da API BCData/SGS - Sistema Gerenciador de Séries Temporais. 

Link para a API: https://api.bcb.gov.br/dados/serie/bcdata.sgs.{codigo_serie}/dados?formato=json&dataInicial={dataInicial}&dataFinal={dataFinal}

## Estrutura do Projeto

O projeto consiste em um Jupyter Notebook que realiza as seguintes tarefas:

1. Importação dos dados usando a API do Banco Central do Brasil.
2. Pré-processamento e limpeza dos dados.
3. Análise estatística dos dados, incluindo cálculo da média, máximo e mínimo da taxa de inadimplência.
4. Geração de gráficos para visualização dos dados.

## Requisitos

Para executar este projeto, você precisará das seguintes bibliotecas Python:

- Pandas
- NumPy
- Matplotlib
- Requests

Você pode instalar essas bibliotecas usando o seguinte comando:

pip install pandas numpy matplotlib requests


## Como executar o projeto

1. Clone este repositório para o seu computador local.
2. Abra o arquivo Jupyter Notebook (`analise_taxa_inadimplencia.ipynb`) usando o Jupyter.
3. Execute todas as células do notebook para obter os resultados da análise e visualizações.

## Contribuindo

Sinta-se à vontade para contribuir com este projeto, seja corrigindo bugs, adicionando novas funcionalidades ou melhorando a documentação. Para contribuir, crie um fork deste repositório, faça as alterações desejadas e envie um pull request.

## Licença

Este projeto é licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para obter detalhes.


## Notas

Este arquivo README e o código contido nesse repositório foram escritos para demonstrar a capacidade do ChatGPT 4.0
