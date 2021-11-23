This repository is to analyze the results of the microRNA RACE NGS from RPE65-ERT2-cre x miR-204fl/fl x miR-211fl/fl mice.

# alignment

my sample coding file has a header in it, so SLURM_ARRAY_TASK_ID only took the first five samples.

therefore, I created align2.sh with a SLURM_ARRAY_TASK_ID of '7' so it would only align P6.
