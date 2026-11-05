# Dashboard de Vendas Porsche | Análise de Dados com IA

## Sobre o projeto

O objetivo deste projeto foi utilizar a inteligência artificial para desenvolver uma dashboard de vendas a partir de uma base de dados em Excel, sem precisar recorrer à programação tradicional.

Escolhi trabalhar com uma base de vendas de veículos Porsche e desenvolver um painel que permitisse analisar os resultados comerciais de forma simples, visual e interativa.

Como referência para o layout, utilizei o site oficial da Porsche. A ideia era ter uma dashboard com uma apresentação mais sofisticada, mas sem perder a objetividade e a facilidade de leitura das informações.

## O que busquei analisar

Minha proposta foi entender o comportamento das vendas ao longo do tempo, principalmente identificar os períodos de maior e menor faturamento.

Para isso, defini algumas perguntas de negócio: qual ano vendeu mais e qual vendeu menos, qual semestre apresentou o melhor e o pior resultado, quais meses concentraram as maiores vendas e quais modelos tiveram maior participação no faturamento.

Também considerei importante analisar a distribuição das vendas por estado e a situação das entregas dos veículos.

Escolhi essas perguntas porque entendo que uma dashboard precisa ir além de apresentar números. Ela deve permitir comparar resultados, identificar comportamentos e facilitar a análise das informações para uma possível tomada de decisão.

## Como desenvolvi a dashboard

Utilizei o ChatGPT para desenvolver a dashboard em HTML, a partir de prompts com as orientações sobre os filtros, os indicadores e a referência visual que gostaria de seguir.

Meu primeiro prompt foi:

"Crie uma dashboard em HTML no Canvas, com filtros para mês de compra, vendedor e estado da compra. As perguntas que devem ser feitas são: quem vendeu mais e qual foi o período de maior venda. A referência visual deve seguir o padrão do site da Porsche."

Depois da primeira versão, identifiquei que a base não tinha informações sobre vendedores. Por isso, solicitei a substituição desse filtro pelo ano de compra.

Na sequência, percebi que poderíamos aprofundar a análise e pedi um novo ajuste:

"Acrescente uma análise comparativa por semestre e por ano e acrescente a pergunta de qual ano e semestre temos maior e menor venda."

A dashboard foi sendo construída dessa forma, com ajustes a partir das versões apresentadas. Não defini todas as funcionalidades no primeiro prompt. Fui avaliando o resultado e acrescentando o que considerava necessário para melhorar a análise.

## Tratamento da base de dados

Utilizei uma planilha em Excel com informações sobre as vendas dos veículos, incluindo modelo, data da compra, preço, estado e situação da entrega.

Não fiz um tratamento completo da base antes de enviar para o ChatGPT. A própria análise dos dados durante o desenvolvimento permitiu identificar alguns pontos que precisavam de atenção.

O primeiro foi a ausência da informação de vendedor, que exigiu uma mudança no escopo inicial.

Também foram identificados registros com datas inválidas, que não poderiam ser considerados nas comparações por mês, semestre e ano. Para essas análises, foram utilizadas apenas as datas válidas.

Além disso, foi necessário organizar os dados financeiros e as informações de período para permitir os cálculos e o funcionamento dos filtros.

Esse processo mostrou que, mesmo utilizando IA, é importante conhecer a base e conferir se as informações disponíveis realmente permitem responder às perguntas propostas.

## Ferramentas utilizadas

O projeto foi desenvolvido no ChatGPT, com apoio de recursos especializados de análise de dados e construção de dashboards, incluindo skills.

Embora o pedido inicial tenha sido para desenvolver a dashboard no Canvas, a solução foi entregue em HTML, sem utilização do Canvas tradicional.

Para disponibilizar o projeto, utilizei o GitHub como repositório e o GitHub Pages para publicação da dashboard.

## Resultado final

A versão final da dashboard apresenta indicadores de faturamento, quantidade de vendas e ticket médio, além de gráficos com a evolução das vendas, participação dos modelos e distribuição por estado.

Também foram incluídos filtros por ano, mês, estado e situação da entrega, permitindo consultar diferentes recortes da base.

O principal ajuste em relação à primeira versão foi a inclusão dos comparativos anuais e semestrais, que permitem identificar os períodos de maior e menor faturamento.

## Minha avaliação

O exercício foi interessante principalmente pela possibilidade de desenvolver uma ferramenta de análise sem precisar escrever os códigos.

O que mais chamou minha atenção foi perceber que o resultado depende muito da forma como direcionamos a IA. O primeiro prompt trouxe uma solução inicial, mas foram os ajustes seguintes que permitiram chegar a uma dashboard mais completa e alinhada ao que eu queria analisar.

Também ficou claro que a IA não substitui a necessidade de entender os dados. Foi preciso avaliar a base, identificar informações que não estavam disponíveis e ajustar as perguntas para não trabalhar com resultados que não poderiam ser comprovados.

Considero que o principal aprendizado foi entender a importância de combinar boas perguntas de negócio, conhecimento sobre os dados e direcionamentos claros para conseguir um resultado realmente útil.
