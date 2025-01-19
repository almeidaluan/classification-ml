# ML - Dados Financeiros

Projeto responsavel por realizar analises voltadas ao mercado financeiro
## Tech/libs

- [Poetry] 
- [Numpy]
- [plotly]
- [yfinance] 
- [seaborn] 
- [matplotlib]

## Installation

Instalar o poetry e depois instalar o poetry shell
```sh
poetry self add poetry-plugin-shell
```
Ativar a criacao da env direto na pasta do projeto para instalacao das libs
```sh
poetry config --list
poetry config virtualenvs.in-project true
```

Dentro da pasta do projeto digitar

```sh
poetry shell
```

## Projeto
ex: Caso eu tenha segurado a acao do dia 2015-01-01 até o dia 2025-01-17

Comparacao historica dos precos normalizados(todos os precos divididos pelo menor valor,pegamos o menor valor do nosso range e dividimos todas as cotacoes pra no final saber se tivemos lucro ou prejuizo)

Prejuizo GOL4 / Prejuizo CVCB3 / Lucro 10% WEG3
![Image](https://github.com/user-attachments/assets/51d3a2c8-baa6-4e05-a743-c9ba23ff5778)



![Image](https://github.com/user-attachments/assets/3e83f445-d083-4b87-b9db-aa9b60edf2d9)
