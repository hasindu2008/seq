# R9.4.1 chemistry

## NA12878 PromethION data (~30X)

- SRA: [SRS9414678](https://www.ncbi.nlm.nih.gov/sra/?term=SRS9414678)
- associated publication: https://www.nature.com/articles/s41587-021-01147-4
- Notes: the complete dataset with 9.1M reads (93.4 Gbases), as well as a subset of 500,000 reads are available
    
### Complete Dataset (9.1M reads):

#### raw signal data:
| Description                                          | SRA accession                                                      | Direct download link (md5sum) | 
| ---------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------|
| [BLOW5 format](https://www.nature.com/articles/s41587-021-01147-4) | [SRR22186402](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR22186402&display=data-access) |  [na12878_prom_merged.blow5](https://slow5.page.link/na12878_prom_slow5) (`7e1a5900aff10e2cf1b97b8d3c6ecd1e`), [na12878_prom_merged.blow5.idx](https://slow5.page.link/na12878_prom_slow5_idx) (`a78919e8ac8639788942dbc3f1a2451a`)    |
| FAST5 format | [SRR15058166](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR15058166&display=data-access) | [fast5.tar.gz](https://slow5.page.link/na12878_prom) (`0adbd2956a54528e92dd8fe6d42d2fce`) |



#### basecalls:

| Basecaller    | model |SRA accession                                                                                         |
| ------------------ | ----| ---------------------------------------------------------------------------------------------------------- |
| Guppy 4.0.11 | dna_r9.4.1_450bps_hac_prom | [SRR15058167](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR15058167&display=download) | 

Super accuracy basecalls from a recent Guppy version is available on a in-house NAS. Contact using Github issues if you want me to share them.
    
### Subset (500,000 reads):

#### raw signal data:
| Description                                          | SRA run Data access                                                                                        |Direct download link (md5sum) | 
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |  ------------------------------|
| [BLOW5 format](https://www.nature.com/articles/s41587-021-01147-4)                   | [SRR22186403](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR22186403&display=data-access) |[subsample_slow5.tar](https://slow5.page.link/na12878_prom_sub_slow5) (`6cdbe02c3844960bb13cf94b9c3173bb`) |
| FAST5 format                    | [SRR15058164](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR15058164&display=data-access) | [subsample.tar.gz](https://slow5.page.link/na12878_prom_sub) (`591ec7d1a2c6d13f7183171be8d31fba`) |

#### basecalls:
| Basecaller    | model |SRA accession                                                                                         |
| ------------------ | ----| ---------------------------------------------------------------------------------------------------------- |
| Guppy 4.0.11 | dna_r9.4.1_450bps_hac_prom | [SRR15058164](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR15058164&display=download) | 

Super accuracy basecalls from a recent Guppy version is available on a in-house NAS. Contact using Github issues if you want me to share them.

---

Following are datasets uploaded by others. Some of them have very old basecalls. In some of them, raw FAST5 signal files are no longer working with latest Guppy. I have converted them to BLOW5 format and have basecalled using a very recent Guppy through [buttery-eel](https://github.com/Psy-Fer/buttery-eel). 


## NA12878 MinION data from Nanopore WGS Consortium

- link: https://github.com/nanopore-wgs-consortium/NA12878/blob/master/Genome.md
- associated publication: https://www.nature.com/articles/nbt.4060
- raw signal data converted to BLOW5 format can be obtained from [SRR23513620](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23513620&display=data-access). filename: `na12878_DNA_blow5.tar` (md5sum: `2d02a7706d00572dcd9fcfa96e0357f4`)
- Guppy 6.1.3 super accuracy rebasecalled reads (through [buttery-eel wrapper](https://github.com/Psy-Fer/buttery-eel), with dna_r9.4.1_450bps_sup.cfg model) that passed the default qscore filter: [SRR23513621](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23513621&display=data-access).


## CHM13 from Telomere-to-telomere consortium project

- link: https://github.com/marbl/CHM13
- associated publication: https://www.science.org/doi/10.1126/science.abj6987
- raw signal data converted to BLOW5 format can be obtained from [SRR23371619](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23371619&display=data-access). file name: `CHM13_T2T_ONT_blow5.tar` (md5sum: `04f9d1c6ea2d11ccfc131c8244f059d3`).
- Guppy 6.3.7 high accuracy rebasecalled reads (through [buttery-eel wrapper](https://github.com/Psy-Fer/buttery-eel), with dna_r9.4.1_450bps_hac.cfg model) that passed the default qscore filter: [SRR23365080](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23365080&display=data-access).

## SARS-CoV-2 SP1

- link: https://community.artic.network/t/links-to-raw-fast5-fastq-data-for-artic-protocol/17
- associated publication: https://www.sciencedirect.com/science/article/pii/S1477893920300806
- raw signal data in BLOW5 format and the associated BLOW5 index:
    - [SP1-raw-mapped.blow5](https://slow5.page.link/SP1-raw-mapped) (md5sum: `d87c60f70bf8646ee56bcee2795e7535`)
    - [SP1-raw-mapped.blow5.idx](https://slow5.page.link/SP1-raw-mapped-idx) (md5sum: `c79ef9280be63fad7c07e4352402ce7a`)
- Guppy 6.1.3 high accuracy rebasecalled reads (through [buttery-eel wrapper](https://github.com/Psy-Fer/buttery-eel), with dna_r9.4.1_450bps_hac.cfg model) that passed the default qscore filter in FASTQ format : [SP1-mapped_guppy_6.1.3_hac_pass.fastq.gz](https://seqdata.page.link/SP1-mapped_guppy_6_1_3_hac_pass)


## Yeast (Saccharomyces cerevisiae)

- link: https://www.ncbi.nlm.nih.gov/bioproject/PRJNA510813
- associated Publication: https://genome.cshlp.org/content/29/8/1329


## Chalmydomonas (Chlamydomonas reinhardtii)

- link: https://www.ncbi.nlm.nih.gov/sra/ERR3237140/
- associated associated publication: https://www.nature.com/articles/s41467-019-10168-2

## Zymo data from LomanLab

- link: https://github.com/LomanLab/mockcommunity
- associated publication: https://academic.oup.com/gigascience/article/8/5/giz043/5486468
- raw signal data in BLOW5 format and the associated BLOW5 index for the Zymo-GridION-EVEN-BB-SN sample:
    - [Zymo-GridION-EVEN-BB-SN.blow5](https://slow5.page.link/Zymo-GridION-EVEN-BB-SN) (md5sum: `d7c894164aef398907adc6c034dd3049`)
    - [Zymo-GridION-EVEN-BB-SN.blow5.idx](https://slow5.page.link/Zymo-GridION-EVEN-BB-SN-idx) (md5sum: `d7d5feae1107c6d4517ebb416dc02683`)
- Guppy 6.1.3 high accuracy rebasecalled reads (through [buttery-eel](https://github.com/Psy-Fer/buttery-eel) wrapper, with dna_r9.4.1_450bps_hac.cfg model) that passed the default qscore filter FASTQ format for the Zymo-GridION-EVEN-BB-SN sample: [Zymo-GridION-EVEN-BB-SN_guppy_6.1.3_hac_pass.gz](https://seqdata.page.link/Zymo-GridION-EVEN-BB-SN_guppy_6_1_3_hac_pass)
