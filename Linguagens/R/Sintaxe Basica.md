# Sintaxe Básica de R

## Vetores e Listas

- **Vetores**: guardam valores do mesmo tipo.
- **Listas**: guardam valores de qualquer tipo, inclusive outras listas


### Criando vetores

```R
# cria um vetor de números reais
c(2.5, 48.5, 10.4)

# cria um vetor de números inteiros
c(1L, 2L, 5L)

# cria um vetor de strings
c("hello", "world")

# cria um vetor de booleans
c(TRUE, FALSE, FALSE)

# cria um vetor e atribui para a variável v
v <- c(2.4, 5.6, 6.7)
```

### Funções de vetores

```R
# função para identificar o tipo do vetor
typeof(c("a", "b"))

# função para identificar o tamanho do vetor
v <- c(2.4, 5.6, 6.7)
length(v)

# função para verificar se um vetor é de um determinado tipo
is.integer(v)
is.logical(v)
is.double(v)
is.character(v)

# função para nomear um vetor
x <- c(1, 3, 5)
names(x) <- c("a", "b", "c")
# o primeiro elemento do vetor passa a se chamar a, o segundo b e o terceiro c
```

### Criando listas

```R
# Criando listas
list("a", 1L, TRUE, 1.4)
list(list(1L, 2L, 3L), TRUE, 2.3)
```

### Funções de listas

```R
# determinando os tipos de elementos que a lista contém
str(list("a", 1L, TRUE, 1.4))

# nomeando listas
list('Banana' = 1, 'Chocolate' = 2, 'Queijo' = 3)
# assim, o primeiro elemento se chama Banana, o segundo Chocolate e o terceiro Queijo
``` 

## Datas e tempos

Para trabalhar com datas e tempos no R, precisamos carregar um pacote chamado `lubridate` que faz parte do pacote `tidyverse`. Tidyverse é uma coleção de pacotes feita para trabalhar com dados, é o pacote padrão para isso.

```R
# instalando o pacote tidyverse
install.packages("tidyverse")
# carregando pacotes
library(tidyverse)
library(lubridate)
```

### Funções de data e tempo

```R
# Uma data
("2022-12-01")
# Um tempo
("20:11:00 UTC")
# Uma data e hora
("2022-01-12 22:20:00 UTC")
# função para ver a data do dia
today()
# função para ver a data e hora daquele instante
now()
# converte strings em tempo
mdy("01-23-2022") # retorna "2021-01-20"
dmy("20-Jan-2021") # retorna "2021-01-20"
ymd(20210120) # retorna "2021-01-20"
# cria data e tempo de uma string
ymd_hms("2021-01-20 20:11:59")
mdy_hm("01/20/2022 10:10")
```

## Data Frames

Forma de armazenar dados em R, semelhante a uma tabela, a primeira linha deve conter o nome de cada coluna e cada coluna deve ter o mesmo tipo de dado

```R
# Cria um data frame
data.frame(x = c(1, 2, 3) , y = c(1.5, 5.5, 7.5))
# resultado: 
#   x   y
# 1 1 1.5
# 2 2 5.5
# 3 3 7.5
```

## Tibbles

Tibbles são como data frames em linha, que são configurados para mostrar as 10 primeiras linhas de um dataset e apenas as colunas que couberem na tela. Tibbles nunca mudam o nome de suas colunas nem o tipo das variáveis. São parte do pacote Tidyverse.

### Criando Tibbles

```R
# carrega a biblioteca Tidyverse que contém os tibbles
library(tidyverse)
# cria um tibble do data frame diamonds
tibble_table <- as_tibble(diamonds)
```

## Arquivos

```R
# função para criar uma nova pasta
dir.create("folder")
# função para criar um arquivo
file.create("file.csv") # retorna TRUE se conseguiu criar se não FALSE
# copia um arquivo para uma pasta
file.copy("file.txt", "folder")
# deleta um arquivo
unlink("file.txt")
```