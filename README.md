ExplorATE - Data Test
====
### Description

This folder contains the dataset to run the ExplorATE [vignette](https://femeniasm.github.io/ExplorATE_vignette/).
#### Model organisms data
***humans data set***
The `inputs_hs` directory contains simulated data from a human ovary sample. The `reads` subdirectory contains a subset of `.fastq` files from the original data set. Additionally, it includes a *de novo* transcriptome (`trme_hs.fa`) and a transcriptome-derived RepeatMasker file (`RM_trme_hs.out`).

***Drosophila melanogaster data set***
The inputs_dm directory contains a data set for *Drosophila melanogaster* based on [Ohtani et al. (2013)](http://genesdev.cshlp.org/content/27/15/1656). This directory contains the files:
`geneModel_dm.gtf`, a gene model for the D. melanogaster genome (v3)
`genome_dm.fa`, a reference genome (v3)
`RM_gen_dm.out`, a genome-derived RepeatMasker file
`RM_trme_dm.out`, a RepeatMasker file derived from the transcriptome
`trme_dm.fa`, a *de novo* transcriptome for the data set

Users can download reads in `.fastq` format from Gene Expression Omnibus (accession no. `GSE47006`). See the ExplorATE [vignette](https://femeniasm.github.io/ExplorATE_vignette/).
#### Non-model data set
The inputs_lp directory contains a subset of *Liolaemus parthenos* data. The complete data set is available in Gene Expression Omnibus (accession no `GSE173261`). The directory contains:
`reads`, a folder with the reads in .fastq (subset) format
`blastAnot_lp.outfmt6`, a BLAST output, in output format 6, for the *de novo* transcriptome
`geneModel_lp.gff3`, a TransDecoder output file
`RM_lp`, a RepeatMasker file for the *de novo* transcriptome (subset)
`trme_lp`, the *de novo* transcriptome (subset)

### How to use
Clone the repository to the desired directory with the following command.
```sh
git clone https://github.com/FemeniasM/ExplorATE_data_test
```

Access the desired data set and unzip the files with the following
```sh
gzip -d *.gz
```

### User guide and vignette

Check the [vignette](https://femeniasm.github.io/ExplorATE_vignette/) and the [user guide](https://femeniasm.github.io/ExplorATE_user_guide/) for more information.

