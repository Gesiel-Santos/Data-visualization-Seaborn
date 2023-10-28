# Análise exploratória de dados sobre as gorjetas dos clientes de um restaurante 🍽️

Neste projeto, eu utilizei a técnica de **testes de hipóteses** para analisar os fatores que influenciam as **gorjetas** dos clientes de um restaurante.

## Dados 📊

Os dados foram obtidos do arquivo tips.csv, que contém as seguintes variáveis:

- **total_bill**: valor total da conta
- **tip**: valor da gorjeta
- **sex**: sexo do cliente
- **smoker**: indica se o cliente é fumante ou não
- **day**: dia da semana
- **time**: hora do dia (almoço ou jantar)
- **size**: número de pessoas na mesa

## Bibliotecas 📚

As bibliotecas utilizadas neste projeto foram:

- **pandas**: para manipular os dados
- **matplotlib**: para gerar gráficos
- **seaborn**: para gerar gráficos estatísticos
- **scipy**: para realizar testes de hipóteses

## Análise 🔎

A análise foi dividida em três etapas:

1. Exploração dos dados: nesta etapa, eu verifiquei as características dos dados, como o número de observações, os tipos das variáveis, os valores ausentes, as estatísticas descritivas e sua Tradução.
2. Análise gráfica: nesta etapa, eu utilizei diferentes tipos de gráficos para visualizar a distribuição, a relação e a variação das variáveis, como histograma, scatter plot, violinplot.
3. Testes de hipóteses: nesta etapa, eu realizei testes de hipóteses para verificar se há diferenças significativas entre as médias ou as proporções das variáveis categóricas em relação à variável gorjeta.

## Resultados 🏆

Os principais resultados obtidos foram:

- A média das gorjetas foi de 3 dólares, com um desvio padrão de 1,38 dólares.
- A média das gorjetas teve uma correlação positiva com o valor total da conta (0,68) e o número de pessoas na mesa (0,49).
- A média das gorjetas foi maior nos jantares (3,10 dólares) do que nos almoços (2,73 dólares), com uma diferença estatisticamente significativa.
- A média das gorjetas foi maior nos finais de semana (3,12 dólares) do que nos dias úteis (2,84 dólares), com uma diferença estatisticamente significativa.
- A média das gorjetas não teve uma diferença estatisticamente significativa entre os sexos dos clientes (3,02 dólares para homens e 2,83 dólares para mulheres) nem entre os fumantes e não fumantes (3,01 dólares para fumantes e 2,99 dólares para não fumantes).
- A proporção de clientes fumantes foi maior nos jantares (23%) do que nos almoços (15%), com uma diferença estatisticamente significativa.

## Conclusão 🎓

A conclusão deste projeto foi que a técnica de testes de hipóteses foi útil para analisar os fatores que influenciam as gorjetas dos clientes de um restaurante. A análise mostrou que as variáveis que tiveram um impacto significativo nas gorjetas foram o valor total da conta, o número de pessoas na mesa, o dia da semana e a hora do dia. As variáveis que não tiveram um impacto significativo nas gorjetas foram o sexo do cliente e o fato de ser fumante ou não. Portanto, sugere-se que o restaurante foque em atrair mais clientes nos finais de semana e nos jantares, oferecendo promoções ou descontos, para aumentar as gorjetas recebidas.
