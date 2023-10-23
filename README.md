# SistemaRecomendacao_analisedataset_MovieLens

## Descrição Projeto

**Conjunto de dados:**
Para esse projeto, utilizou-se um dataset com 3 arquivos:
- `ratings.parquet`: avaliações de usuários para filmes em um determinado timestamp
- `movies.parquet`: metadados dos filmes
- `users.parquet`: metadados dos usuários

**Arquivo:** .parquet

**Objetivo:**
Realizar uma análise exploratória e analítica em arquivos de um dataset baseados em avaliações de usuários para filmes coletados através de uma interface web.

**IDE:** Colab

**Linguagem:** Python 

**Principais bibliotecas utilizadas:**
•	Cycler, para personalizar cores em gráficos;
•	Pandas, para manipulação e tratamento dos dados;
•	Matplotlib, para criação e visualização de gráficos;
•	Google.colab, para importar arquivos da núvem;
•	Datetime, para manipulação de dados no formato de data.

**Sequencia processos:**
1° Instalação bibliotecas; 
2° Carregar datasets;
3° Pré Processamento dos dados;
- Extrair a data do campo timestamp
- Extrair o ano de lançamento do filme, que consta junto ao título
- Converter a string concatenada de gêneros em uma lista de gêneros
4° Realizar análise na distribuição dos gêneros dos filmes;
5° Realizar análise na distribuição das avaliações dos filmes;
6° Realizar análise na evolução temporal das avaliações dos filmes;
7° Realizar duas análises de esparsisidade:
- Esparsisidade Geral: entre avaliação / usuário / item 
- Esparsisidade Específica: entre Usuário / item

Análise da Esparsidade: Um dos fatores que mais impactam os sistemas de recomendação (sobretudo os baseados em filtragem colaborativa) é a esparsidade do cenário onde eles são aplicados. De uma forma resumida, a esparsidade pode ser entendida como uma medida da falta de informação.

**Resultado:**
Através da sequência de processos realizadas, foi possível realizar uma análise dos dados que envolvem os arquivos do dataset desse projeto, facilitando a criação de códigos futuros para sistemas de recomendação.
