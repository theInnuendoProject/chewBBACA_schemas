# *Escherichia coli*
## Schema creation and validation
The wgMLST schema from [EnteroBase](https://enterobase.warwick.ac.uk/species/ecoli/download_data) have been downloaded and curated using *chewBBACA AutoAlleleCDSCuration* for removing all alleles that are not coding sequences (CDS). The quality of the remain loci have been assessed using *chewBBACA Schema Evaluation* and loci with single alleles, those with high length variability (i.e. if more than 1 allele is outside the mode +/- 0.05 size) and those present in less than 0.5% of the *Escherichia* genomes in [EnteroBase](https://enterobase.warwick.ac.uk/species/index/ecoli) at the date of the analysis (April 2017) have been removed. The wgMLST schema have been further curated, excluding all those loci detected as “Repeated Loci” and loci annotated as “non-informative paralogous hit (NIPH/ NIPHEM)” or “Allele Larger/ Smaller than length mode (ALM/ ASM)” by the *chewBBACA Allele Calling* engine in more than 1% of a dataset composed by 4,590 *Escherichia coli* genomes.

## wgMLST schema
The **wgMLST *Escherichia coli* schema** included a total of **7,601 loci**. 

* [schema *Escherichia coli* (7z file part 1)](https://drive.google.com/file/d/1NvphfcSoUyrX4qnyxjnPTv1lrBVHpK5R/view?usp=sharing)
* [schema *Escherichia coli* (7z file part 2)](https://drive.google.com/file/d/1b-tCodCZclnt2_TpAPYgQh_bYVGOUtCf/view?usp=sharing) 

## Dataset
*description missing*

## core genome MLST (cgMLST) profile
The **cgMLST profile**, defined as the loci presence in at least the **99% of the samples**, consists of **2,360 loci**.

* [cgMLST allele profile *Escherichia coli*](https://drive.google.com/file/d/1x-IkL508WRiNWSVNEKZlgkqUjP-Prjso/view?usp=sharing)
* [goeBURST partitions](https://drive.google.com/file/d/1QumrQ1R2ulBaQTkM2Z9Ii16764G1HvQq/view?usp=sharing)
