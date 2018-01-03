# *Escherichia coli*
## Schema creation and validation
The wgMLST schema from [EnteroBase](https://enterobase.warwick.ac.uk/species/ecoli/download_data) have been downloaded and curated using *chewBBACA AutoAlleleCDSCuration* for removing all alleles that are not coding sequences (CDS). The quality of the remain loci have been assessed using *chewBBACA Schema Evaluation* and loci with single alleles, those with high length variability (i.e. if more than 1 allele is outside the mode +/- 0.05 size) and those present in less than 0.5% of the *Escherichia* genomes in [EnteroBase](https://enterobase.warwick.ac.uk/species/index/ecoli) at the date of the analysis (April 2017) have been removed. The wgMLST schema have been further curated, excluding all those loci detected as “Repeated Loci” and loci annotated as “non-informative paralogous hit (NIPH/ NIPHEM)” or “Allele Larger/ Smaller than length mode (ALM/ ASM)” by the *chewBBACA Allele Calling* engine in more than 1% of a dataset composed by **2,337 *Escherichia coli*** genomes.

## wgMLST schema
The **wgMLST *Escherichia coli* schema** included a total of **7,601 loci**. 

* [schema *Escherichia coli* (7z file part 1)](https://drive.google.com/file/d/1NvphfcSoUyrX4qnyxjnPTv1lrBVHpK5R/view?usp=sharing)
* [schema *Escherichia coli* (7z file part 2)](https://drive.google.com/file/d/1b-tCodCZclnt2_TpAPYgQh_bYVGOUtCf/view?usp=sharing) 

## Dataset
As reference dataset, **2,218** public draft or complete genome assemblies and available metadata of *Escherichia coli* have been downloaded from [EnteroBase](https://enterobase.warwick.ac.uk/species/index/ecoli) in April 2017. Genomes have been selected on the basis of the ribosomal ST (rST) classification available in [EnteroBase](https://enterobase.warwick.ac.uk/species/index/ecoli): from the same rST, genomes have been randomly selected and downloaded. The number of samples for each rST in the final dataset is proportional to those available in [EnteroBase](https://enterobase.warwick.ac.uk/species/index/ecoli) in April 2017. The dataset includes also **119** *E.coli* VTEC belonging to the **[INNUENDO Sequence Dataset](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxpbm51ZW5kb2NvbnxneDo2YmYyOGU0MjE4ZGJiMmQ0)**.

* [Minimal metadata of *E. coli* dataset]() *file to be added*

## core genome MLST (cgMLST) profile
The **cgMLST profile**, defined as the loci presence in at least the **99% of the samples**, consists of **2,360 loci**.

* [cgMLST allele profile *Escherichia coli*](https://drive.google.com/file/d/1n-6a2gCZx2zxoBHmpMt-v_rkDfmImTG_/view?usp=sharing)
* [goeBURST partitions](https://drive.google.com/file/d/13spszs5jMqJCXisQA2Mehm9zvrr0veRW/view?usp=sharing)
