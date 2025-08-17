---
created: 2023-07-12 09:39
---

# Wednesday, July 12, 2023

<< [[2023-07-11-Tuesday]] | [[2023-07-13-Thursday]]>>

---

# 📝 Notes
## Conversa com Jose Luciano (Nubank AE)
- https://www.linkedin.com/in/jmelo3/
- Tech Manager desde 2021, Manager desde 2023
- Também teve background de BA
- Pessoas específicas no negócio tem um impacto transversal e orquestram a resolução de problemas relevantes
	- Ex.: políticas de crédito
	- Um IC7 está pensando em pegar essa política de crédito, sair de 80MM de clientes e escalar pra 200MM de clientes
	- Ex.: infra de blockchain necessária
- Disciplina de AE - foco em gerar impacto por meio da melhoria da forma que as pessoas trabalham com o dado
- Perguntas
	- Momento do chapter e da carreira no equilíbrio tech/data/business
		- Noção de analytics como uma disciplina (assim como produto, engenharia)
		- BAs continuam fazendo a mesma coisa (da análise à construção do produto de tecnologia)
			- Mas vai ser cobrado pela análise/camada analítica/produto analítico
			- Vida "não mudou em nada" com a chegada do AE
		- O problema de vários BAs é um problema de um AE
			- Dores comuns entre várias pessoas (ex.: pipeline de dados redundante, inconsistente)
		- Onde está o problema com AEs
			- Gostariam de trabalhar na parte da tecnologia em si, mas muitas vezes precisam entender o negócio pra que as soluções façam sentido 
			- Entender o negócio é um processo potencialmente doloroso
	- O que motivou transição de Tech Manager para Manager?
		- Todo mundo que entra no Nubank que já era manager vira Tech Manager (responsável pela execução junto com o time)
		- Evolução de Manager 1 para Manager 2, ganha mais contexto
		- Contratações passam pelo detalhe

## Papo com BHub
- Dan - gerente de engenharia (financeiro/fintech + dados)
- Implementando Databricks - dando mais autonomia para os times consumirem dados na empresa
	- Ideia é ter um chapter de dados, com pessoas espalhadas, mas sem ter a disciplina em si implementada
	- Ex.: time de engenharia é dividido em chapters (ex.: SRE)
- Primeira versão com Athena, EMR, Glue - não funcionaram
- Em paralelo, uma versão do Data Lake usando BigQuery
- Como ferramenta de visualização, usando Metabase (possivelmente trocar no futuro)
- Desafio
	- Implementar o Databricks (boas práticas da ferramenta, features, camadas de transformação de dados)
	- Aplicações consumirem essas informações - ETL Reverso
	- Granularidade de acesso à informação é um desafio para o médio prazo
	- Como validar a POC?
	- Entregável é o formato ou é o resultado?

---

### Notes created today

```dataview

List FROM "" WHERE file.cday = date("2023-07-12") SORT file.ctime asc

```

### Notes modified today

```dataview

List FROM "" WHERE file.mday = date("2023-07-12") SORT file.mtime asc

```

### Notes linked to today

```dataview 

List without id link(file.link, title) where contains(this.file.inlinks, file.link)

```