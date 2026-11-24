# Duplicate-Aware Normal-Only Anomaly Detection for Wi-Fi/MQTT IoMT Traffic

**Published article:** [DOI: 10.4018/IJCSME.426864](https://doi.org/10.4018/IJCSME.426864)

This directory contains the research materials associated with the published paper: Jupyter notebooks, the retained CICIoMT2024 Wi-Fi/MQTT CSV dataset files, experiment artifacts, and references.

## Contents

| Directory or file | Contents |
| --- | --- |
| `Notebook/` | Research notebooks and analysis code |
| `Experiments/` | Publication experiment snapshots, configurations, outputs, metrics, and related artifacts |
| `DataSet/CICIoMT2024/` | Retained dataset files, descriptive documents, and file inventories |
| `references/` | Research reference materials |
| [`RAW_DATASET.md`](RAW_DATASET.md) | Official source and retrieval notes for raw PCAP files |

## Scientific scope

The reported methodology uses the Wi-Fi/MQTT CSV branch of CICIoMT2024:

- **Profiling:** 42 files (389,956 records) for normal-data training, validation, and testing.
- **Attack test:** 21 files (1,614,182 records) for evaluating anomalous traffic.
- **Attack train:** 51 files (7,160,831 records) used for duplicate and overlap auditing only, **not** for model fitting.

The Bluetooth documentation is included as part of the CICIoMT2024 dataset reference materials; Bluetooth traffic was not used in the reported experiments.

## Research reproducibility

The repository retains 114 CSV files and two publication experiment ZIP archives through Git LFS. Install Git LFS before cloning to retrieve these files. Raw PCAP captures are not included; their official source is documented in [RAW_DATASET.md](RAW_DATASET.md).

The experiment archives contain results and associated experimental materials. Reproducing the published results may additionally require compatible software dependencies and the official dataset. Dataset redistribution and reference-publisher rights should be checked before making this repository public.
