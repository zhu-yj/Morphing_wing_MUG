<p align="center">
  <img src="assets/overview_GitHub_1.png" width="820" alt="AWUG overview">
</p>

# Morphing-Wing MUG Open-Source Repository

This repository is the public release hub for the morphing-wing MUG platform. It is intended to collect the experimental dataset, hardware design files, electronics documentation, upper/lower computer software, and reproducibility notes associated with the paper.

## Current Contents

| Part | Status | Location |
| --- | --- | --- |
| Hardware overview image | included | `assets/overview_GitHub_1.png` |
| Raw motion-capture CSV dataset | included | `data/raw_mocap_csv/` |
| Mechanical hardware files | to be added | `hardware/` |
| Electronics and PCB files | to be added | `electronics/` |
| Host-side software | to be added | `software/host/` |
| Embedded firmware | to be added | `software/firmware/` |
| Communication protocol and calibration notes | to be added | `software/protocol/`, `software/calibration/` |
| Experiment and reproducibility notes | to be added | `experiments/`, `docs/` |

## Repository Layout

```text
Morphing_wing_MUG/
├── assets/                  # overview images, animations, README media
├── data/
│   └── raw_mocap_csv/        # selected raw motion-capture CSV files
├── hardware/                 # CAD, drawings, BOM, assembly, fabrication
├── electronics/              # electrical architecture, PCB, wiring, power
├── software/                 # host software, firmware, protocol, calibration
├── experiments/              # pool-test setup, procedures, logs, checklists
└── docs/                     # release checklist, paper wording, file naming
```

## Dataset Subset

The current dataset release contains raw motion-capture CSV files whose experiment indices are:

```text
2-4, 7-9, 14-61
```

The files are stored under `data/raw_mocap_csv/`. See `data/README.md` and `data/raw_mocap_csv/README.md` for details.

## Planned Release Items

Before the first complete public release, add:

- mechanical CAD source and neutral exports;
- manufacturing drawings and assembly instructions;
- bill of materials;
- PCB/schematic/Gerber files;
- wiring table, connector pinout, and power budget;
- upper-computer software;
- lower-computer firmware;
- communication protocol;
- calibration and experiment procedures;
- paper citation, DOI/arXiv link, and license information.

See `docs/release_checklist.md` for a more detailed checklist.

## Suggested Paper Link Statement

> The morphing-wing MUG hardware documentation, electronics files, software, and experimental dataset are available at `https://github.com/zhu-yj/Morphing_wing_MUG`.
