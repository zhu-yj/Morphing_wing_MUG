# Raw Motion-Capture CSV Files

This directory contains selected raw Tracker motion-capture CSV files.

## Selection Rule

Included experiment indices:

```text
2-4, 7-9, 14-61
```

Excluded experiment indices:

```text
1, 5-6, 10-13
```

## Filename Convention

Typical filename:

```text
1128_23_4-Tracker0.csv
```

Meaning:

- `1128`: experiment date or batch code.
- `23`: experiment index.
- `4`: repeated trial number.
- `Tracker0`: motion-capture tracker identifier.

## Notes for Reuse

Document the coordinate frame, sampling frequency, marker/rigid-body definition, and preprocessing procedure in `data/metadata/` if processed data are added later.

