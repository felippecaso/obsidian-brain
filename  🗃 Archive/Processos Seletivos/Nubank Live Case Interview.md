# Nubank Live Case Interview
## Notas
- Lucas - desde fim 2019 - hoje governança e menos negócio
- Nériton - desde 2021 - entrou como manager e virou IC - hoje BU de IA para CX

- whiteboarding
- revisão de código (code review)
- perguntas mais amplas
## Business Case - investimentos de renda fixa
- Cliente A começa a investir em um produto no dia 16 do mês 1
- Realiza investimentos e saques em outros dias
- Tabela de entrada:
	- day: [16, 20, 2, 5]
	- month: [1, 1, 2, 2]
	- account_id: [A, A, A, A]
	- deposit: [1000, 500, 0, 1000]
	- withdrawal: [0, 0, 200, 200]
- No final do dia, deve gerar 0,01% de rendimento ao saldo
- Saldo é cumulativo com outros investimentos
- Se saldo for negativo, rendimento é igual a zero
- `Movements = Previous Day Balance + Deposit - Withdrawal`
- `End of Day Income = Movements * Income Rate`
- `Account Daily Balance = Movements + End of Day Income`
- Tabela de saída:
	- day: 1, 2, 3, 4, 5, ...
	- month: 1, 1, 1, 1...
	- account_id: 
	- deposit: 
	- withdrawal: 
	- end of day income: x, x, x, x
	- account daily balance: y, y, y, y

### Raciocínio
- começar com tabela dim_date e fazer left join
- movements: `lag(account_daily_balance) + deposit - withdrawal`
- eod income: `movements * income rate`
- account daily balance: `movements + eod income`

## Ambiente de dados
- Exemplo:
	- Em um cenário em que dois jobs em uma pipeline foram criados para rodar a cada noite, o primeiro job começa às 00h00 e normalmente termina em 20 minutos. O segundo job depende do primeiro e é iniciado, normalmente, às 00h30. Às vezes, o segundo job falha quando o primeiro job não termina até as 00h30, uma vez que o segundo job não tem o input necessário para rodar. O que poderia ser feito para evitar esse problema?
- Exemplo de resposta esperada: 
	- Poderiam ser utilizadas múltiplas tasks em um único job com uma dependência linear.

## Perguntas
- Mercado de Analytics tem se movimentado bastante nos últimos 2-3 anos, tanto em temas (ex.: analytics operacional, ETL reverso) quanto em ferramentas. Como é essa evolução no Nubank? Quanto esse tipo de decisão é tomada localmente (ex.: squad) ou globalmente (ex.: plataforma analítica pra empresa inteira)?
- Qual entrega mais têm orgulho na jornada do Nubank, e por que?