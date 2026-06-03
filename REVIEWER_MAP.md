# Reviewer Map

    ## Claim Scope

    - Canonical-lane claim: inside the `manifold_constrained` routed lattice, if the theorem chain in this repository holds and the guard certificate passes, the repository-level super-lane closure claim is satisfied.
    - Standard target claim: Across the declared admissible motive lattice, cycle-class filtrations, regulator maps, and expected vanishing/support constraints persist with the predicted motivic compatibility package.

    ## Super-Lane Families

    1. cycle-class and coniveau filtration control
2. regulator and special-value compatibility packages
3. motivic vanishing and support constraints
4. correspondence-induced filtration transport
5. local-global stitching of the declared motivic endpoint package

    ## Theorem Dependency Chain

    1. `EG1`: coercive projected response and active floor.
    2. `EG2`: routed-family capture across the declared lattice.
    3. `EG3`: compactness and no-collapse spacing for normalized towers.
    4. `EG4`: rigidity and endpoint transfer.
    5. Identification bridge: strict coherence on the determining class.
    6. Scalar closure: `BB_G1`, `BB_G2`, `BB_G3`, `BB_G4`, `BB_G5`, `BB_G6`, `BB_GM` all `PASS`.

    ## Falsification Conditions

    - `repro/certificate_runtime.json` has any non-`PASS` gate.
    - `lane.active_lane != "manifold_constrained"`.
    - `all_pass != true`.
    - Any manifest hash mismatch under `repro/repro_manifest.json`.
    - A verified counterexample to any routed family theorem used by the super-repo.
