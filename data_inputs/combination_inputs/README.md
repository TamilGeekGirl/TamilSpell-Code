
# Combination input files 
This folder contains input files used for generating 2-way and 3-way TamilSpell error combinations. These files specify sentences that already contain one or more error types and identify positions that should not be altered when adding a non-word error. 

## Files 
| File | Description | 
|---|---| 
| `rwe_with_unaltered_positions_input.tsv` | Input file for generating real-word + non-word error combinations | 
| `se_with_unaltered_positions_input.tsv` | Input file for generating sandhi + non-word error combinations | 
| `rwe_se_2way_input.tsv` | Input file for real-word + sandhi two-way combinations | 
| `rwe_se_3way_input.tsv` | Input file for real-word + sandhi + non-word three-way combinations | 
## Expected format 
The expected format is usually tab-separated. 

```text
sentence_with_existing_error corrected_sentence unaltered_positions
```

The `unaltered_positions` column identifies word positions that should not be changed when generating additional non-word errors.
