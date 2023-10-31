# Validations for XBB.1.5 serum escape mutations

The notebooks in this repo contain analysis of serum escape mutants to validate data for [XBB.1.5 library experiments](https://github.com/dms-vep/SARS-CoV-2_XBB.1.5_spike_DMS) 


Data in this repo includes:
- Raw infectivity data for each mutant. At: [data/virus_titer_RLU/virus_titers.csv](./data/virus_titer_RLU/virus_titers.csv)
- Fraction infectivity data for each serum neutralization. At: [data/neuts/serum_neuts_batch2_frac_infectivity.csv](./data/neuts/serum_neuts_batch2_frac_infectivity.csv)
- DMS escape data taken from [XBB.1.5 library experiments](https://github.com/dms-vep/SARS-CoV-2_XBB.1.5_spike_DMS). At: [data/dms](./data/dms)

[config file](./config.yaml) contains paths to files above. 

Notebooks in this repo are as follows:
- Measure rescued luciferase-carrying virus infectivity. Notebook: [virus_titers.ipynb](virus_titers.ipynb).
- Plot neutralization curves for each virus mutant and compare to DMS data. Notebook: [virus_neutralization.ipynb](virus_neutralization.ipynb)


[plasmid_maps](./plasmid_maps) folder includes plasmid maps for each mutants used in neutralization experiments as well as plasmids used in XBB.1.5 and BA.2 library production experiments.

Outputs from each notebook can be found at [results](./results) folder.


By Bernadeta Dadonaite
