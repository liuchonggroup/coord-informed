# coord-informed

This repository provides the data-availability package for the manuscript:

**Coordination-Informed Machine Learning Enables Model-Based Screening of Phenanthroline Ligands for Predicted Am/Eu Binding Preference**

## Contents

```text
coord-informed/
├── data/
│   ├── screening/
│   │   └── low_uncertainty_8250_virtual_library_screening.csv
│   ├── SclogK_with_cb.tar.gz
│   ├── mono_ml_pair.tar.gz
│   ├── mono_ml_pair_split_10/
│   └── GibbsBeta.tar.gz
└── models/
    ├── cp_model/
    └── sc_logbeta1_ablation/
```

## Data

The `data/` folder contains the processed datasets and virtual-library screening outputs used in the study.

| Location | Content |
| --- | --- |
| `data/screening/` | Low-uncertainty virtual-library screening results for the 8,250 retained Phen-derived candidates. |
| `data/SclogK_with_cb.tar.gz` | Processed single-complex `logbeta` dataset with coordination-bond annotations. |
| `data/mono_ml_pair.tar.gz` | Processed mono-metal-ligand pair dataset. |
| `data/mono_ml_pair_split_10/` | Split upload parts for `mono_ml_pair.tar.gz`. |
| `data/GibbsBeta.tar.gz` | Processed GibbsBeta data archive. |
| `data/README.md` | Zenodo DOI, checksums and split-file reconstruction notes for the large processed data archives. |

Large data archives are deposited on Zenodo record `10.5281/zenodo.21386870`

## Models

| Location | Content |
| --- | --- |
| `models/cp_model/` | Released CP-model parameter file, test metrics and evaluation figures. |
| `models/sc_logbeta1_ablation/` | Released SC/logbeta1 model variants and test metrics. |

## Source Code

Model code, data-processing scripts and the packaged CP-connection workflow are maintained in the Hotpot GitHub repository:

<https://github.com/Zhang-Zhiyuan-zzy/hotpot>

## Citation

If these files are used, please cite the associated manuscript.
