# Software

This directory is reserved for software artifacts other than the released raw dataset.

## Recommended Layout

| Directory | Contents |
| --- | --- |
| `host/` | upper-computer software, GUI, logger, control tools |
| `firmware/` | lower-computer embedded firmware |
| `protocol/` | communication protocol and packet definitions |
| `calibration/` | calibration scripts and templates |

If system-identification code is released in this repository later, place it under `software/identification/` and document the exact dataset split and dependency versions.

