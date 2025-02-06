# Projeto Data Lake PoD Cartões - PoD Academy

## O Problema de Negócio - PoD Cartões

A PoD Cartões é uma empresa de serviços financeiros especializada em cartões de crédito, com uma base de milhares de clientes 
em todo o Brasil. A empresa enfrenta desafios relacionados ao gerenciamento e aproveitamento de seus dados para melhorar as 
operações e apoiar decisões estratégicas:

1. Armazenamento de dados:
   Os dados de clientes, transações e comportamento estão fragmentados em diferentes sistemas legados, dificultando a 
consolidação e a confiabilidade das informações.
2. Suporte às operações:
   A infraestrutura atual não é capaz de lidar eficientemente com o aumento do volume, variedade e velocidade dos dados 
gerados pela operação, impactando a escalabilidade e a agilidade da empresa.
3. Capacitação para modelagem preditiva:
   Os cientistas de dados enfrentam dificuldades para acessar e consumir dados organizados e de alta qualidade, o que limita 
o desenvolvimento de modelos analíticos e preditivos que poderiam auxiliar na retenção de clientes, previsão de 
inadimplência e personalização de ofertas.

## Objetivo:

- Desenvolver Arquitetura de dados baseada em um Data Lake
- Realizar Book de Variáveis de Fatura


## Checklist do Projeto

- Arquitetura de Dados
- Data Quality
- Orquestração

## Plataforma e Ferramentas Utilizadas

- Microsoft Fabtic 
- OneLake
- Lakehouse
- PySpark
- Data Factory
- Dataflow

## Análise rápida na Liguagem SQL da Stage
- 40% das faturas foram pagas em Atraso, sendo 21,47% tem valores entre R$ 45k a R$ 60k;
- 30% das Faturas estão Sem pagamento, sendo que 21,50% dos valores dessas faturas é de até R$ 15k;
- E aproximadamente 3% das faturas são pagas no Prazo, onde 22,81% dos valores pagos são de até R$ 15K.
