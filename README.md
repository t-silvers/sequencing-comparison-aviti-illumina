# Comparing AVITI and Illumina

## Usage

```bash
module load snakemake
echo "$SLURM_MAX_SUBMIT_JOB_LIMIT" # 225
snakemake --rerun-triggers mtime --resources njobs=$SLURM_MAX_SUBMIT_JOB_LIMIT
```