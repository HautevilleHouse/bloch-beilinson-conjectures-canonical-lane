# EG4 Public Note (Rigidity and Endpoint Transfer)

Mature wording: `bad-limit exclusion / endpoint transfer`.

In-paper anchor: `paper/BLOCH_BEILINSON_CONJECTURES_PREPRINT.md` (`BB_G4`, `BB_G5`).

## Goal
Separate the rigidity job from the endpoint-transfer job for `proving persistence of admissible motivic filtrations, regulator compatibilities, and cycle-class packages through a multi-lane motivic super-architecture`.
The older wording `rigidity and endpoint-transfer` corresponds to bad-limit exclusion plus the bridge into the intended endpoint object.

## Objects

- bad-limit class: candidates extracted by the compactness gate but incompatible with closure.
- rigidity floor: `1.078`.
- endpoint-transfer lock: `1.0305400000000002`.
- coherence interface: `0.0` remains available to the bridge and final margin.

## Closure Criterion

`BB_G4` closes when `1.078` excludes bad endpoint alternatives: bad endpoint alternatives are excluded by the rigidity monitor.
`BB_G5` closes when `1.0305400000000002` transfers the surviving endpoint to the intended target class: the rigid endpoint transfers to the intended problem-side class.
Together they feed the strict margin `M_BB`.

## Lemma Chain and Proof Payload

### Lemma EG4.1 (bad-limit exclusion)
Every extracted bad limit contradicts a declared rigidity constraint or leaves the admissible class.

Payload: verify `1.078` in the registry and certificate surfaces.

### Lemma EG4.2 (endpoint transfer)
The surviving rigid representative is locked to the standard problem-side endpoint by `1.0305400000000002`.

Payload: read this note together with `notes/IDENTIFICATION_BRIDGE.md`.

### Theorem EG4.3 (rigidity/transfer gate closure)
If bad limits are excluded and the endpoint lock is active, then `BB_G4` and `BB_G5` deliver the boundary object needed by the final margin.

## Current Instantiation

- rigidity gate: `BB_G4`
- rigidity artifact key: `1.078`
- transfer gate: `BB_G5`
- transfer artifact key: `1.0305400000000002`
- mature equivalent: `bad-limit exclusion / endpoint identification`
- audit surface: `notes/IDENTIFICATION_BRIDGE.md` and `repro/certificate_runtime.json`
