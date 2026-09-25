# Projeto 23 — SYNC PROTOCOL

## Objetivo

Permitir que a IA usada por Marco e a IA usada por Eduardo compartilhem **mudanças materiais** sem reenviar todo o contexto do projeto.

O GitHub é a superfície versionada comum.  
O sync comunica somente o delta.

## Quando gerar SYNC DELTA

Gerar quando ocorrer pelo menos um:

- nova evidência que muda o estado;
- resultado computacional relevante;
- decisão humana ratificada;
- mudança de interpretação;
- abertura/fechamento de gate;
- novo modelo ou mecanismo aceito;
- mudança de proveniência;
- alteração relevante na arquitetura do projeto.

Não gerar por:

- brainstorm;
- paper isolado ainda não integrado;
- ajuste textual;
- hipótese descartável;
- busca sem consequência;
- tentativa computacional sem efeito no estado.

## Formato

Cada sync deve conter:

### BASELINE
Commit, tag ou estado a partir do qual o trabalho começou.

### SCOPE
ZA, ZG, shared ou project-wide.

### NEW EVIDENCE
Somente fatos/evidências novas.

### RESULTS
Resultados novos, incluindo negativos e nulls.

### INTERPRETATION CHANGE
O que mudou na leitura científica e por quê.

### HUMAN DECISIONS
Somente decisões explicitamente ratificadas por Marco e/ou Eduardo.

### OPEN GATES
Bloqueios, dependências ou decisões pendentes.

### NEXT SAFE STEP
Menor próximo passo sustentado pelo estado.

### ARTIFACTS
Arquivos/commits necessários para reproduzir ou auditar o delta.

## Regra de autoridade

Em conflito:

`fonte primária > decisão humana ratificada / PROJECT_STATE > artefato científico auditado > SYNC DELTA > resumo conversacional`

Um SYNC DELTA não promove sozinho uma proposta a decisão.

## Recebimento

A IA receptora deve:

1. verificar o baseline;
2. comparar o delta com seu estado local;
3. incorporar apenas as superfícies afetadas;
4. preservar tudo que não foi alterado;
5. sinalizar conflitos reais;
6. atualizar `PROJECT_STATE.md` somente quando houver mudança material aceita.

## Git discipline

Preferir commits pequenos e semanticamente claros.

Exemplos:

- `ZA: freeze M0 input interfaces`
- `ZA: add tested minimal movement kernel`
- `ZG: reproduce baseline transition matrix`
- `sync: integrate Eduardo ZA data audit`

Evitar commits vagos como `updates`, `final`, `misc`.

## Filosofia

O objetivo não é sincronizar conversas inteiras.

O objetivo é tornar recuperável:

> o que mudou, por que mudou, qual evidência sustenta a mudança e o que pode ser feito a seguir.
