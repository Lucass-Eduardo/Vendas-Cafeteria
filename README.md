# Análise de vendas.

Neste projeto, analisei uma base de dados da rede de cafeterias da Maven Roasters. Analisei o comportamento de vendas de 3 unidades em Nova York para obter insights que possam ser usados pela empresa.

A base de dados era do primeiro semestre de 2023 e tinha informações de 3 cafeterias que se localizam em Hell's Kitchen, Lower Manhattan e Astoria. A base de dados continha cada transação realizada em cada loja. Primeiramente, utilizei as séries temporais para identificar se havia tendência, sazonalidade e estacionariedade.

A tendência era linear de crescimento. Consegui identificar sazonalidade e que a série é não estacionária. Olhando a sazonalidade, foi possível identificar os dias e horários que as lojas mais vendem: segunda-feira e o horário mais movimentado é entre as 6h e 10h.

Ao analisar a venda dos produtos e a média mensal de venda de cada loja, percebi que o comportamento delas era quase igual. Não havia diferença significativa entre os produtos mais vendidos, a quantidade vendida e a média de venda. Sendo assim, muitas decisões podem ser tomadas de forma geral, sem a necessidade de uma estratégia única para cada loja.

Para fazer gráficos mais avançados, utilizei a biblioteca plotly para Python. O plotly permite criar gráficos interativos e faz parte de uma ferramenta chamada Dash, utilizada por analistas e cientistas de dados para criar dashboards. Posteriormente, criarei um dashboard utilizando as informações e insights deste projeto.

## **Conclusões:**

- A análise de vendas de 3 cafeterias da Maven Roasters em Nova York revelou uma tendência de crescimento linear.
- As lojas vendem mais na segunda-feira, entre as 6h e 10h.
- O comportamento de vendas das lojas é similar, permitindo decisões gerais sem necessidade de estratégias individualizadas.

- obs: Os gráficos interativos do Plotly não funcionam no github, para visualizar utilize o este [Link](
(https://www.kaggle.com/code/lucassedu/an-lise-da-cafeteria)
