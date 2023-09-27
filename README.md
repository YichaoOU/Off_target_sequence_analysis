# Off-target sequence analysis

Reproduce figure 3 a-d in the CHANGE-seq paper
![image](https://github.com/YichaoOU/Off_target_sequence_analysis/assets/19987406/bb509318-912c-48fa-9d0b-5e47739e8522)

# Dependencies

- python3
- weblogo
- seaborn, matplotlib, pandas, Levenshtein, scipy, numpy

# Usage


```
OTSA.py -i change_seq_be.merged.tsv -o change_seq_BE -rc read_count -off seq -on Target_Sequence
```

