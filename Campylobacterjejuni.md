# *Campylobacter jejuni*

## Dataset
The dataset is composed by a total of **6,685** genomes. A total of  **5,691** whole genome sequences illumina raw reads of entries deposited in Sequence Read Archive (SRA) as *Campylobacter jejuni* were retrieved.  Additionally, the dataset contains **514** genomes previously published in [Kovanen et al., 2016](https://www.ncbi.nlm.nih.gov/pubmed/27041390), [Llarena et al., 2016](https://www.ncbi.nlm.nih.gov/pubmed/28348829), [Kovanen et al., 2014](https://www.ncbi.nlm.nih.gov/pubmed/25232158) and [Kovanen et al., 2014](https://www.ncbi.nlm.nih.gov/pubmed/24655229). Finally, **480** new genomes of *C. jejuni* strains collected from 5 European countries in 22 years and isolated from 12 different hosts were sequenced (**269** of which belonging to the **[INNUENDO Sequence Dataset](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxpbm51ZW5kb2NvbnxneDo2YmYyOGU0MjE4ZGJiMmQ0)**). Genomes were assembled using [INNUca v3.1 pipeline](https://github.com/INNUENDOCON/INNUca) and passed the QC. 

* [Minimal metadata of *C. jejuni* dataset](https://drive.google.com/file/d/1wJ77AeISR380m0k7f_MqCDv9D3bmgnwG/view?usp=sharing) 

## Schema creation and validation
Draft genome assemblies were annotated using Prokka and initial pangenome was defined using Roary. The *chewBBACA CreateSchema.py* script was used for creating a whole genome schema starting from roary pangenome initially composed by 5,447 loci. The schema have been populated with the **6,685** *C. jejuni* genomes and the quality of the loci have been assessed using *chewBBACA Schema Evaluation*. Loci with single alleles, those with high length variability (i.e. if more than 1 allele is outside the mode +/- 0.05 size) and those present in less than 0.5% of the *C. jejuni* genomes dataset have been removed. The wgMLST schema have been further curated, excluding all those loci detected as “Repeated Loci” and loci annotated as “non-informative paralogous hit (NIPH/ NIPHEM)” or “Allele Larger/ Smaller than length mode (ALM/ ASM)” by the *chewBBACA Allele Calling* engine in more than 1% of the *C. jejuni* genomes dataset. 

## wgMLST schema
The **wgMLST *C. jejuni* schema** included a total of **2,795 loci**.

* [schema *C. jejuni* (7z archive)](https://drive.google.com/open?id=1uJzxk6uwHNQJM92NDJy3vJrQQfSwLHhj)
* [wgMLST allele profile of 6,685 *C. jejuni*](https://drive.google.com/open?id=1t1TY4lqFsF2vL8eSvGjWZGujHgSNT1ih)

## core genome MLST (cgMLST) profile
The **cgMLST profile**, defined as the loci presence in at least the **99.9% of the samples**, consists of **678 loci**. Genomes have no more than 2% of missing loci.

* [cgMLST allele profile of 6,685 *C. jejuni*](https://drive.google.com/open?id=1nPihxWJKm0_-ojV_BI_AVcfBQq9B3pCI)
* [goeBURST clustering of the cgMLST profile of 6,685 *C. jejuni* at all possible thresholds](https://drive.google.com/open?id=119hQBf9yD1rpFcvdk4LTeMpvI1vybSaA)

