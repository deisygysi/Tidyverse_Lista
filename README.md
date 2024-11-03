

### Tidyverse

1. Para esse exercício você deverá utilizar o banco de dados `chocolate.csv.gz`.

O dicionário das variáveis encontra-se disponível abaixo.


| Variável  | Descrição|
|-----------------------|-------------------------------------------------|
| local_compania  | Região do Fabricante|
| ano             | Ano da Revisão|
| origem_cacau    | País de Origem dos Grãos de Cacau|
| cocoa_percent   | Percentagem de Cacau (% chocolate)|
| ingredientes    | Ingredientes |
| caracteristicas | Características mais memoráveis daquele chocolate |

**Lista de ingredientes**:
"\#": representa o número de ingredientes no chocolate; 
B: Grãos, 
S: Açúcar, 
S\*: Adoçante diferente de açúcar de cana branco ou beterraba, 
C: Manteiga de Cacau, 
V: Baunilha, 
L: Lecitina, 
Sa: Sal


a. Quantos países produzem chocotale?
b. Quantos chocolates existem com pelo menos 3 ingredientes?
c. Quantos chocolates existem com 5 ingredientes?
d. Quantos chocolates existem com pelo menos 4 características memoráveis?
e. Quantos chocolates existem com Sal em sua composição?
f. Quantos chocolates existem com Baunilha em sua composição?
g. Quantos chocolates existem com Lecitina e Baunilha em sua composição?

2. Para esse exercício você deverá utilizar os banco de dados `Art.csv.gz` e `Art_Moma.csv.gz`. Desconsidere artistas sem nacionalidade e/ou sem nome. 

O dicionário das variáveis encontra-se disponível abaixo.

| variável                   | descrição                                                                                                           |
|----------------------------|---------------------------------------------------------------------------------------------------------------------|
| artist_name                |  O nome de cada artista                                                                                             |
| edition_number             |  O número da edição do livro.                 |
| year                       |  O ano de publicação de uma determinada edição do livro                                                 |
| artist_nationality         |  A nacionalidade de um artista.                                                                     |
| artist_nationality_other   |  A nacionalidade do artista |
| artist_gender              |  O gênero do artista                                                                                                |
| artist_race                | A raça do artista                                                                                                  |
| artist_ethnicity           |  A etnia do artista                                                                                                 |
| book                       | Qual livro, "Janson" ou "Gardner"                 |
| space_ratio_per_page_total |  A área em centímetros quadrados do texto e da figura de um determinado artista |
| artist_unique_id           |  O número de identificação exclusivo atribuído aos artistas            |
| moma_count_to_year         |  O número total de exposições já realizadas pelo Museu de Arte Moderna (MoMA) |
| whitney_count_to_year      |  O número de exposições realizadas pelo The Whitney  |
| artist_race_nwi           |  O indicador de raça não branca para a raça do artista |

a. Qual a média de exposições realizadas pelo MoMA e pelo Whitney por ano?

b. Qual a média de exposições realizadas pelo MoMA e pelo Whitney por ano para artistas de raça não branca?

c. Quais os quatro artistas com mais exposições realizadas pelo MoMA?

d. Do total de artistas, quantos são homens e quantos são mulheres?

e. Do total de artistas, qual as cinco nacionalidades predominante?

f. Dos artistas que expuseram no MoMA, quantos aparecem em cada livro? E dos que expuseram no Whitney?

g. Qual a média de espaço ocupado por página de cada artista?

3. Para esse exercício você deverá utilizar os banco de dados `refugiados_pais.csv.gz` e `refugiados.csv.gz`. Considere apenas observações completas.

a. Qual a média de refugiados por país?

b. Quantos refugiados houveram saíndo do Afeganistão em 1990? E a partir de 2000?

c. Crie a matriz de migração intercontinental (de -> para) de refugiados do ano 2005.

d. Qual o país que mais recebeu refugiados em 2005? E em 2010?

e. Quantos refugiados os 3 países que mais receberam refugiados em 2010 receberam em 2005?
