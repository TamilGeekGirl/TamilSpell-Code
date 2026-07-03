
# Real-word error input files

This folder contains input files for Tamil real-word errors.

Real-word errors are valid Tamil words that are incorrect in a given context.

## Files

| File | Description |
|---|---|
| `rwe_kn.txt` | Kuril--Nedil real-word error examples |
| `rwe_m.txt` | Mayangoli real-word error examples |

## Error codes

| Error code | Description |
|---|---|
| `RWE_KN` | Kuril--Nedil errors |
| `RWE_M` | Mayangoli errors |

## Expected format

The expected format is a tab-separated text file.

```text
sentence_with_error    corrected_sentence    edit_distance    error_code

Some source files may contain fewer columns before they are processed by the corpus-generation code.
