# Sandhi error input files 
This folder contains input files for Tamil sandhi errors. Sandhi errors occur at word boundaries due to incorrect insertion or omission of Vallina Mei characters. 

## Files 
| File | Description | 
|---|---| 
| `se.txt` | Sandhi error examples | 

## Error codes 
| Error code | Description | 
|---|---| 
| `SE_VA` | Addition of Vallina Mei | 
| `SE_VD` | Deletion of Vallina Mei | 

## Expected format 

The expected format is a tab-separated text file. 
```text
sentence_with_error corrected_sentence edit_distance error_code
