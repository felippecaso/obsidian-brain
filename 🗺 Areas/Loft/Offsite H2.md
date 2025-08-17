# Offsite H2
## Reorg
- Facilitar interações e deixar mais claros os escopos de cada time e interações cross

## OKRs
- O1 - Efficiency
	- Reduzir % de CAC/GMV vendido
	- Atingir % de G&A orçado vs real (BP)
	- Aumentar produtividade de listings publicados por pessoa por quinzena
	- Reduzir o tempo de atendimento do BPO
- O2 - Growth
	- Atingir x novos listings (sem contar WT)
	- Gerar x 1st schedules (canal direto) com GMV médio de x (lead, não portfolio)
	- Crescer em x% nosso Lucro Bruto
	- Atingir GMV vendido
- O3 - People
	- Aumentar produtividade (GMV/C&B + terceiros)
	- Atingir 100% do target de C&B orçado vs real
	- Atingir x% de vagas preenchidas por talentos internos (grupo)
	- Redução SG&A tools %
- O4 - Win Together
	- Atingir x CCVs vindos de portfolio de imobiliárias
	- Atingir x listings totais vindos de imobiliárias
	- Atingir x% conversão Schedule > Offer

## EPOD Analytics
- Como garantir contratos de dados?
	- Precisamos garantir que controlamos todo o fluxo de dados - hoje já temos a ponta que é o Looker, mas não puxamos ainda a parte de trás
	- Analytics como responsável por homologar a métrica e adicionar cruzamentos com outras fontes
	- Cultura é gerada a partir de exemplo
		- Market Data: travamos a partir de não ter nenhum outro crawler na companhia
- Quem está mais próximo da ponta?
	- BA Manager consegue ser o caminho para priorização das métricas que precisam ser criadas
	- AE consegue reagir a essas prioridades
- Requisito de mensuração
	- No caminho canônico, surge de Produto (que é responsável por mensurar o impacto)
- Precisamos definir as métricas
	- Novas
		- Conseguimos fazer a partir dos contratos
	- Existentes
		- Apoiar nos stakeholders que precisam dessa definição (Operações e Finance)

## Contratos de dados
### Template
- EPOD Consumidora
- EPOD Produtora
- O que é necessário? (qual dado ou feature é necessária)
- Onde isso se encaixa? (qual o fluxo ou job to be done de operação envolvido, vale link pro miro, etc, desde que explicado)
- Qual é o impacto esperado disso? (métrica impactada + dóllar impact)
- Quando se espera começar a gerar esse impacto?
- Outras informações

### Supply
#### Histórico de listings
- EPOD Consumidora
	- Analytics
- EPOD Produtora
	- Portfolio Management
- O que é necessário? (qual dado ou feature é necessária)
	- Disponibilização de dados de todo o histórico de listings publicados e despublicados, que hoje existe somente no ambiente analítico
- Onde isso se encaixa? (qual o fluxo ou job to be done de operação envolvido, vale link pro miro, etc, desde que explicado)
	- Disponibilização de dados analíticos
- Qual é o impacto esperado disso? (métrica impactada + dóllar impact)
	- Redução no tempo de desenvolvimento e manutenção de Analytics
	- Aumento na governança de métricas e conceitos, reduzindo número de incidentes de dados
- Quando se espera começar a gerar esse impacto?
	- Imediato conforme disponibilização
- Outras informações

#### Dados de custo e prazo de reforma
- EPOD Consumidora
	- Analytics
- EPOD Produtora
	- Portfolio Management
- O que é necessário? (qual dado ou feature é necessária)
	- Com a descontinuação dos times de tecnologia que suportam o processo de reforma, precisamos consumir de uma fonte única os dados de custo e prazo (estimado e realizado) das reformas em apartamentos Loft
	- Pode ser construído de início com base no que já existe na camada analítica, mas os conceitos precisam viver fora dela
- Onde isso se encaixa? (qual o fluxo ou job to be done de operação envolvido, vale link pro miro, etc, desde que explicado)
	- Disponibilização de dados analíticos
- Qual é o impacto esperado disso? (métrica impactada + dóllar impact)
	- Redução no tempo de desenvolvimento e manutenção de Analytics
	- Aumento na governança de métricas e conceitos, reduzindo número de incidentes de dados
- Quando se espera começar a gerar esse impacto?
	- Imediato conforme disponibilização
- Outras informações

#### Dados de portfolio
- EPOD Consumidora
	- Analytics
- EPOD Produtora
	- Portfolio Management
- O que é necessário? (qual dado ou feature é necessária)
- Onde isso se encaixa? (qual o fluxo ou job to be done de operação envolvido, vale link pro miro, etc, desde que explicado)
- Qual é o impacto esperado disso? (métrica impactada + dóllar impact)
- Quando se espera começar a gerar esse impacto?
- Outras informações

#### Estruturação dos dados de Pricing
- EPOD Consumidora
	- Analytics
- EPOD Produtora
	- Listing Onboarding
- O que é necessário? (qual dado ou feature é necessária)
	- Reestruturação dos dados de pricing disponibilizados no Data Lake
	- Documentação dos conceitos que devem ser usados para consumo dos dados (ex.: existem 6 atributos de área do apto)
- Onde isso se encaixa? (qual o fluxo ou job to be done de operação envolvido, vale link pro miro, etc, desde que explicado)
	- Disponibilização de dados analíticos
- Qual é o impacto esperado disso? (métrica impactada + dóllar impact)
	- Redução no tempo de desenvolvimento e manutenção de Analytics
	- Aumento na governança de métricas e conceitos, reduzindo número de incidentes de dados
- Quando se espera começar a gerar esse impacto?
	- Já acontece, pode melhorar
- Outras informações

#### Dados de ações e testes de venda de portfolio proprietário
- EPOD Consumidora
	- Analytics
- EPOD Produtora
	- Portfolio Management
- O que é necessário? (qual dado ou feature é necessária)
	- Substituição de sheets ([link 1](https://docs.google.com/spreadsheets/d/19Q68OEdBqYIN8lFx09bS5q8CGyhufLWjE26P52kAoUM/edit#gid=0) e [link 2](https://docs.google.com/spreadsheets/d/16wCzZjtUbKgXNvabWdhUYOAt27DLZXJWPDkVno280Ps/edit#gid=1237017944)) que são fonte para dados de ações e testes (ex.: Home Staging e campanhas) que são feitos nos apartamentos do portfólio proprietário.
- Onde isso se encaixa? (qual o fluxo ou job to be done de operação envolvido, vale link pro miro, etc, desde que explicado)
	- Disponibilização de dados analíticos
- Qual é o impacto esperado disso? (métrica impactada + dóllar impact)
	- Redução no tempo de desenvolvimento e manutenção de Analytics
	- Aumento na governança de métricas e conceitos, reduzindo número de incidentes de dados
	- Aumento de eficiência operacional no preenchimento das ações pelo time de operações em Portfólio
- Quando se espera começar a gerar esse impacto?
	- Imediato conforme disponibilização
- Outras informações

#### Dados de modelos de DS (?)


### Finance
#### Netsuite


#### BP e valores orçados


### Data Platform
#### Dados de custos da plataforma de dados
