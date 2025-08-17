# Arquitetura
## Estrutura dos dados
- db: health
	- schema: raw
		- table: `{source}_{entity}`
- db: finances
	- schema: raw
		- table: `{source}_{entity}`
## Etapas
### ELT
- Meltano
- dbt
- Separação por domínio:
	- Finanças
	- Saúde
### Armazenamento
- S3
- Motherduck
- Local
### Ativação
#### Visualização
- Hex
- Evidence
#### Exploração
- Rill
- Motherduck
## Dados e fontes por domínio
### Finanças
- BTG
	- Cartão de crédito
	- Investimentos
	- Conta corrente
- Nomad
- Caju
- Itaú
- Legado
	- C6
	- Nubank
	- Alelo
	- BB
### Saúde
- Liti
	- Pesagens bioimpedência
	- Hábitos
- Apple Health
	- Atividade física
- Sleep Cycle