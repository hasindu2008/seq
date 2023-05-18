# ONT R10.4.1 chemistry - DNA data

## NA24385 (HG002) PromethION data (~30X)

- SRA: https://www.ncbi.nlm.nih.gov/sra/?term=SRS16575602
- associated publication: https://www.nature.com/articles/s41587-021-01147-4
- info: sheared DNA libraries (~17Kb) were prepared using the ONT LSK114 ligation library prep and a R10.4.1 flow cell was used to generate ~30X genome coverage.
- Notes: the complete dataset with 15.3M reads (102.2 Gbases), as well as a subset of 500,000 reads are available

### Complete Dataset (15.3M reads):

raw signal data:
| Description                                          | SRA accession                                                       | Direct download link (md5sum)  |
| ---------------------------------------------------- | ------------------------------------------------------------------- |--------------------------------|
| BLOW5 format | [SRR23215366](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23215366&display=data-access)  | [PGXX22394_reads.blow5](https://slow5.page.link/hg2_prom_slow5) (`3498b595ac7c79a3d2dce47454095610`), [PGXX22394_reads.blow5.idx](https://slow5.page.link/hg2_prom_slow5_idx) (`1e11735c10cf63edc4a7114f010cc472`)|

basecalls:

| Basecaller         | model | Notes | SRA accession                                                                                               | Direct download link (md5sum)  |
| ------------------ | ----  | ----  | ---------------------------------------------------------------------------------------------------------- | ---------------------|
| Guppy 6.3.7 | dna_r10.4.1_e8.2_sup@v3.5.1 | live basecalling;  reads that passed the default qscore filter | [SRR23215363](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23215363&display=download) |         |
| Guppy 6.1.5 | dna_r10.4.1_e8.2_hac@v3.5.1 | reads that passed the qscore filter for threshold 9 | [SRR23215364](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23215364&display=download) |         |


### Subset (500,000 reads):

| Description                                          | SRA run Data access                                                                                        | Direct download link (md5sum)  |
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |--------------------------------|
| BLOW5 format                   | [SRR23215365](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23215365&display=data-access) |[hg2_subsample_slow5.tar](https://slow5.page.link/hg2_prom_sub_slow5)</sub> <sub>(`65386e1da1d82b892677ad5614e8d84d`)|




