# EDIT-School-Projects
Projects made during my Data Science and Data Analytics course. 

## Análise de Dados de Automóveis - Módulo 4 Sessão 3

Este projeto é uma análise exploratória de dados baseada num dataset de automóveis. O foco principal está na identificação de **outliers** e na preparação de dados para análises futuras. O trabalho foi realizado no contexto do Módulo 4, Sessão 3 da formação em Ciência de Dados.

### 📂 Estrutura do Notebook

#### Parte I - Outliers

- Importação de bibliotecas essenciais: `pandas`, `numpy`, `matplotlib`, `seaborn`.
- Carregamento do dataset `carros3_AnaCintiaOliveira.csv`.
- Análise preliminar com `.info()` e `.describe()`.
- Limpeza inicial: remoção de colunas não essenciais (`width_std`, `mean_width`, `height_log`, `price_decile`).
- Análise de outliers com base em medidas estatísticas e visualizações - IQR, estandardização e decis.
- Comparação e análise da distribuição de variáveis, considerando as estandardização aplicada.
- Apreciação e impacto na correlação entre variávei.

#### Parte II

- Conversões e criações de variáveis (numérica - num-of-doors, dummy, casas decimais.
- Cálculo da amplititude e criação de niveis de price:alto,medio e baixo.
  
#### Parte III

- Exploração de dados utilizando boxplot, gráfico de barras, pie chart, scatter plot e heatmap

## 🧰 Tecnologias Utilizadas

- Python 3.x
- [pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- Google CoLab/Jupyter Notebook

## ▶️ Como Executar

1. Certifica-te de que tens o Python instalado ou acede ao Google CoLab.
2. Instala os pacotes necessários:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3. Abre o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4. Executa o ficheiro `Modulo_4_Sessão3_Exercicio_1_Ana_Cintia_Oliveira_.ipynb`.

## 👩‍💻 Autora

Projeto desenvolvido por **Ana Cíntia Oliveira**.

---

> Este projeto é parte de um exercício académico e pode ser expandido com visualizações, modelagem ou conclusões mais robustas.
