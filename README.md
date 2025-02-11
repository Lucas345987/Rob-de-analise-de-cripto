# Rob-de-analise-de-cripto
# Robo_analista

Este repositório contém um notebook Jupyter (`Robo_analista.ipynb`) que realiza a análise de dados de criptomoedas utilizando a biblioteca `yfinance` para coletar dados históricos de preços de criptomoedas como Solana (SOL) e Ripple (XRP). O notebook também utiliza bibliotecas como `pandas`, `matplotlib`, e `mplcyberpunk` para manipulação de dados e visualização gráfica.

## Descrição do Projeto

O objetivo deste projeto é analisar os dados históricos de preços de criptomoedas, especificamente Solana (SOL) e Ripple (XRP), ao longo de um período de 6 meses. O notebook realiza as seguintes tarefas:

1. **Instalação de Dependências**: Instala as bibliotecas necessárias, como `pandas`, `yfinance`, `matplotlib`, e `mplcyberpunk`.
2. **Coleta de Dados**: Utiliza a biblioteca `yfinance` para baixar os dados históricos de preços das criptomoedas selecionadas.
3. **Manipulação de Dados**: Organiza os dados coletados em um DataFrame do `pandas` e realiza operações de manipulação de dados para facilitar a análise.
4. **Visualização de Dados**: Utiliza `matplotlib` e `mplcyberpunk` para criar gráficos que mostram a evolução dos preços das criptomoedas ao longo do tempo.

## Requisitos

Para executar o notebook, você precisará das seguintes bibliotecas Python:

- `pandas`
- `yfinance`
- `matplotlib`
- `mplcyberpunk`

Você pode instalar essas bibliotecas utilizando o `pip`:

```bash
pip install pandas yfinance matplotlib mplcyberpunk
```

## Como Executar

1. Clone este repositório para o seu ambiente local:

   ```bash
   git clone https://github.com/seu-usuario/Robo_analista.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd Robo_analista
   ```

3. Abra o notebook Jupyter:

   ```bash
   jupyter notebook Robo_analista.ipynb
   ```

4. Execute as células do notebook para realizar a análise de dados.

## Estrutura do Repositório

- `Robo_analista.ipynb`: O notebook Jupyter que contém o código para a análise de dados.
- `README.md`: Este arquivo, que fornece uma visão geral do projeto e instruções para execução.
