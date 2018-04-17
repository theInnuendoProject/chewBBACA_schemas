
# *Salmonella enterica*

## Dataset
As reference dataset, **4,313** public available draft or complete genome assemblies and available metadata of *Salmonella enterica* have been downloaded from public repositories (i.e. [EnteroBase](https://enterobase.warwick.ac.uk/), [National Center for Biotechnology Information NCBI](https://www.ncbi.nlm.nih.gov/) and [The European Bioinformatics Institute EMBL-EBI](https://www.ebi.ac.uk/); accessed April 2017). The collection includes **1,465** *S.* Enteritidis, **2,410** *S.* Typhimurium, and **438** of other frequently isolated serovars in Europe (EFSA/ ECDC, 2016). The dataset includes also **148** *S.* Typhimurium variant 4,[5],12:i:- collected from different Italian regions between 2012 and 2014 during a surveillance study and  **129** *S.* Enteritidis belonging to the **[INNUENDO Sequence Dataset](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxpbm51ZW5kb2NvbnxneDo2YmYyOGU0MjE4ZGJiMmQ0)**.

* [Minimal metadata of *S. enterica* dataset](https://drive.google.com/open?id=1-IDEcxavmoc-QLfcNoGuup7Ru-zjR1Qo) 

## Schema creation and validation
The wgMLST schema from [EnteroBase](https://enterobase.warwick.ac.uk/species/senterica/download_data) have been downloaded and curated using [*chewBBACA AutoAlleleCDSCuration*](https://github.com/B-UMMI/chewBBACA/wiki/1.-Schema-Creation) for removing all alleles that are not coding sequences (CDS). The quality of the remain loci have been assessed using [*chewBBACA Schema Evaluation*](https://github.com/B-UMMI/chewBBACA/wiki/1.-Schema-Creation) and loci with single alleles, those with high length variability (i.e. if more than 1 allele is outside the mode +/- 0.05 size) and those present in less than 0.5% of the *Salmonella* genomes in [EnteroBase](https://enterobase.warwick.ac.uk/species/index/senterica) at the date of the analysis (April 2017) have been removed. The wgMLST schema have been further curated, excluding all those loci detected as “Repeated Loci” and loci annotated as “non-informative paralogous hit (NIPH/ NIPHEM)” or “Allele Larger/ Smaller than length mode (ALM/ ASM)” by the [*chewBBACA Allele Calling*](https://github.com/B-UMMI/chewBBACA/wiki/2.-Allele-Calling) engine in more than 1% of a dataset composed by **4,590 *Salmonella*** genomes.

## wgMLST schema
The **wgMLST *Salmonella enterica* schema** includes a total of **8,558 loci**. 

* [schema *Salmonella enterica* (.tar.gz)](https://drive.google.com/open?id=1pI2J3cXulauN8lWyI9lm1Mo4S4VRUfof) (120 Mb)
* [wgMLST allele profile of 4,590 *Salmonella enterica*](https://drive.google.com/file/d/1rk8R-O6uwAWdXkbxxZkUzP07mdMnvf3p/view?usp=sharing)

## core genome MLST (cgMLST) profile
The **cgMLST profile**, defined as the loci presence in at least the **99% of the samples**, consists of **3,255 loci**. Genomes have no more than 2% of missing loci.

* [List of cgMLST loci](https://drive.google.com/file/d/1mKNWqnMzHeYN1ZA3R_d3YiHlLFQc1eq-/view?usp=sharing)
* [cgMLST allele profile of 4,524 *Salmonella enterica*](https://drive.google.com/file/d/1UL4vtShHA6DLW-71R1MkAQUMmx9gH6EO/view?usp=sharing)
* [goeBURST clustering of the cgMLST profile of of 4,524 *Salmonella enterica* at all possible thresholds](https://drive.google.com/file/d/1qxKFhfq2b7YmXDY7NyxxFOv9yLm8Beku/view?usp=sharing)
