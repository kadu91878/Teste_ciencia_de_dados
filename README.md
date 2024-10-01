##Teste Técnico Para Ciência De Dados Júnior
Recomendações:
- Para a realização do teste a seguir nós recomendamos a
busca por informações, ideias e insights em fontes diversas
voltadas à resolução dos problemas tratados, não basta se
prender ao arcabouço técnico de programação e estatística.
- Como cientista de dados, a pesquisa e busca por novos
conhecimentos será diária e essencial para a plena realização
de sua função, sendo assim, sempre estimulamos a
criatividade e curiosidade para resolução de problemas.
- Sinta-se à vontade para utilizar a abordagem que melhor se
adequar em sua visão para os problemas tratados.
- Caso encontre outras análises pertinentes que não foram
diretamente solicitadas, sinta-se à vontade para incluir as
mesmas em sua resposta.
- Em caso de resoluções com o desenvolvimento de códigos, é
interessante que os mesmos sejam disponibilizados, em
casos onde os mesmos não forem necessários, escreva sua
linha de raciocínio para a resolução da demanda.
- Caso não consiga finalizar alguma das questões, indique sua
ideia frente ao problema. Seu raciocínio e lógica de
abordagem são muito mais importantes do que o resultado
final em si.
Boa sorte!

##1) Considere que você é o cientista de dados responsável pela análise do
comportamento e evolução do balanço final da empresa mês a mês, para tal, foi
disponibilizado um arquivo (metricas_financeiras_mensais) com duas colunas, uma
com a data de apuração do balanço financeiro e outra com o valor em reais do
balanço no mês de referência. Sendo assim, foram solicitadas as seguintes
informações para a tomada de decisões futuras:
#a) Quais os 5 meses com o melhor fechamento de balanço e quais os 5 meses
com o pior fechamento de balanço?
#b) Qual foi o melhor ano para a empresa em termos de ganho total? Qual a
média de fechamento de balanço ano a ano? A média e a mediana se
aproximam? Em caso de negativa, explique o motivo.
#c) Qual o maior período de meses com o maior somatório de balanço
ininterrupto? Em que mês se inicia e finaliza esse período e qual o valor total
do mesmo? Como base para responder essas questões, considere o
seguinte exemplo:
lista_exemplo=[1,1,2,4,-5,20,-100,22]
A faixa de maior soma se dá entre o primeiro e o sexto termo da lista, visto
que, 1+1+2+4-5+20=23.
#d) Se fosse solicitado para que você estimasse o balanço final dos meses de
outubro, novembro e dezembro de 2024 considerando o comportamento
observado nos meses anteriores, qual seria a sua estratégia para abordar o
problema?
##2) Suponha que você esteja participando de um projeto voltado à mitigação de fraudes,
e para tal, você deve analisar dados diversos, tais como o CPF, Telefone Celular
(Com DDD incluso) e entre outros. Com isso em mente, responda às seguintes
questões:
#a) Quais critérios você utilizaria para indicar se o CPF é válido em termos
estruturais? Construa um algoritmo para automatizar esse processo e realize
um teste com os seguintes CPFs, indicando aqueles que são válidos ou não:
- 217.894.500-71
- 112.622.670-05
- 695.226.930-49
- 015.897.070-51
- 311.692.760-06
#b) Quais critérios você utilizaria para indicar se um telefone celular é válido ou
não em termos estruturais? Construa um algoritmo para automatizar esse
processo e realize um teste com os seguintes telefones, indicando aqueles
que são válidos ou não:
- (64) 96743-8065
- (75) 89555-5682
- (99) 98362-0347
- (10) 98595-1389
#c) Erros e variações de escrita são comuns em processos de preenchimento de
dados como nomes. Com isso em mente, qual estratégia você tomaria para
que em um contexto de avaliação, um modelo retornasse True para as
seguintes comparações:
- Fernando dos Santos / Fernando Santos
- Maria da Silva Rodrigues / Maria Rodrigues
- João Roberto / joao robert
##3) Solicitaram para você que seja criado um modelo de apuração de métricas de
processamento em relação ao valor, quantidade de vendas e método de pagamento.
Para tal, uma base de dados (metricas_dados_de_pagamento) foi disponibilizada
como referencial, contendo as colunas user_id (Representa o parceiro analisado),
mes_ano, metodo_pagamento, status_finalizacao, qtd_total (Quantidade de
transações) e tpv (Valor total processado). Para o fechamento de receita, são
considerados apenas os pedidos finalizados em integrado, sendo assim, os
questionamentos são os seguintes:
#a) Qual parceiro (user_id) possui o maior processamento em termos de TPV em
cada um dos meses?
#b) Em qual dos meses ocorre o pico de processamento de cartão de crédito?
#c) Parceiros supremos são aqueles que possuem média de processamento
total superior a 300 mil reais olhando para um período de 3 meses de
processamento, com isso em mente, quantos e quais são os parceiros
supremos contidos na base?
#d) Analisar a estabilidade do processamento dos parceiros é um dos pontos
vitais para a manutenção da saúde processual de uma fintech, com isso em
mente, em termos percentuais e inteiros, qual foi a oscilação do total de
parceiros com processamento maior do que zero de agosto para setembro?