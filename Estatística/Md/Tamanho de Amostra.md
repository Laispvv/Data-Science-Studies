# Tamanho de Amostra e Margem de Erro

Alguns termos a se familiarizar no meio estatístico:

Terminologia | Definição
-|-
População (Population) | O grupo inteiro que se está estudando
Amostra (Sample) | Um pedaço representativo da população
Margem de Erro (Margin of error) | A diferença do resultado de analisar uma amostra vs. analisar a população
Nível de Confiança (Confidence level) | O quão confiável são os resultados obtidos, por exemplo, se a pesquisa for refeita 100 vezes e obtiver o mesmo resultado 99 vezes, então o nível de confiança é 99%
Intervalo de Confiança | Intervalo de possíveis resultados que seriam obtidos com a população considerando o nível de confiança do estudo, ou seja, [resultado da amostra - margem de erro, resultado da amostra + margem de erro]
Significância estatística | Determina se os resultados podem ter ocorrido por acaso ou não, quanto maior a significância menor as chances de ter sido por acaso.

## Calculando o Tamanho da Amostra (Sample Size)

Quando se determina o tamanho da amostra, tenha em mente:

- **Não use um tamanho de amostra menor que 30**: o tamanho 30 é o menor tamanho de amostra onde o CLT(Central Limit Theorem) ainda é válido
- **O nível de confiança deve estar entre 90% - 95%**: sendo o mais comum o 95%

#### Calculadoras online do tamanho da amostra

- [Calculadora da Raosoft](http://www.raosoft.com/samplesize.html)
- [Calculadora da SurveyMonkeys](https://www.surveymonkey.com/mp/sample-size-calculator/)

<hr>

## Calculando a Margem de Erro (Margin of Error)

A margem de erro é importante para entender se os resultados obtidos tem **significancia estatística**, por exemplo: 

>Se fizermos um teste A/B para determinar qual frase gera mais clique em um site, e observarmos que:
> - a frase A resultou em 5% de cliques por visualização
> - a frase B resultou em 3% cliques por visualização

>se a margem de erro for de 2%, **não conseguimos concluir qual das frases tem o melhor resultado**, pois o intervalo de confiança da frase A [3% - 7%] e o da frase B [1% - 5%] se sobrepõe

#### Calculadoras online do tamanho da amostra

- [Calculadora da Google](https://goodcalculators.com/margin-of-error-calculator/)
- [Calculadora da CheckMarket](https://www.checkmarket.com/sample-size-calculator/#sample-size-margin-of-error-calculator)