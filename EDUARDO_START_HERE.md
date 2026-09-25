# EDUARDO — COMEÇE AQUI

Este repositório permite que você trabalhe no Projeto 23 com uma IA sem precisar conhecer toda a arquitetura interna usada por Marco.

A ideia é simples:

1. **o GitHub guarda o estado compartilhado do projeto;**
2. **a IA lê esse estado antes de trabalhar;**
3. **você conversa normalmente com a IA;**
4. **quando surgir algo realmente novo, a IA prepara um pequeno pacote de atualização;**
5. **Marco e a IA dele conseguem incorporar só essa novidade, sem reconstruir toda a conversa.**

## O que você pode pedir à IA

Você não precisa usar termos técnicos do sistema.

Pode pedir coisas como:

- “Me explique onde o projeto está agora.”
- “Explique ZA de forma simples.”
- “Quais dados ainda faltam antes de simular?”
- “Analise esta ideia que tive.”
- “Compare esta hipótese com o modelo atual.”
- “Leia este artigo e diga se ele muda alguma coisa no projeto.”
- “Qual é o próximo teste mais simples?”
- “Prepare isso para eu mandar para Marco.”
- “Atualize o pacote de sincronização com o que descobrimos.”

A IA deve recuperar a estrutura necessária sozinha e explicar o contexto quando ele for importante.

## Dois temas ativos

### ZA — Zombie Ant Search

Estamos investigando quanto da organização espacial das mortes de formigas infectadas pode ser explicada por mudanças simples de locomoção, antes de acrescentar mecanismos mais complexos.

O próximo modelo mínimo é chamado **ZA-M0**.

### ZG — Graveyard Dynamics

Estamos estudando a dinâmica dos cadáveres infectados e sua progressão até estados capazes de contribuir para transmissão.

ZG já possui uma baseline de replicação funcional e pode ser aprofundado em paralelo.

## Como começar uma conversa nova com sua IA

Abra:

`prompts/EDUARDO_AI_START_PROMPT.md`

Cole o prompt na IA que estiver usando e forneça o link deste repositório.

Depois disso, converse normalmente.

## Quando você encontrar algo novo

Você não precisa organizar manualmente.

Diga à IA algo como:

> “Isso parece importante para o projeto. Prepare a atualização para Marco.”

A IA deve então produzir um **SYNC DELTA**: um resumo pequeno que registra apenas o que mudou, as evidências, dúvidas restantes e o próximo passo.

## O que não precisa fazer

Você não precisa:

- decorar nomes de arquivos;
- entender Git profundamente;
- repetir todo o histórico a cada conversa;
- decidir sozinho onde cada informação deve ser registrada;
- transformar toda ideia em documento;
- rodar grandes simulações antes de o modelo estar bem definido.

## Regra prática

Quando estiver em dúvida, simplesmente explique à IA o que está tentando entender.

Ela deve primeiro recuperar o estado do projeto, separar fato de hipótese e ajudar a encontrar o menor próximo passo útil.
