# *Yersinia enterocolitica*

## Dataset
All whole genome sequences raw reads of entries deposited in the European Nucleotide Archive (ENA) as *Yersinia enterocolitica* at the time of the analysis (August 2017) were retrieved using [getSeqENA](https://github.com/B-UMMI/getSeqENA). Genomes were assembled using [INNUca v3.1 pipeline](https://github.com/INNUENDOCON/INNUca) and 115 passed the QC. In addition, 169 new genomes of *Y. enterocolitica* strains collected from 12 European countries in 25 years were sequenced and assembled as above (80 of which belonging to the **[INNUENDO Sequence Dataset](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxpbm51ZW5kb2NvbnxneDo2YmYyOGU0MjE4ZGJiMmQ0)**). All the genomes were typed using **[patho_typing software](https://github.com/B-UMMI/patho_typing)**  which predicted the phylogenetic position of *Y. enterocolitica* according to [Reuter et al., 2015](http://mgen.microbiologyresearch.org/content/journal/mgen/10.1099/mgen.0.000030) and the serotype for pathogenic strains: approximatelly 50% of the strains are serotype O:3, biotype 4, phylotype PG3.

* [Minimal metadata of *Y. enterocolitica* dataset](https://drive.google.com/file/d/1O6_Y79aqMhBn1ZL2KogLvxvV7UfseAQQ/view?usp=sharing) 

## Schema creation and validation
All the 284 genomes were used for creating the schema using **[chewBBACA suite](https://github.com/B-UMMI/chewBBACA)**. The quality of the loci have been assessed using [*chewBBACA Schema Evaluation*](https://github.com/B-UMMI/chewBBACA/wiki/1.-Schema-Creation) and loci with single alleles, those with high length variability (i.e. if more than 1 allele is outside the mode +/- 0.05 size) and those present in less than 1% of the genomes have been removed. The wgMLST schema have been further curated, excluding all those loci detected as “Repeated Loci” and loci annotated as “non-informative paralogous hit (NIPH/ NIPHEM)” or “Allele Larger/ Smaller than length mode (ALM/ ASM)” by the *chewBBACA Allele Calling engine* in more than 1% of a dataset.


## wgMLST schema
The **wgMLST *Yersinia enterocolitica* schema** included a total of **6,435 loci**.

* [schema *Yersinia entercolitica* (7z archive)](https://drive.google.com/file/d/16ZHNji8x95PigtLCHryIdwPM9dQ8Km71/view?usp=sharing)
* [wgMLST allele profile of 284 *Y. enterocolitica*](https://drive.google.com/file/d/10-TxsiFeoc-k0ZwaZJFhskRRBi6zIb7D/view?usp=sharing)

## core genome MLST (cgMLST) profile
The **cgMLST profile**, defined as the loci presence in at least the **99% of the samples**, consists of **2,403 loci**. Genomes have no more than 2% of missing loci.

* [cgMLST allele profile of 284 *Y. enterocolitica*](https://drive.google.com/file/d/1bFsgtzoCNEJstWqL60DPbweYO-6Qb_5s/view?usp=sharing)
* [goeBURST clustering of the cgMLST profile of 284 *Y. enterocolitica* at all possible thresholds](https://drive.google.com/file/d/14PHUeG2pC3UOmP8tqkgoLnwdVHSuD4RY/view?usp=sharing)
