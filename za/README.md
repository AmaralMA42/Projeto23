# ZA — Zombie Ant Search

## Current state

`ZA_M0_PRECOMPUTE`

### Provenance surfaces

- `ZA-R0d` — deposited Mendeley NetLogo surface; reconstructed and metric-audited.
- `ZA-R0p` — final 2021 publication surface; exact final implementation not fully recovered.
- `ZA-independent` — Projeto 23 independent model family.

Never merge these labels.

## Replication anchor

Imirzian & Hughes (2021), *An agent-based model shows zombie ants exhibit search behavior*, Journal of Theoretical Biology 526:110789. DOI: 10.1016/j.jtbi.2021.110789.

Associated deposited dataset: Mendeley Data DOI 10.17632/nmgz9kp8t8.1.

## What we learned

The deposited model and final paper are not identical surfaces.

An independent search baseline shows an intermediate-turning optimum, but a structured spatial null reproduces essentially the same pattern.

Therefore, pure search is baseline geometry, not yet biological novelty.

## ZA-M0 question

> How much of the spatial organization of zombie-ant death locations can emerge from a minimal change in normal locomotor behavior, without giving simulated ants information about where other zombie ants died?

### M0N

Natural-search null constrained by healthy-ant locomotion.

### M0Δ

Minimum locomotor perturbation if M0N fails.

### Primary observables

- radial distance to nest;
- distance to nearest trail where valid numerical trail geometry exists;
- simple spatial clustering statistics;
- manipulation distance from healthy locomotor repertoire;
- cross-environment generalization.

## Expansion rule

`M0 → residual → one mechanism → kill-test`

No environmental sensing, cadaver attraction, social interaction, 3D climbing, fungal development or ZA–ZG coupling in M0.

## Current gate

Before original compute:

1. inspect/freeze healthy-tracking input schema;
2. materialize the necessary Loreto longitudinal table;
3. freeze interfaces;
4. implement a tiny tested M0 kernel.

No large parameter sweep.
