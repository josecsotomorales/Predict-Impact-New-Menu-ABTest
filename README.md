# Predict-Impact-New-Menu-ABTest
En-Us
Round Roasters, a coffee restaurant in the United States of America. The company needs to implement a growth initiative, given that in the past few years the growth levels off and sales become stagnant. The growth initiative is to introduce gourmet sandwiches to the menu, along with limited wine offerings. It is crucial to drive people into the stores with these new offerings through television advertising campaign. The television campaign will require a significant boost in the company’s marketing budget, but the profitability is unknown. It is necessary needs to figure whether the new menu can drive enough sales to offset the cost of marketing the new menu. To predicted impact to profitability, we implement A/B testing. In particular, we apply the changes in two markets that their performance would be a good proxy to predict how well the updated menu performs.
The Gross margin helps a company assess the profitability of characteristics activities. Then, this measure is used as the performance metric of the test.

The test ran for a period of 12 weeks (2016-April-29 to 2016-July-21) where five stores in each of the test markets offered the updated menu along with television advertising. The file “treatment-stores” contains store information for this store.

The file “RoundRoastersTransactions” contains transaction level information for all of Round Roaster's stores from 2015-January-21 to 2016-August-18, they are 574 days. The test should run for a normal cycle, we need to understand and track customer flow through the store. It is assumed that customer visits the stores at least once a week, then we aggregate the data to week level.

We combine “RoundRoastersTransactions” file and “round-roaster-stores” file that contains store information for each Round Roaster store in the USA. We manipulate the data in particular with Date/Time Functions that present in the Alteryx and we obtain weekly traffic and sales for each store. Furthermore, we utilize also the “treatment-stores” file to create the list of control and treatment stores.

Pt-Br
O Problema do negócio
Round Roasters é uma luxuosa franquia de cafés presente na costa oeste dos Estados Unidos da América. Os últimos anos representaram na estagnação no crescimento da franquia, e uma nova equipe de gestão foi montada para realavancar o crescimento de suas lojas.

A primeira grande iniciativa de crescimento é introduzir sanduíches "gourmet" no cardápio, juntamente de uma carta de vinhos. A nova gestão crê que uma campanha de propagandas televisivas seja crucial para direcionar o público para as lojas com estas novas ofertas.

Contudo, esta campanha publicitária por meio da televisão requeriria um significativo aumento no orçamento de marketing da empresa, com um retorno de investimento (ROI, do inglês Return of Investiment). Ademais, existe uma preocupação que os atuais clientes não iriam aderir aos novos produtos do cardápio.

Para minimizar o risco, a gestão decidiu verificar tais mudanças em duas cidades com novas propagandas televisivas. Denver e Chicago foram as cidades escolhidas para participar desde teste pois o comportamento das lojas (e seus respectivos mercados), são similares aos comportamentos das lojas do restante da rede. Deste modo, a performance obtida nestes mercados pode ser um bom indicativo de como o novo cardápio atuará no restante da cadeia.

O teste fui executado em um período de 12 semanas (entre 29 de Abril de 2016 até 21 de Julho de 2016), onde cinco lojas nos mercados supracitados utilizavam o cardápio atualizado juntamente da campanha publicitária na televisão. A semana fiscal para a cadeia Round Roasters começa na Sexta-feira e termina na Quinta-feira.

O período de comparação é o mesmo do período de testes, menos para o ano passado (29-04-2015 a 21/07/2015).

Você foi requisitado para analizar os resultados do experimento para determinar se a mudança do cardápio deve ser replicada para todas as lojas da franquia. O impacto previsto nas vendas deve ser grande o suficiente para justificar o aumento nos gastos em marketing: um aumento de pelo menos 18% de aumento nas vendas no período de comparação em relação às lojas de controle deve existir, caso contrário, possíveis aumentos serão considerados apenas aumentos incrementais das vendas.

Você teve acesso a três conjuntos de dados para sua análise:

Dados de transações para todas as lojas entre 21 de Janeiro de 2015 até 18 de Agosto de 2016
Uma listagem de todas as lojas Round Roasters
A listagem de 10 lojas (5 em cada mercado) que foram utilizadas como mercados teste.
