# Projeto 23

Pesquisa computacional interdisciplinar em fungos entomopatogênicos, ecologia/evolução e sistemas hospedeiro–parasita.

**Pesquisadores:** Marco Antonio Amaral e Eduardo Perovano  
**Estado operacional:** `ZA_ZG_FOCUSED / ZA_M0_PRECOMPUTE`  
**Arquitetura:** FPM-lite + Atlas-native

## Entrada rápida para Eduardo

Se você está começando agora, use primeiro:

- [EDUARDO_START_HERE.md](EDUARDO_START_HERE.md) — explicação curta de como trabalhar com o projeto e com a IA.
- [prompts/EDUARDO_AI_START_PROMPT.md](prompts/EDUARDO_AI_START_PROMPT.md) — prompt pronto para iniciar uma nova conversa de trabalho.
- [sync/EDUARDO_FLOW_GUIDE.md](sync/EDUARDO_FLOW_GUIDE.md) — mapa simples de como a informação circula entre Eduardo, a IA, GitHub e Marco.

Não é necessário conhecer a arquitetura FPM/Atlas para usar o projeto.

## Objetivo

Desenvolver ciência pequena, mecanisticamente clara, reproduzível e publicável, seguindo a regra:

> pergunta pequena → modelo mínimo → resultado interpretável → robustez proporcional.

O foco inicial ratificado é:

- **ZA — Zombie Ant Search / manipulação comportamental**
- **ZG — Graveyard Dynamics / transmissão mediada por cadáveres**

Outras linhas exploradas permanecem preservadas como possibilidades futuras, mas não são o foco operacional atual.

## Comece aqui — estrutura técnica

- [PROJECT_STATE.md](PROJECT_STATE.md) — estado científico vigente e gates.
- [autoboot/COMPACT_BOOT.md](autoboot/COMPACT_BOOT.md) — boot econômico para uso cotidiano.
- [autoboot/PROACTIVE_BOOT.md](autoboot/PROACTIVE_BOOT.md) — boot completo para uma nova instância de IA.
- [sync/SYNC_PROTOCOL.md](sync/SYNC_PROTOCOL.md) — protocolo de sincronização Marco ↔ Eduardo.
- [za/README.md](za/README.md) — estado e próximos gates de ZA.
- [zg/README.md](zg/README.md) — estado e próximos gates de ZG.

## Regra de proveniência

Manter separadas:

1. fontes e códigos originais de terceiros;
2. reconstruções independentes;
3. modelos originais do Projeto 23.

Nunca promover uma reconstrução independente como código original.

## Política para dados e literatura

Este repositório é público. **Não versionar aqui** PDFs protegidos, datasets brutos de terceiros, credenciais, arquivos locais ou materiais cuja redistribuição não esteja claramente autorizada.

Dados públicos grandes devem permanecer em seus repositórios de origem e ser referenciados por DOI/URL e metadados de proveniência. Dados derivados pequenos e redistribuíveis podem ser adicionados posteriormente com documentação explícita.

## Estado atual

ZA já possui auditoria do modelo depositado, baseline independente red-teamed e desenho pré-compute ZA-M0. ZG possui baseline de replicação funcional. O acoplamento ZA–ZG permanece opcional e só deve ser aberto quando uma pergunta científica exigir a interface.

Nenhum grande sweep computacional está autorizado no estado atual.
