# Analytics Ops
> Ou, analytics as a product
## Brainstorming
### [[2022-06-26]]
- Criar diagnóstico de como está a responsabilidade de cada ator/área no processo de fazer os dados chegarem do outro lado
- Linear flow / turbulent flow

- Frentes
	-   Produtos de Prateleira
	    -   Visto como principal quick win
	-   Cursos de ferramentas
	    -   Conecta com Academy
	-   Guia de Analytics

- Mensurar uptime de tabelas a partir dos snapshots de runs

- Ideia para dbt2looker
	- Usar 100% da integração, e edições específicas no Looker são feitas com refinements
	- https://docs.looker.com/data-modeling/learning-lookml/refinements

### Mensuração de produtividade
- Quantos bugs o time precisa atuar?
	- Quanto tempo gasto por bug?
		- Proxy: tempo do bug no espaço de atenção do time
		- Média últimos 3 meses: 10 dias (36 bugs)
		- Maioria: *Problem/Help with curated dashboard*
	- Qual é a causa raiz do bug?
		- Erro próprio previsível
		- Erro próprio imprevisível
		- Mudança de conceito de processo

### Health Metrics
- 90% dos explores com mais de 50 queries nos últimos 30 dias
	- Premissa: 2 execuções de um dashboard

### [[2021-12-22]]
Plano de absorção do escopo dos [[BA Teams]]:
- Q1/22
	- Experiência de Clientes
	- Gestão e Controle de Uso
- Q2/22
	- Autosserviço
	- Transformação
- Q3/22
	- Criação de Conteúdo
	- Comunicação com Dados

Escopo que está dentro do [Data Quality](https://docs.google.com/presentation/d/1sKFPqhkLjOLv5Di4tVbn6TGdakRpWpN52e7uOBa-L28/edit#slide=id.g1072a945024_0_0):
- Performance do Looker
- Expectativas operacionais
	- Looker como backoffice (diagnóstico)
	- Governança: PMO
	- Evangelização da função da ferramenta

Coisas que acho que deveriam entrar
- Fluxo looker_help
- Permissionamento de acesso do Looker
	- Proposta: só pode ganhar Explorer quem concluir o treinamento que a gente definir
	- "se o closer fizer o treinamento, ele pode ter?"
- Interface com DataX para gerenciamento do Databricks

## Referências
- https://review.firstround.com/how-i-structured-engineering-teams-at-linkedin-and-admob-for-success
	- [Updates Liderança Engenharia [[2022-01-10]]](https://docs.google.com/document/d/1LtoD7ie74HqM1VPUKKFJTl2ZbBbWHF2zE2IQc7vDfEs/edit#heading=h.28pbz4vi0eaw)
	- Stop confusing building technology with building a company\
- https://app.diagrams.net/#G1esbsn_-JIabmKNdZY11SUOZXzkcXGVJo