# PROJECT STATE

**Data de corte:** 2026-09-25  
**Status:** `ACCEPTED_OPERATIONAL_STATE`

## 1. Foco ratificado

O scouting amplo inicial foi encerrado.

Foco operacional:

- `ZA — Zombie Ant Search / behavioral manipulation`
- `ZG — Graveyard Dynamics / chronic cadaver-mediated transmission`

Linhas como competição EPF, threshold/barrier, epizootias e life-history permanecem preservadas, porém estacionadas.

## 2. ZA

### Proveniência

- `ZA-R0d`: modelo NetLogo depositado no Mendeley — **RECONSTRUCTED / METRIC_AUDITED / VERSION-SPECIFIC**.
- `ZA-R0p`: superfície correspondente ao modelo final publicado em 2021 — **BLOCKED / FINAL VERSION NOT RECOVERED**.
- `ZA-independent`: família de modelos especificada independentemente pelo Projeto 23.

Essas superfícies nunca devem ser fundidas semanticamente.

### Resultado independente já estabelecido

Um baseline de busca produziu ótimo intermediário de turning. Um null espacial estruturado reproduziu essencialmente o mesmo padrão.

Interpretação aceita:

> o ótimo expressa, no baseline, um trade-off genérico entre exploração e residência.

Interpretação não autorizada:

> a geometria empírica dos cadáveres de zombie ants seleciona especificamente esse turning.

### ZA-M0

Pergunta operacional em preparação:

> Quanto da organização espacial das posições de morte de zombie ants pode emergir de uma alteração mínima da locomoção normal, sem fornecer à formiga simulada informação sobre onde outros indivíduos morreram?

Arquitetura:

- `M0N` — natural-search null, restringido pelo repertório locomotor saudável.
- `M0Δ` — menor perturbação locomotora necessária caso M0N falhe.

Observáveis primários planejados:

- distância radial ao ninho;
- distância à trilha quando a geometria numérica estiver disponível;
- estrutura espacial/clustering;
- `Δ_manipulation`;
- generalização entre ambientes.

Regra de expansão:

`M0 → residual → exatamente um mecanismo biologicamente informado → kill-test`.

### Gate atual ZA

`ZA_M0_DATA_AUDIT_PRECOMPUTE = COMPLETE_WITH_RAW_DATA_ACCESS_GAPS`

Antes de compute original:

1. inspecionar o schema bruto do dataset de tracking saudável ou extrato oficial equivalente;
2. recuperar/materializar a tabela longitudinal de Loreto em formato utilizável;
3. congelar interfaces de entrada;
4. implementar kernel M0 mínimo e testado.

**Nenhum grande parameter sweep está autorizado.**

## 3. ZG

Baseline de Andersen et al. (2012):

`Fresh → Stroma → Mature → Hyperparasitized`

Estado:

- `ZG-R0: PASS`
- `ZG-R1: PASS_WITH_CAVEAT`
- `ZG-R2: PASS_QUALITATIVE`

A caveat ligada a `Pm` deve ser preservada.

Direções de aprofundamento ainda não ratificadas incluem modulação ambiental, sucesso de frutificação, hiperparasitismo, exposição crônica e forcing temporal.

## 4. Ponte ZA–ZG

Hipótese modular possível:

`manipulação → posição de morte → destino do cadáver → graveyard infeccioso → nova exposição`

Status: `OPTIONAL_INTERFACE / NOT_REQUIRED_ARCHITECTURE`.

ZA e ZG devem permanecer compreensíveis separadamente até que uma pergunta científica exija o acoplamento.

## 5. Guardrails

- fato ≠ inferência ≠ hipótese ≠ proposta ≠ decisão;
- fonte original ≠ reconstrução ≠ modelo independente;
- preservar nulls, resultados negativos e caveats;
- não reiniciar scouting amplo sem decisão humana;
- não criar model zoo;
- não acoplar escalas por estética;
- não adicionar mecanismo antes de um residual justificar sua entrada;
- documentação não deve crescer mais rápido que a ciência.

## 6. Próximo passo materialmente útil

Fechar as interfaces empíricas faltantes de ZA-M0 e, somente depois, implementar o kernel mínimo testável.

ZG permanece pronto como baseline paralelo, sem necessidade de acoplamento imediato.
