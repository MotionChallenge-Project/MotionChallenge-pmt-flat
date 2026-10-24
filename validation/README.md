# Native inference validation

`native-parity.json` records 160 cases and four resets against the original PMT
observation functions, ActorCritic and Isaac Lab coordinate transforms. The report
includes per-field errors, tolerances and checkpoint/source identities.

`validate_inference.py --help` lists the source and checkpoint inputs. Their
required hashes are pinned in `native-sources.json`; the script executes the
original inference functions without importing the Isaac simulator.
