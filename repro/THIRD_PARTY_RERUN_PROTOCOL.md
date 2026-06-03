# Third-Party Rerun Protocol

1. Clone the repository.
2. Run `bash repro/run_repro.sh`.
3. Confirm that `repro/certificate_runtime.json` reports `BB_G1` through `BB_G6` and `BB_GM` as `PASS`.
4. Confirm that `scripts/release_gate.py --mode fully_extracted` returns `ok = true`.
5. Confirm that all tracked hashes in `repro/repro_manifest.json` match.
6. Read `paper/BLOCH_BEILINSON_CONJECTURES_PREPRINT.md` with the super-repo interpretation in mind.
