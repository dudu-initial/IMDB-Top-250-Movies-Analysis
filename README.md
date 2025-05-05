# IMDB-Top-250-Movies-Analysis

# Análise dos 250 Melhores Filmes do IMDb

Este projeto consiste em uma análise exploratória dos 250 filmes mais bem avaliados segundo o IMDb, utilizando Python e Jupyter Notebook. Através de gráficos, estatísticas e visualizações, buscamos identificar padrões, tendências e curiosidades sobre os filmes mais aclamados do cinema.

## Objetivos

- Entender as características mais comuns dos filmes com altas avaliações.
- Analisar a distribuição de notas, anos de lançamento e gêneros.
- Identificar diretores e atores mais recorrentes.
- Criar visualizações informativas e interativas.

## Estrutura do Projeto

- `IMDb_Top_250_Analysis.ipynb`: notebook principal com toda a análise e visualizações.
- `imdb_top_250.csv`: arquivo com os dados dos filmes (ou link para a fonte, se for scrape).
- `imgs/`: pasta com capturas de gráficos (opcional).
- `README.md`: documentação do projeto.

## Tecnologias Utilizadas

- Python 3.7
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## ▶️ Como Executar

1. Clone o repositório:
   git clone https://github.com/dudu-initial/IMDB-Top-250-Movies-Analysis.git

2. Instale as dependências (de preferência num ambiente virtual):
  pip install -r requirements.txt

Ou manualmente:
  pip install pandas numpy matplotlib seaborn

3. Abra o Jupyter Notebook:
  jupyter notebook IMDb_Top_250_Analysis.ipynb

# Exemplos de Visualizações:

- Aqui estão algumas visualizações produzidas no projeto:

1. Quantos filmes foram lançados por década?
2. Qual o filme mais antigo e o mais recente?
3. Qual é o filme com a maior nota?
4. Existe uma relação entre a duração do filme e sua nota?
5. Qual é a distribuição dos filmes por ano?
6. Os filmes mais antigos são melhor avaliados que os recentes?
7. Existem filmes muito longos na lista?

# Conclusões: 

- A maioria dos filmes está concentrada nas décadas de 1990 a 2010.
- Filmes mais longos tendem a ter notas ligeiramente maiores, embora a correlação seja fraca.
- A nota média dos filmes não varia muito com o ano de lançamento.
- Filmes com mais de 200 minutos são minoria, sendo o mais longo "Fanny and Alexander" com 312 minutos.
