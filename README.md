# PYEAST Data

Companion data repository for [PYEAST](https://github.com/TomLoan/PYEAST) — a Python toolkit for yeast genetic engineering.

This repository contains the biological sequence data and reference files that PYEAST uses to design cloning experiments.

## Contents

| Folder | Description |
|---|---|
| `component_libraries/` | Genetic part libraries (promoters, terminators, markers, fluorescent proteins, MoClo parts) |
| `integration_sites/` | Genomic target sequences for chromosomal integration |
| `primers/` | Example primer plate layouts |
| `templates/` | Reference genome and plasmid sequences |

## Private Data

The `private/` directory mirrors the public folder structure but is excluded from version control. You can add your own proprietary sequences, primers, and templates there and PYEAST will search both locations automatically.

```
private/
├── component_libraries/
│   ├── OpenPichia_MoClo_lvl1/
│   ├── Saccharomyces_cerevisiae/
│   ├── Yeast_Moclo_lvl_0/
│   └── Yeast_MoClo_lvl_1/
├── integration_sites/
├── primers/
└── templates/
```

## Usage

This repository is downloaded automatically when you run `pyeast init` after installing PYEAST. See the [PYEAST repository](https://github.com/TomLoan/PYEAST) for full installation and usage instructions.
