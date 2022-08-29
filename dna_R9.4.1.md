# R9.4.1 chemistry

## NA12878 PromethION data (~30X)

- SRA: https://www.ncbi.nlm.nih.gov/sra/?term=SRS9414678
- associated publication: https://www.nature.com/articles/s41587-021-01147-4
- Notes: the complete dataset with 9.1M reads (93.4 Gbases), as well as a subset of 500,000 reads are available
    
### Complete Dataset (9.1M reads):

raw signal data:
| Description                                          | SRA accession                                                                                         |
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| BLOW5 format | [SRR22186402](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR22186402&display=data-access) |
| FAST5 format | [SRR15058166](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR15058166&display=data-access) |

basecalls:

| Basecaller    | model |SRA accession                                                                                         |
| ------------------ | ----| ---------------------------------------------------------------------------------------------------------- |
| Guppy 4.0.11 | dna_r9.4.1_450bps_hac_prom | [SRR15058167](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR15058167&display=download) | 

Super accuracy basecalls from a recent Guppy version is available on a in-house NAS. Contact using Github issues if you want me to share them.
    
### Subset (500,000 reads):
    
| Description                                          | SRA run Data access                                                                                        |
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |  
| BLOW5 format                   | [SRR22186403](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR22186403&display=data-access) |
| FAST5 format                    | [SRR15058164](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR15058164&display=data-access) |

basecalls:
| Basecaller    | model |SRA accession                                                                                         |
| ------------------ | ----| ---------------------------------------------------------------------------------------------------------- |
| Guppy 4.0.11 | dna_r9.4.1_450bps_hac_prom | [SRR15058164](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR15058164&display=download) | 

Super accuracy basecalls from a recent Guppy version is available on a in-house NAS. Contact using Github issues if you want me to share them.

---

Following are datasets uploaded by others. Some of them have very old basecalls. In some of them, raw FAST5 signal files are no longer working with latest Guppy. I have converted them to BLOW5 format and have basecalled using a very recent Guppy through [buttery-eel](https://github.com/Psy-Fer/buttery-eel). Those data is available in-house, so contact using Github issues if you want me to share them.


## NA12878 MinION data from Nanopore WGS Consortium

- link: https://github.com/nanopore-wgs-consortium/NA12878/blob/master/Genome.md
- associated publication: https://www.nature.com/articles/nbt.4060


## CHM13 from Telomere-to-telomere consortium project


- link: https://github.com/marbl/CHM13
- associated publication: https://www.science.org/doi/10.1126/science.abj6987


## SARS-CoV-2 SP1

- link: https://community.artic.network/t/links-to-raw-fast5-fastq-data-for-artic-protocol/17
- associated publication: https://www.sciencedirect.com/science/article/pii/S1477893920300806?via%3Dihub


## Yeast (Saccharomyces cerevisiae)

- link: https://www.ncbi.nlm.nih.gov/bioproject/PRJNA510813
- associated Publication: https://genome.cshlp.org/content/29/8/1329


## Chalmydomonas (Chlamydomonas reinhardtii)

- link: https://www.ncbi.nlm.nih.gov/sra/ERR3237140/
- associated associated publication: https://www.nature.com/articles/s41467-019-10168-2

#### Zymo data from LomanLab

- link: https://github.com/LomanLab/mockcommunity
