# ONT R9.4.1 chemistry - RNA Data


Following are datasets uploaded by others. Some of them have very old basecalls.
In some of them, raw FAST5 signal files are no longer working with latest Guppy.
I have converted them to [BLOW5 format](https://www.nature.com/articles/s41587-021-01147-4) and have basecalled using a very recent Guppy through [buttery-eel](https://github.com/Psy-Fer/buttery-eel).


## GM12878 MinION cDNA data from Nanopore WGS Consortium

- link: https://github.com/nanopore-wgs-consortium/NA12878/blob/master/RNA.md
- associated publication: https://www.nature.com/articles/s41592-019-0617-2
- raw signal data converted to BLOW5 format can be obtained from [SRR23513622](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23513622&display=data-access). filename: `na12878_cDNA_blow5.tar` (md5sum: `cba2ce651d8c33528e594a9e45ff6515`)
- Guppy 6.1.3 high accuracy rebasecalled reads (through [buttery-eel wrapper](https://github.com/Psy-Fer/buttery-eel), with dna_r9.4.1_450bps_hac.cfg model) that passed the default qscore filter: [SRR23513619](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23513619&display=data-access).


## GM12878 MinION direct-RNA data from Nanopore WGS Consortium

- link: https://github.com/nanopore-wgs-consortium/NA12878/blob/master/RNA.md
- associated publication: https://www.nature.com/articles/s41592-019-0617-2
- raw signal data converted to BLOW5 format can be obtained from from [SRR23513624](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23513624&display=data-access). filename: `na12878_directRNA_blow5.tar` (md5sum: `282e305f2b6a72d28980a8d5c803d54e`. Also available for direct download from [na12878_rna_merged.blow5](https://slow5.bioinf.science/na12878_rna) (md5sum: `36bc164e9d885838245073f6cd2ecd79`), [na12878_rna_merged.blow5.idx](https://slow5.bioinf.science/na12878_rna_idx) (md5sum: `82f96208ac2f42574abe0cf5a3954602`)
- Guppy 6.1.3 high accuracy rebasecalled reads (through [buttery-eel wrapper](https://github.com/Psy-Fer/buttery-eel), with rna_r9.4.1_70bps_hac.cfg model) that passed the default qscore filter: [SRR23513623](https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR23513623&display=data-access).

## DNA datasets from Singapore Nanopore-Expression Project (SG-NEx)
- link: https://github.com/GoekeLab/sg-nex-data
- associated publication: https://doi.org/10.1101/2021.04.21.440736
- raw signal data converted to BLOW5 format can be obtained from [sg-nex-data-blow5 AWS S3 bucket](http://sg-nex-data-blow5.s3-website-ap-southeast-1.amazonaws.com/). We highly acknowledge [Jonathan Göke](https://github.com/jonathangoeke), [Chen Ying](https://github.com/cying111) for being open and hosting BLOW5 files through the AWS Open Data. Please visit [SG-NEx_blow5_tutorial](https://github.com/GoekeLab/sg-nex-data/blob/master/docs/SG-NEx_blow5_tutorial.md) on how you could use/analyse this data.
- Guppy 6.4.2 rebasecalled reads (through [buttery-eel wrapper](https://github.com/Psy-Fer/buttery-eel)) will be soon made available under [sg-nex-data AWS S3 bucket](http://sg-nex-data.s3-website-ap-southeast-1.amazonaws.com/).
