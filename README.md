# solucoes-mineracao-de-dados-2022.1
Repositório para os scripts e missões da disciplina de Soluções de Mineração de Dados (Data Mining)
Equipe: Filipe Melo, Ismael Cesar, Thiago Melo

Na disciplina, realizamos um projeto em cima do dataset de Shill Biding, que pode ser encontrado em: https://archive.ics.uci.edu/ml/datasets/Shill+Bidding+Dataset
Esse dataset trata do problema de detecção de shill biddings no ebay. "Shill Bidding" é um tipo de fraude em leilões virtuais, onde donos de produtos (ou seus cúmplices) criam contas falsas para gerar uma demanda e aumentar os preços do produto artificialmente, então quando um comprador honesto propõe um lance cobrindo os lances anteriores o mesmo acaba pagando mais que deveria, já que o preço foi aumentado artificialmente. Segundo o Internet Crime
Complain Centre (IC3) (Fonte: I.C.C. Center, “2015 internet crime report,” in 2015 IC3 Report) fraudes em leilões virtuais é um dos cyber-crimes mais comuns.

A prática de "Shill Bidding" é um problema para a plataforma do ebay, desde os seus primeiros anos, e é uma preocupação da empresa tomar ações contra isso. Recentemente, eles removeram o maior vendedor de "trading cards" do site, removendo mais de 18000 anúncios feitos pelo usuário. Fonte:
 
- https://www.eseller365.com/ebay-removes-trading-card-seller-shill-bidding/

Para o projeto, temos como objetivo detectar quais bidders são fraudulentos e quais não são. Para alcançar isso temos como objetivo de ciência de dados, treinar uma variedade de modelos e otimizar os seus parâmetros, para ver como poderíamos atingir um melhor resultado, utilizando o dataset do Shill Bidding para treino, validação e teste.

Para alcançar esses objetivos, realizaremos uma série de scripts em python. Utilizaremos bibliotecas do python como numpy, pandas, sklearn e seaborn. Seguiremos as etapas do CRISP-DM: Compreensão do Problema, Compreensão dos dados, Preparação dos dados, Modelagem, Avaliação dos Modelos, Deployment. A etapa de deployment foi abstraída por se tratar de um projeto de uma disciplina.
