# Explorando o pacote dplyr

[![CRAN status](https://www.r-pkg.org/badges/version/dplyr)](https://cran.r-project.org/package=dplyr)
![Tidyverse Certified](https://img.shields.io/badge/dplyr-Tidyverse%20Certified-blue)
![Powered by dplyr](https://img.shields.io/badge/Powered%20by-dplyr-9cf)


## Introdução 
dplyr é um pacote muito popular e útil para manipulação de dados em R e que fornece um conjunto de "verbos" que nos ajuda nos desafios enfrentados  durante o processo de manipução dos dados. 


## Principais características

- Funções intuitivas: dplyr nos disponiliza funções fáceis de entender com objetivos claros.

- Syntax consistente : Todas as funções seguem uma sintaxe padrão similar.

- Performance rápida: Muitas operações são otimizadas em C++ para performance.

- Amigável com operador pipe.


## Funções principais do dplyr

- filter(): Seleciona linhas baseado em condições específicas.
- select(): Seleciona colunas pelo nome/label.
- mutate(): Cria e altera colunas.
- arrange(): Organiza linhas/observações em ordem ascendente e descendente.
- summarize(): Realiza aggregações de dados e retorna um novo dataframe como output.
- group_by(): Agrupa dados para operações.


## Instalação

Antes de utilizar todas as funcionalidades deste pacote, primeiramente é necessário instalá-lo. Como uma questão de conveniência, sempre instalo o ambiente tidyverse, que é um conjunto de pacote que já carrega uma série dependências úteis a análise e Ciência de Dados. Porém, pode ser instalado e carregado apenas o dplyr indivualmente.

```{r}
# Instalando tidyverse
install.packages("tidyverse")

# Carregando tidyverge
library(tidyverse)
```
