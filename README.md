# 🎬 Projeto Final - Computação em Nuvem ☁️

Este projeto consiste em uma análise exploratória de dados de avaliações de filmes, utilizando Python e Pandas em um ambiente Jupyter Notebook.

## 👨‍🎓 Aluno

- Daniel Moraes (dmms@cesar.school)

## 📁 Estrutura do Projeto

- `notebook.ipynb`: Notebook principal com todo o código e análises.
- `data/`: Pasta que deve conter os arquivos de dados (`customers_rating.csv` e `movies.csv`).

## 🚀 Como Executar

1. **Clone o repositório** (se aplicável) e acesse a pasta do projeto.
2. **Baixe os arquivos de dados**:
    - [customers_rating.csv](https://drive.google.com/file/d/1gLsCjaMrL91ECdThq58cZAzB9tPxG18g/view?usp=sharing)
    - [movies.csv](https://drive.google.com/file/d/1gLsCjaMrL91ECdThq58cZAzB9tPxG18g/view?usp=sharing)
3. **Coloque os arquivos baixados na pasta `data/`** dentro do diretório do projeto.
4. **Crie um ambiente virtual (.venv)**:
    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    ```
5. **Instale as dependências**:
    ```bash
    pip install pandas jupyterlab
    ```
6. **Abra o JupyterLab**:
    ```bash
    jupyter lab
    ```
7. **Abra o arquivo `notebook.ipynb`** e execute as células.

## 📊 Descrição das Análises

- **Importação e preparação dos dados**: Leitura dos arquivos CSV, renomeação de colunas e extração do ano dos títulos dos filmes.
- **Questões respondidas**:
    1. 🎞️ Quantidade de filmes disponíveis no dataset.
    2. 🏆 Os 5 filmes com melhor média de avaliação.
    3. 📉 Os 9 anos com menos lançamentos de filmes.
    4. ⭐ Quantidade de filmes com avaliação maior ou igual a 4.7 na última data de avaliação.
    5. 👥 Os 5 clientes que mais avaliaram filmes.

## ⚠️ Observações

- Os dados utilizados devem estar na pasta `data/` no mesmo diretório do notebook.
- O projeto utiliza apenas bibliotecas padrão do Python e o Pandas.

## 📄 Licença

Este projeto é apenas para fins educacionais.