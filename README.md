# DMSim
In silico simulation of deep mutational scanning data for SARS-CoV-2 spike protein receptor-binding domain (RBD) to predict the mutation effects with respect to two phenotypes of amino acid mutations within the SARS-CoV-2 spike protein receptor-binding domain (RBD). Fine-tunes the Evolutionary Scale Model 2 (ESM-2) protein language model (pLM) using Hugging Face.

## Deep Mutational Scanning (DMS) Datasets
`DMSim` uses deep mutational scanning (DMS) data produced by Jesse Bloom's lab at the Fred Hutchinson Cancer Research Center. The following data sources were compiled into one data source for use in this codebase and accessed via Google Drive. Feel free to request access to the compiled data source or reproduce into your own Google Drive with the included file `data/ACE2_RBD_final_variant_scores.csv`. This dataset is simply a concatenation of the original sources for ease of processing:

(1) https://github.com/jbloomlab/SARS-CoV-2-RBD_DMS_Omicron/blob/main/results/final_variant_scores/final_variant_scores.csv

(2) https://github.com/jbloomlab/SARS-CoV-2-RBD_DMS_variants/blob/main/results/final_variant_scores/final_variant_scores.csv

## To Run
Currently hosted as [Google Colaboratory notebook](https://colab.research.google.com/drive/1h8CN3szut_nN9pz4MneRsE5KMf1FvwLa) to enable ease of running on suitable hardware to fine-tune ESM-2 pLM. Use A100 GPU hardware (or better).
