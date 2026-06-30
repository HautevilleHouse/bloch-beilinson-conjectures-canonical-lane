# EG2 Public Note (Capture and Restart)

Mature wording: `transport / local-to-global transfer`.

In-paper anchor: `paper/BLOCH_BEILINSON_CONJECTURES_PREPRINT.md` (`BB_G2`).

## Goal
Expand the compressed capture/restart language into the local-to-global transport gate for `proving persistence of admissible motivic filtrations, regulator compatibilities, and cycle-class packages through a multi-lane motivic super-architecture`.

## Objects

- transport carrier: the admissible evolution, deformation, or routed lattice declared in the preprint.
- capture floor: `1.075`.
- restart law: the normalization/re-entry rule that keeps corrective steps inside the admissible class.
- carried losses: defect, restart, and normalization losses that must remain explicit.

## Closure Criterion

`BB_G2` closes when `1.075` survives admissible losses and restart corrections: capture/restart losses remain inside the declared defect ledger.
This is the transport contribution to `M_BB`.

## Lemma Chain and Proof Payload

### Lemma EG2.1 (transport accounting)
Every transport step used by the lane is charged to the declared defect ledger instead of being absorbed into prose.

Payload: verify that the capture constant `1.075` is present in the constants registry and extraction inputs.

### Lemma EG2.2 (restart preservation)
Restart or normalization preserves the declared admissible class and does not create an untracked remainder.

Payload: inspect the repro script and guard output for the gate tied to `1.075`.

### Theorem EG2.3 (capture gate closure)
If transport accounting and restart preservation hold, then `BB_G2` carries local control forward without breaking admissibility.

## Current Instantiation

- gate: `BB_G2`
- artifact key: `1.075`
- mature equivalent: `transport / local-to-global transfer`
- audit surface: `repro/run_repro.sh` and `repro/certificate_runtime.json`
