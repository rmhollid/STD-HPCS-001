# STD-HPCS-001 Manifest

## Latest validated local revision

`STD-HPCS-001_v0.16.2`

## Local artifact set

| Path target | Artifact | Status |
| --- | --- | --- |
| `standards/` | `STD-HPCS-001_v0.16.2.txt` | generated locally, validated |
| `validation/` | `STD-HPCS-001_v0.16.2_validation.log` | generated locally |
| `validation/` | `STD-HPCS-001_v0.16.2_canonical.log` | generated locally |
| `reports/` | `STD-HPCS-001_v0.16.2_content_report.txt` | generated locally |

## Validation record

```text
VALID
COMPLIANT
STRUCTURALLY_ACCEPTED
EXACT_VERSION
canonical_hash = 44939a890b6fa71026e9d3038ffb16d22c5d55ddf13cf9fd3d2fafc985271565
```

## v0.16.2 expansion

`v0.16.2` preserves candidate branches and replaces rejection posture with proof/disproof posture.

Added or corrected:

- proof-status language
- `UNPROVEN`
- `PROVEN_IN_TEST_ENVELOPE`
- `DISPROVEN_IN_TEST_ENVELOPE`
- `INDETERMINATE`
- `NEEDS_DISCRIMINATING_TEST`
- `CTI_HPCS_PROOF_RECORD`
- `CTI_HPCS_PROOF_STATUS_ALGORITHM`
- bounded disproof by material, geometry, operating regime, measurement method, baseline, and uncertainty envelope

## Intended directory layout

```text
/
├── README.md
├── MANIFEST.md
├── standards/
│   └── STD-HPCS-001_v0.16.2.txt
├── validation/
│   ├── STD-HPCS-001_v0.16.2_validation.log
│   └── STD-HPCS-001_v0.16.2_canonical.log
└── reports/
    └── STD-HPCS-001_v0.16.2_content_report.txt
```

## Scope lock

Only `STD-HPCS-001` material belongs in this repository. Do not mix unrelated STSF standards into this repo.
