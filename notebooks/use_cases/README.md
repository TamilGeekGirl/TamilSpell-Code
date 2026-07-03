# Use-case notebooks 

This folder contains notebooks that demonstrate how TamilSpell can be used after publication. 

## Notebooks 

| Notebook | Description | 
|---|---| 
| `tamilspell_benchmark_vaani.ipynb` | Uses TamilSpell as a benchmark for evaluating a Tamil spell checker | 
| `tamilspell_neural_training_mbart.ipynb` | Uses TamilSpell as training data for a neural spelling-correction model | 

## Use case 1: TamilSpell as a benchmark 
The benchmark notebook demonstrates how to: 
1. select a TamilSpell subset,
2. submit erroneous sentences to a Tamil spell checker,
3. collect system outputs,
4. compare outputs with the TamilSpell corrected sentences, and
5. calculate accuracy by error category.

## Use case 2: TamilSpell for neural model training 
The neural training notebook demonstrates how to: 
1. load TamilSpell examples,
2. prepare source and target sentence pairs,
3. split data into training and validation sets,
4. tokenise the data,
5. fine-tune a neural sequence-to-sequence model, and
6. evaluate correction performance.

## Notes 

The full TamilSpell corpus should be downloaded from the official DOI before running these notebooks.
