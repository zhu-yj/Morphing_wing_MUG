# Data

This directory contains the public experimental dataset.

## Current Release

| Directory | Contents |
| --- | --- |
| `raw_mocap_csv/` | selected raw motion-capture CSV files |

The current CSV subset includes experiment indices:

```text
2-4, 7-9, 14-61
```

## Future Additions

If processed data are later released, use:

```text
data/
├── raw_mocap_csv/
├── processed_mocap/
├── metadata/
└── examples/
```

Recommended metadata files:

- `metadata/dataset_manifest.csv`: file path, size, checksum, category.
- `metadata/data_dictionary.md`: column definitions, units, coordinate frames.
- `metadata/train_test_split.md`: exact train/test split used in the paper.

