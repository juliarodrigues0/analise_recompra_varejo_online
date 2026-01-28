# Análise de Recompra no Varejo Online

## Objetivo
Este projeto tem como objetivo analisar os fatores associados à recompra de clientes no varejo online brasileiro, utilizando dados públicos de e-commerce, com foco em frequência de compras, ticket médio, valor gasto e custo de frete.

## Problema
O crescimento do varejo online ampliou o acesso a produtos e serviços, mas evidenciou um desafio central para a sustentabilidade dos negócios digitais: a baixa taxa de recompra de clientes. Muitos consumidores realizam apenas uma compra e não retornam à plataforma, aumentando a dependência de investimentos contínuos em aquisição de novos clientes.

## Fonte de Dados
Foi utilizado o *Brazilian E-Commerce Public Dataset by Olist*, disponibilizado publicamente na plataforma Kaggle. O conjunto de dados é composto por informações anonimizadas sobre pedidos, clientes, produtos, pagamentos e logística, permitindo análises detalhadas do comportamento de recompra.

## Metodologia
Os dados foram coletados por download direto, tratados e integrados em Python no Google Colab. A análise exploratória considerou apenas pedidos entregues e agregou informações no nível do cliente, possibilitando a construção de métricas como total de pedidos, ticket médio, valor total gasto e frete médio. A recompra foi definida como a realização de mais de um pedido pelo mesmo cliente ao longo do período analisado.

## Principais Insights
- A maior parte dos clientes realiza apenas uma compra, evidenciando uma baixa taxa de recompra.
- Clientes recorrentes apresentam maior ticket médio e maior valor total gasto, indicando maior potencial de geração de valor ao longo do tempo.
- O frete médio é mais elevado entre clientes não recorrentes, sugerindo que custos logísticos podem atuar como uma barreira à recompra.

## Visualização dos Resultados
Os resultados da análise foram apresentados em um dashboard desenvolvido no Looker Studio, contendo visualizações sobre distribuição de clientes por recompra, frequência de compras, ticket médio, valor gasto e frete médio por tipo de cliente.

🔗 **Link do dashboard no Looker Studio:**  
[(https://lookerstudio.google.com/reporting/cab864bb-6971-4af4-9c69-e4e76e49f99d) 
](https://lookerstudio.google.com/reporting/cab864bb-6971-4af4-9c69-e4e76e49f99d)
## Sugestões de Ações
Com base nos resultados obtidos, recomenda-se a implementação de estratégias de incentivo à recompra logo após a primeira compra, como campanhas personalizadas e benefícios progressivos. Além disso, políticas de frete diferenciadas para clientes com maior potencial de recorrência podem contribuir para reduzir barreiras à recompra. O monitoramento contínuo de indicadores de comportamento de compra pode apoiar estratégias de CRM mais eficazes e orientadas por dados.

## Conclusão
A análise demonstra que a recompra no varejo online está associada a padrões mensuráveis de consumo, reforçando a importância da análise de dados como ferramenta de apoio à tomada de decisão estratégica e à suste
