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

# STJUDE usage

## for latest guide-seq output table

```

module load conda3/202402

source activate /home/yli11/.conda/envs/captureC

python OTSA2.py -i G4501_pool.matched.final.high_confidence.tsv -o G4501_pool -rc total_guideseq_reads  -off target_aligned -on on_target_sequence


```

