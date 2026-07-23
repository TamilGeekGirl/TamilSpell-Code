# TamilSpell code repository 
This repository contains the code, input files, notebooks, documentation, and use-case experiments associated with **TamilSpell**, a large-scale Tamil spelling error corpus. The full TamilSpell corpus has been published as a citable dataset in the University of Dundee Discovery Research Portal. 

**DOI:** [10.15132/10000260](https://doi.org/10.15132/10000260) 
**Dataset page:** https://discovery.dundee.ac.uk/en/datasets/tamilspell-a-tamil-spelling-error-corpus/ 

## What this repository contains 
This repository contains: 
1. input files used during corpus construction,
2. the original corpus-generation notebook,
3. notebooks for TamilSpell use cases,
4. code and scripts for reproducibility,
5. documentation and figures, and
6. small example files showing the expected data format.

## What this repository does not contain 
This repository does **not** contain the full final TamilSpell corpus. Please access the full corpus using the DOI above. 

## Main workflows
### Corpus construction

The original corpus-generation notebook is available at:

notebooks/corpus_generation/TamilSpell.ipynb

This notebook contains the code used for Tamil character setup, keyboard-neighbour construction, non-word error generation, isolated error generation, and 2-way and 3-way error-combination generation.

### TamilSpell as a benchmark

The benchmark use-case notebook is available at:

notebooks/use_cases/VAANI_TESTING_Final.ipynb

This workflow demonstrates how TamilSpell can be used as a benchmark for evaluating a Tamil spell checker.

### TamilSpell for neural model training

The neural training use-case notebook is available at:

notebooks/use_cases/TamilSpell_Sandhi.ipynb

This workflow demonstrates how TamilSpell can be used as training data for a neural spelling-correction model.

## Installation

For the core corpus-generation notebook:

pip install -r requirements-core.txt

For the benchmark use case:

pip install -r requirements-benchmark.txt

For the neural model training use case:

pip install -r requirements-neural.txt

## Licence

The code in this repository is released under the MIT License. See LICENSE.

The TamilSpell corpus and associated data files are licensed separately under the Creative Commons Attribution-NonCommercial 4.0 International License, CC BY-NC 4.0. See DATA_LICENSE.md.

## Citation
A journal article describing the construction, structure and applications of TamilSpell is currently under review. Once the article has been published, users should cite both the dataset and the article. 

Paper citation: [To be added following publication]

Dataset citation:
DOI: 10.15132/10000260

## Repository structure 

```text TamilSpell-code/
├── data_inputs/ Input files used by the corpus-construction code
├── notebooks/ Corpus-generation and use-case notebooks
└── docs/ Documentation and figures

