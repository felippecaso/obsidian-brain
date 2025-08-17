# 22Q3 Everest [[Giovanna Fiorito]]
## Avaliação Liderança
### Competências Loft
[Foco em Clientes] (5)
(+) Construção de entregas aderentes com as necessidades de stakeholders e do negócio (compartilhado com Utilização de Dados). Exemplo principal: área curada de métricas de Pricing e Supply 1P.

[Trabalho em Equipe] (5)
(+) Tem abertura e busca ativamente trabalhar em equipe, tanto com clientes e stakeholders quanto com pares na equipe de Analytics.
(-) No período avaliado, poderia ter desenvolvido como referência em explorar maior sinergia com pares dentro de BA - por exemplo na troca com Supply 3P ao construir a estrutura de dados. Já tem demonstrado em projetos mais recentes como Portfolio.

[Adaptabilidade] (4)
(+) Reage bem a mudanças de direção e prioridade dentro da equipe, adequando seu escopo e aprendizado de acordo com o necessário. Exemplo principal: atendimento aos times de Portfolio.
(+-) Tem oportunidade de ajudar a guiar a mudança a partir de dados e informações concretas com consistência. Exemplo de quando aconteceu: análises de oportunidades "perdidas" e reprocessamentos. Compartilhado com Utilização de Dados.

[Diversidade e Inclusão] (5)
(+) Se destaca por envolver quem precisa estar na mesa, com exemplos principais nos times de operações e tecnologia (produto + engenharia) de 1P.
(=) Dar continuidade, ampliando o campo de influência dessa competência para também garantir que pessoas e times têm voz na construção de melhores soluções.

### Competências Específicas
[Conhecimento Técnico e Prático] (5)
(+) Aplica conhecimento de SQL e modelagem com consistência em suas entregas, e também é reconhecida por pares como referência local para o stack de ferramentas.
(+) Faz bom uso de documentação, não só para seu próprio código mas também com o EPOD. Tem oportunidade de potencializar essa característica, fazendo da documentação uma alavanca para entregas mais consistentes e na direção correta.
(-) Pode trabalhar de forma mais ativa para simplificar algumas estruturas e dependências de dados, deixando o caminho mais pavimentado para o futuro com Analytics Engineering.

[Gestão de Tempo e Planejamento] (4)
(+) Teve evolução grande na competência, focando em "desapegar" de detalhes no dia-a-dia. Usa ferramentas (ex.: Jira) para ajudar a ter e dar visibilidade das tarefas - pode usar como forma de também dar maior visibilidade de entregas e prioridades macro.

[Comunicação e Influência] (4)
(+) Desenvolveu visibilidade das entregas com stakeholders de forma recorrente, em rotinas criadas para essa finalidade e de forma assíncrona no Slack.
(-) Pode compreender e colocar em prática alavancas de influência dentro de outros times, que podem trazer solução mais rápida para problemas que o negócio enfrenta. Exemplo ao participar de rotinas e cerimônias dos squads que acompanha.

[Utilização de Dados] (5)
(+) Tem domínio das métricas do negócio, e aplica esse conhecimento na priorização e construção de tabelas e visualizações. Exemplo principal na área curada de dashboards de Pricing, que demonstrou ter aderência grande com as necessidades do negócio.
(+) Construção de entregas aderentes com as necessidades de stakeholders e do negócio (compartilhado com Foco em Clientes).
(+-) Tem oportunidade de ajudar a guiar a mudança a partir de dados e informações concretas com consistência. Exemplo de quando aconteceu: análises de oportunidades "perdidas" e reprocessamentos. Compartilhado com Utilização de Dados.

### Performance e Resultados
**Acima do esperado**

Como L2, te enxergamos na etapa Mastering.

Você aplica seus conhecimentos de forma consistente para construir os resultados da equipe, focando no próprio desenvolvimento.

Principais entregas no período:
- Construção de camada analítica para pricing e supply em 1P, com base em estrutura de dados com alto nível de toil.
- Documentação extensiva que foi a principal forma de contornar os problemas na estrutura de dados e construir junto com stakeholders a mensuração de Pricing em 1P.
- Atuou diretamente para que métricas importantes do EPOD estivessem disponíveis, como volume de processamentos de precificação em 1P e conversões ao longo do funil.

Como próximos passos, enxergamos oportunidade de ajudar a guiar mais mudanças e melhorias no negócio dentro (e, eventualmente, até fora) do escopo que você está inserida. Além disso, a orientação de maneira geral é de expandir a área de influência de todas as suas competências.

## Autoavaliação
### Competências Loft
[Foco em Clientes] (5) - era 3
[Trabalho em Equipe] (5) - era 3
[Adaptabilidade] (4) - era 4
[Diversidade e Inclusão] (5) - era 3

A falta de visibilidade ponta a ponta de supply 1P já era a principal dor quando entrei na Loft, e conseguimos resolvê-la com a construção da tabela dm_1p.supply_e2e (e do dashboard principal, PPE | Supply E2E). Ela foi idealizada com base na necessidade dos times de operação de conseguirem acompanhar o topo de funil (foco em cliente), e construída integralmente por mim, com base em conceitos alinhados com as operações de supply e pricing (líderes e analistas), e, principalmente, com o squad de iBuyer Tools (trabalho em equipe e diversidade & inclusão). Um exemplo recente que ilustra a importância dessa entrega foi quando, no começo do mês, graças ao dashboard PPE | Supply E2E identificamos que a PAT estava há dias sem processar oportunidades de 3P — nesse incidente em questão, inclusive, dei suporte para o squad na parte de dados, bem como configurei um relatório (enviado automaticamente) de oportunidades não-processadas, enquanto eles paralelamente trabalhavam na solução que seria implementada na semana seguinte (mais detalhes do incidente: [https://loftbr.atlassian.net/wiki/spaces/VNT/pages/2753888614/2022-07-06+Oportunidades+de+Market+n+o+est+o+entrando+no+funil+de+Supply+1P](https://loftbr.atlassian.net/wiki/spaces/VNT/pages/2753888614/2022-07-06+Oportunidades+de+Market+n+o+est+o+entrando+no+funil+de+Supply+1P)). 

Pensando em adaptabilidade, sinto que tenho lidado bem com às mudanças que têm ocorrido e estou sempre revisando a estrutura de dados que criei para mantê-la aderente às necessidades da operação (acompanhamento de atualização de precificação), bem como mudanças de processos (migração da PAT para listings), e também mudanças dentro do time (dividir escopo de Portfolio com Vitor).

Recentemente, descobri junto com o squad que a operação de Market passou a subir os listings diretamente na LISA, sem criar oportunidade no Salesforce (impactando, portanto, o topo de funil de 1P, que depende de oportunidade de Market). A operação de 1P, até então, não estava sabendo dessa mudança e, proativamente, fui comunicá-los assim que soube, visto que impacta diretamente nos resultados deles.

### Competências Específicas
[Conhecimento Técnico e Prático] (5) - era 3
[Gestão de Tempo e Planejamento] (5) - era 2
[Comunicação e Influência] (5) - era 2
[Utilização de Dados] (5) - era 3

No final do ano passado e ao longo desse ano, tenho me aproximado cada vez mais do squad de iBuyer Tools e sinto que tenho conseguido influenciá-los muito positivamente na importância de dados (eg a criação de um épico para Governança de dados em Q2). Na definição dos OKRs de Q3 do squad de iBuyer tive um papel ativo, participando do brainstorm inicial junto com PM e APM (Perego e Ariane), bem como demais rodadas junto com o resto do squad, e, no final, acabamos com um KR voltado pra governança de dados e fonte única de verdade.

Hoje mesmo, durante uma reunião inicial sobre automação da etapa de qualificação (processo manual que atualmente acontece no Salesforce), o próprio Rud (principal engineer do squad) levantou a “bola" dos dados, perguntando "quais acompanhamentos analíticos vamos precisar?" — demonstrando preocupação com isso antes mesmo de começarem o desenvolvimento! Outro exemplo recente, do final do quarter passado, logo quando começaram a discutir a migração para listing, já me envolveram pois queriam saber como estava a estrutura de dados e quais impactos teríamos pela mudança. Para ilustrar o quão representativo é esse avanço, vale ressaltar que, no meu início na Loft, a situação era completamente diferente: nos primeiros meses acompanhando o squad, eu era frequentemente ignorada e tinha bastante dificuldade até em receber respostas para dúvidas conceituais.

Na metade do quarter passado, a implementação do framework de supply (principal iniciativa do quarter para batimento do KR de redução de precificação manual) estava travada porque a operação não confiava totalmente e tinha receio de perder visibilidade de alguns acompanhamentos (eg elegibilidade, pendências de auditoria, entre outros). Representando os squads de iBuyer Tools e de Portfolio Risk (criação do framework), tive papel protagonista em destravar a implementação, explicando no detalhe exatamente quais dados seriam impactados, quais acompanhamentos precisaríamos ajustar e quais novos acompanhamentos criaríamos para  os times de Políticas e Pricing Ops, bem como desenvolvendo uma maneira mais adequada de acompanhar o KR pós-mudanças da implementação do framework — além da confiança do squad, esse exemplo, demonstra que também conquistei a confiança dos times da operação.

O KR de conversão de listing para oportunidade 1P foi feito pensando na migração que a PAT faria para listings, desconsiderando que na época (e ainda hoje), a PAT depende de oportunidades de 3P. Por estar próxima do squad e conhecer detalhadamente o processamento da PAT, consegui propor um conceito mais aderente ao pretendido, bem como uma métrica mais estável, que poderá ser usada ao longo do quarter todo, mesmo com as mudanças que aconteceram e ainda irão acontecer (semana passada, tivemos uma primeira mudança no processamento da PAT, e a expectativa é termos mais uma mudança até o final de Q3).

Além de construir do zero a estrutura de dados analíticos da PAT, criei uma documentação completa no Confluence, explicando seu funcionamento, conceitos e detalhando como as tabelas analíticas foram criadas, trazendo transparência e clareza para dados que, alguns meses antes, sequer estavam disponíveis para consumo! Sei que isso é só o começo, e que ainda temos muito pra construir (e reconstruir), mas estou extremamente empolgada :)

### Performance e Resultados
**Acima do esperado**

Acredito que as entregas citadas e detalhadas acima são boas demonstrações de que, atuando próxima aos times que atendo, tenho sido bem-sucedida em estruturar soluções analíticas aderentes às necessidades da operação de iBuyer, me tornando referência nas frentes que cubro, e, consequentemente, conquistando a confiança dos meus stakeholders e também uma capacidade de influenciá-los acima do que é esperado de um L2.

## Feedbacks 360
### [[Pedro Barchi]]
Demandas urgentes solicitadas pela equipe de BI dentro de Finance para analise deep-dive de PPE que será entregue ao management (CFO e COO)

A Giovanna se mostrou excepcionalmente solicita, autônoma e competente durante o período de solicitação urgentes das informações por parte de BI, me ajudando amplamente em questões técnicas, construindo boa parte do código necessário para extração por si mesma, e não precisando de auxílio direto para exercer essas atividades.

Não seria exagero falar que os números não teriam saído com um terço da sua qualidade se não fosse a intervenção da Giovanna no tema, em particular no trabalho de conexão entre listing e unit_id. Não era sua obrigação me auxiliar no processo, mas ela o fez de maneira exemplar, e merece reconhecimento pelo mesmo.

### [[Ana Carolina Ribeiro]]
Adoro trabalhar com a Gi! super dentro da cultura da loft e de analytics, ela é alguém que sei que posso contar. Inteligente e dedicada, o sucesso é garantido :)  
  
Destaques:  
Sabe do que está falando - A Gi tem uma parte técnica incrível, e é uma referência em SQL para todo o time.  
Domina os contextos em que está inserida e pode facilmente ser vista como uma referência sobre eles.  
  
Contribuição para equipe - Além de mandar muito bem na parte técnica, ela ajuda muito os pares. Tira dúvidas, dá dicas de como melhorar as queries e compartilha todo o conhecimento que tem.  
  
Sempre aprendendo - A Gi tem muito interesse em aprender, é super aberta a dicas e se interessa em entender melhor todos os conceitos do negócio, estudando materiais e conversando com pares/stakeholders.  
  
Melhorias:  
Sobrecarga - A Gi tem tanta energia e vontade de fazer as coisas acontecerem, que as vezes pode se sobrecarregar. Muitas coisas são urgentes, mas o tempo de descanso é importantíssimo, e se eleger as prioridades direitinho, tudo se encaixa.  
  
Se impor - Nós mulheres costumamos duvidar um pouco da nossa capacidade e isso as vezes pode influenciar em como conseguimos impor as nossas ideias.  
A Gi já tem uma presença super ativa em reuniões e discussões de negócios, sempre falando com propriedade sobre os assuntos. Agora é só se impor como referência para os stakeholders e arrasar.

### [[Luiz Henrique Siqueira]]
Começar:
- Criação (ou dar visibilidade) para a estrutura de dados e acompanhamentos que estão sendo feitos  
- Maior visibilidade do planejamento para priorização e acompanhamento de entrega - vai ser extremamente importante incorporando portfólio

Continuar:
- Entendimento e estruturação de dados extremamente complexos com visão de operação (o que significa / como impacta) e alinhados com objetivos do grupo (rentabilidade e excelência operacional) - ex: estruturação de dados de supply teve impactos enormes tanto em operação (fluxo, problemas de processamento / outputs, esteira, eficiência) e risco (desvios do modelo, rentabilidade, qualidade do portfolio)  
- Conhecimento de operações/negócio que possibilita resolver problemas (ex, processamento de listings), definição de KRs/iniciativas de outros times e entendimento para pessoas de outras áreas (ex, weekly supply)

### [[Marcos Perego]]
Foco em clientes:  
  
A Gi é referência em foco nos clientes. Ela está sempre por perto do time de iBuyer, entendendo nosso direcionamento estratégico e produtos. Isso faz com que ela esteja a um passo à frente das nossas necessidades de dados e acompanhamentos.  
Muito ágil (muito mesmo) nas entregas, a Gi busca qualidade e velocidade, seja na construção de dashboards, auxiliando na definição de KRs ou montando relatórios para a squad e funil de 1P.  
Ponto para evoluir: tentar trazer uma visão ainda mais macro sobre a estratégia do time e 1P. Isso pode auxiliar na identificação de dores e consequentemente, em propostas de projetos e direcionamentos pros times. A Gi tem bom senso crítico e ao usar ele para explorar ainda mais o direcionamento de alto nível, isso pode trazer ótimos resultados.  
  
Trabalho em equipe:  
  
Colaborativa e comunicativa, a Gi tem participado bastante das nossas discussões técnicas e estratégicas, o que demonstra boa capacidade de lidar com diversos assuntos/pessoas. Puxa pessoas do time individualmente para atacar problemas e propor soluções e é super pró ativa.  
Compartilha bem as informações e descobertas e gosta de dar transparência e visibilidade.  
Ponto para evoluir: pode dar mais sua opinião nas reuniões com os times. Sinto que a Gi tem bastante conhecimento sobre o tema de 1P e pode compartilhá-lo cada vez mais com o time, promovendo/puxando ainda mais discussões.  
  
Adaptabilidade:  
  
A Gi navega bem nas incertezas do time e de como serão os próximos capítulos da nossa saga. Trabalha em conjunto com o time para pensar em soluções e é ágil quando temos mudanças estratégicas e de dados (agindo com antecedência em muitos cenários).  
Ponto para evoluir: fazer cada vez mais parte das tomadas de decisões dos times, através de discussões mais alto nível e estratégicas, auxiliando na priorização de alguns assuntos com os times que ela dá suporte.  
  
Diversidade e Inclusão:  
  
Trabalhar com a Gi tem sido muito gratificante e sei que ela navegaria bem com qualquer time. Muito aberta para papos, ela recebe bem os colegas e trabalha bem com todos. Escuta muito a opinião dos outros e é empática com o time.  
Ponto para evoluir: pedir proativamente mais feedbacks do seu trabalho e compartilhar mais feedbacks com o time. Sinto que a Gi está contente com o cenário e pessoas, mas isso não significa que não existem coisas que podem melhorar ao seu redor.

