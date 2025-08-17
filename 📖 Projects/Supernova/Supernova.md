# Supernova
## Ambiente de avaliações quinzenais
- Processo
	- AppSheet cria automaticamente registros esperados do ciclo
		- Data configurável na automação
		- Com todos os colaboradores ativos naquele momento e suas respectivas lideranças (é feita uma "foto" da base)
	- Notificação enviada por email para todas as lideranças informando que o preenchimento está disponível

### Tasks
- [x] Definir indicadores de avaliação
	- [x] Listar todos os indicadores da planilha
	- [x] Selecionar manualmente estruturas permitidas para cada indicador
	- [x] Documentação
- [x] Definir regras de ciclo: qual data de início, se precisa ser configurável, validar premissa da "foto" da base naquele momento
- [x] Criar AppScript para criação do ciclo na data de execução
- [x] Ajustar exibição das etiquetas na tela de avaliações a partir dos Refs
- [x] Configurar lista de indicadores por área do colaborador
- [x] Criar regra de exibição de acesso para lideranças somente das suas avaliações
- [x] Alterar permissão de visualização da página de configuração de indicadores de avaliação
- [x] Configurar início automático do ciclo dia 01 e 16
- [x] Alterar formatação de avaliações pendentes de preenchimento
- [x] Documentação da avaliação
- [x] Atualizar permissão de edição somente quando ciclo está aberto
- [ ] Painel com % de preenchimento para acompanhamento do RH
- [ ] Criar fluxo de notificação de email no início de ciclo
- [ ] Criar fluxo de cobrança de preenchimento do RH para liderança
## Kick-off
[[2024-10-28-Monday]]

Acesso:
pirata@asupernova.com.br
w3@emdXfBWsovcc
### Setup da Fonte Única
Tasks gerais
- [x] Adicionar conceito de matrícula
- [x] Definir estrutura de departamento e subdepartamento
- [x] Definir dados básicos de interesse
- [x] Checar se estrutura de liderança é coerente
- [x] Fazer backfill dos dados

Perguntas em aberto 
- Metas de cada colaborador: indicador para avaliação
	- Hoje é associado individualmente, no futuro a ideia é atribuir ao cargo

- Quem tem acesso:
	- Edição: pessoas de Gente e Gestão
	- Visualização: liderança

Épicos:
- [x] Desenvolvimento de POC para navegação
- [x] Validação da regra de controle de acesso
- [x] Validação de campos para registro
- [x] Backfill
- [ ] Implementação de visão histórica
- [ ] Implementação de pequenas validações de qualidade de dados (a confirmar)
- [ ] Documentação e treinamento
## Escopo
### Setup: Fonte única dos dados dos colaboradores
[Notion](https://www.notion.so/julia-benzaquen/Proposta-de-Trabalho-Super-Nova-Gente-e-Gest-o-65c8020a4d24421cbdb6ae8744ae3bb8?pvs=4#d2edb5f3eeb54b339a4c1d9493b0ec5b)
- Mapeamento e definição da origem da informação ou criação dessa infra
- Exemplos de informações que precisam ser mapeadas e registradas nessa fonte: entrada, saída, movimentações de colaboradores e atribuições de lideranças.

