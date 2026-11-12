# hexapod-hardware

Open-source hardware for 3D-printed six-legged walking robots. The repo has the CAD (STEP for editing, STL for printing), bills of materials, print lists and assembly docs. Shared electronics, including the [leg hub](electronics/leg-hub/) power and data board, are in [`electronics/`](electronics/).

## Variants

| Variant | Key hardware | Status |
|---|---|---|
| [Explorer](explorer/) | ST3215 servos, Raspberry Pi 5, lidar | v0.1, in development |

Each variant's folder has its own README, [print list](explorer/print-list.md), BOM and changelog.

## Licences

This repository uses two licences:

- **CAD, STLs and documentation**: [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE)
- **PCB designs** (everything in [`electronics/`](electronics/)): [CERN Open Hardware Licence Version 2 – Weakly Reciprocal (CERN-OHL-W-2.0)](electronics/LICENSE)

The source for this design is at <https://github.com/TH4R4V3N1324/hexapod-hardware>.
