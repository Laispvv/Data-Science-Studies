# Visualização eficiente de dados

## Método de McCandless
![imagem do método de McCandless](./../images/What-Makes-a-Good-Infoviz-frame.png)

1. 📊 **Informação (Information):** são os dados
2. 🎬 **História (Story):** uma narrativa do conceito
3. 🎯 **Objetivo (Goal):** o objetivo ou função da visualização
4. 🎨 **Forma Visual (Visual Form):** a forma de apresentar, a expressão visual

## 👀 Atributos Pre-attentive

Esses atributos são aqueles elementos da visuais que as pessoas **reconhecem** sem nenhum esforço, **de forma subconsciente**, eles são chamados de **Marks** e **Channels**

### Marks
São elementos visuais básicos, que possuem as seguintes características:
1. Posição
2. Tamanho
3. Formato
4. Cor

### Channels
São aspectos visuais que representam características dos dados, são Marks usados para visualizar dados. Possuem três características:
1. **Acurácia**: o quão útil foi para estimar o valor apresentado.
   1. Ex.: Cor pode ser útil para diferenciar categorias, mas é ruim para distinguir entre quantidades de dados parecidos
2. **Popout**: Quão fácil é distinguir um valor de outros.
   1. Pode se chamar a atenção para um valor com atributos como tamanho, cor, formato, intensidade, espessura de linha, etc.
3. **Agrupamento**: efetividade em comunicar grupos de dados existentes.
   1. Para comunicar grupos de dados pode-se usar a proximidade, similaridade de formato ou cor, etc. 

## ✅ Princípios do Design

- **Escolher o visual certo**: envolve saber quando usar uma tabela simples ou quando é necessário um gráfico complexo para apresentar os dados
- **Otimizar o data-ink ratio**: minimizar as cores, formas e sombras de elementos não essenciais para o entendimento e maximar daqueles que são.
- **Usar a orientação efetivamente**: torne títulos e legendas fáceis de ler mudando a orientação delas quando necessário.
- **Cor**: as cores devem ser usadas de forma consciente, com significado e consistentemente. Mas devem funcionar de forma que pessoas daltônicas também possam entender os dados apresentados.
- **Número de elementos**: tente manter a quantidade de elementos apresentados pequena, se for um gráfico de linhas, enfatize as cinco principais apenas, se for um gráfico de pizza, tente manter menos de 7 elementos representados.

### ❌ Erros para evitar

- Retirar o eixo y
- Usar um eixo y duplo
- Limitar artificialmente o escopo dos dados
- Agrupar dados de forma incorreta
- Se usar um gráfico de parte-para-todo, as partes devem somar 100% do todo
- Esconder tendências em gráficos acumulativos
- Suavizar tendências de forma artificial

## 🔗 Links úteis
- [The beauty of data visualization](https://www.ted.com/talks/david_mccandless_the_beauty_of_data_visualization?language=en#t-150183)
- [‘The McCandless Method’ of data presentation](https://artscience.blog/home/the-mccandless-method-of-data-presentation)
- [Information is beautiful](https://informationisbeautiful.net/)
- [Beautiful daily news](https://informationisbeautiful.net/beautifulnews/)