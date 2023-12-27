### Projeto Dashboard para acompanhamento de empresa de e-commerce:

### 1. Problema de negócio

Uma empresa de e-commerce B2C quer impulsionar o crescimento de seus negócios. Para isso, busca otimizar suas estratégias de marketing e vendas para se destacar em um mercado competitivo. Com o objetivo de tomar decisões mais embasadas, a empresa coletou dados abrangentes sobre clientes, cupons de desconto, gastos com marketing, vendas online e impostos. 

Você foi contratado para criar soluções de dados para a empresa, mas antes de treinar algoritmos, a necessidade da empresa é ter as principais métricas estratégicas organizadas em uma única ferramenta, para que o CEO possa consultar e conseguir tomar decisões simples, porém importantes.

Para acompanhar o crescimento do negócio, o CEO gostaria de ver as seguintes métricas:

- Receita bruta
- Ticket médio de compra
- Total de transações
- Total de desconto dado aos clientes
- Total de clientes
- Receita bruta por mês
- Receita bruta por dia da semana
- Receita bruta por região
- Investimentos em marketing
- Quantidade de cupons por status de uso
- Top 5 produtos
- Top 5 categorias
- Análise RFM
- Análise de Cohort

Nesse contexto, o objetivo desse projeto é criar um conjunto de gráficos que exibam essas métricas da melhor forma possível para o CEO em um dashboard no Excel. A análise de cohort deve ser exibida em uma aba separada, com os principais insights. Já a análise RFM deve ser apresentada de forma resumida no dashboard. 

### 2. Premissas assumidas para a análise

1. A análise foi realizada com dados entre 01/01/2019 e 31/12/2019;
2. E-commerce B2C foi o modelo de negócio assumido;
3. Assumiu-se uma Gross Margin de 65%;
4. Os dados utilizados se encontram em:  https://www.kaggle.com/datasets/rishikumarrajvansh/marketing-insights-for-e-commerce-company

### 3. Estratégias da solução

O painel estratégico foi desenvolvido utilizando as métricas pedidas. Assim, foram utilizadas tabelas dinâmicas, filtros e gráficos para obter os resultados esperados, seguindo-se a seguinte estratégia:

1. Exploração dos dados:
    1. Carregar os conjuntos de dados em um ambiente de análise (Excel);
    2. Identificar e tratar dados ausentes ou inconsistentes;
    3. Compreender a estrutura e os relacionamentos entre as tabelas.
2. Análise Descritiva:
    1. Realizar análises estatísticas descritivas para cada conjunto de dados;
    2. Visualizar distribuições, tendências e padrões nos dados.
3. Integração de Dados:
    1. Relacionar dados entre as diferentes tabelas para obter uma visão holística;
    2. Identificar chaves de junção para realizar a junção correta.
4. Análise das relações:
    1. Utilizar ferramentas do Excel para analisar as relações entre variáveis-chave;
    2. Interpretar a relação entre cupons, gastos com marketing e vendas online.
5. Visualização de Dados:
    1. Criar gráficos e visualizações para representar as descobertas de maneira clara e acessível.
6. Análise Temporal:
    1. Explorar tendências temporais nas vendas, gastos com marketing e demais despesas.
7. Comparação de Canais de Marketing:
    1. Avaliar o desempenho relativo dos diferentes canais de marketing.
8. Recomendações Estratégicas:
    1. Com base nas análises, propor recomendações estratégicas para melhorar o desempenho de marketing e vendas.

### 4. Top 5 Insights de dados

1. A maior receita anual de vendas acontece entre os dias de quarta a sexta-feira (55% da receita), enquanto segunda e terça-feira são os dias de menor receita (16%);
2. A categoria Nest-USA é a categoria de produtos responsável pela maior parte da receita anual da empresa (53%). Os 5 produtos mais vendidos, responsáveis por 46% do faturamento anual, fazem parte dessa categoria;
3. Os estados de Chicago e Califórnia são responsáveis por quase 80% da receita anual da empresa;
4. A maior parte (75%) dos clientes possui um score médio entre 2 e 4 (numa escala de 1 a 5). Sendo que 6% deles possuem o score máximo e 5% o mínimo.
5. O ticket médio anual é de $95,60. No caso das compras utilizando cupons, esse valor é de $81,49 (14,8% menor) 

### 5. O produto final do projeto

Dashboard no Excel com filtros de seleção (região, gênero dos clientes, status dos cupons e mês), macros para limpar filtros,  ativar a múltipla seleção de itens e enviar o usuário à aba da análise de cohort. O dashboard permite a visualização dos principais insights de dados.

### 6. Conclusão

O objetivo desse projeto foi criar um conjunto de gráficos que exibissem as métricas descritas anteriormente da melhor forma possível para o CEO em um dashboard em Excel. Além disso, foi também realizar uma análise RFM e uma análise de cohort.

As principais conclusões sugerem que:

- Nos dias da semana que geram a maior receita (quarta a sexta-feira) é possível fazer ações específicas para aumentar mais as vendas. É possível também fazer ações específicas nos dias de menor receita (segunda e terça-feira) para estimular o crescimento de vendas nesses dias.
- Ações semelhantes podem ser tomadas em relação as regiões de maior e menor receita.
- A categoria de produtos Nest é o carro chefe da empresa, podendo receber ações específicas para aumentar o faturamento.
- Podem ser feitas ações específicas (descontos, cupons, brindes, etc) para os clientes de maior score para manter sua fidelização e aumentar a receita gerada por eles. Enquanto que para os clientes de menor score, podem ser feitas ações direcionadas a atraí-los a comprar mais na empresa.

### 7. Próximos passos

1. Reduzir o número de métricas após alinhamento com o time de negócios;
2. Obter mais informações sobre os gastos de marketing (por exemplo, gastos por região, quais novos clientes vieram por meio de anúncios).
3. Obter mais informações sobre os clientes (por exemplo, idade).
