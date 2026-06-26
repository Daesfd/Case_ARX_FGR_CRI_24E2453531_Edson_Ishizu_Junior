# Instruções para execução

1. Baixe ou clone este repositório.

2. Instale as dependências necessárias:
pip install pandas numpy scipy camelot

3. Com o jupyter-notebook, abra calculadora.ipynb (./case_arx/steps/calculo/calculadora.ipynb)
  
4. Execute as células de forma apresentada.

5. A calculadora permite:
Informar uma taxa de desconto e obter o PU do CRI;
Informar um PU e obter a taxa implícita;

Os arquivos de dados utilizados devem estar condizentes na mesma pasta do case, especialmente:
df_fluxo.csv

# Dependências utilizadas

O projeto foi desenvolvido em Python e utiliza as seguintes bibliotecas:

- pandas: manipulação e tratamento das bases de dados;
- numpy: cálculos numéricos;
- scipy: cálculo da taxa implícita por métodos numéricos;
- camelot: leitura do pdf do Termo de Securitização;
