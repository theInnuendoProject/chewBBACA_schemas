# *Campylobacter coli*

## Dataset
All whole genome raw sequence reads of entries deposited in the European Nucleotide Archive (ENA) as *Campylobacter coli* were retrieved using [getSeqENA](https://github.com/B-UMMI/getSeqENA). Genomes were assembled using [INNUca v3.1 pipeline](https://github.com/INNUENDOCON/INNUca). Species was confimed using [GScompare](http://gscompare.ehu.eus/) and assigned to one of the three described major phylogenetic clades ([Sheppard et al., 2013](https://www.ncbi.nlm.nih.gov/pubmed/23279096?dopt=Abstract); [Skarp-de Hann et al., 2014](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3928612/)) using phylogenetic analysis and hierBAPS clustering of *[atpA](https://www.ncbi.nlm.nih.gov/nuccore/KF855277)* gene as described in [Culebro et al., 2018](https://www.nature.com/articles/s41598-018-21438-2). The dataset contains a total of **4,558** *C. coli* genomes.

* [Minimal metadata of *C. coli* dataset](https://drive.google.com/open?id=1CtSGEECC0PohOJmPETz4SdBRi6AcLWCI)

## Schema creation and validation
Draft genome assemblies were annotated using Prokka and initial pangenome was defined using Roary. The [*chewBBACA CreateSchema.py*](https://github.com/B-UMMI/chewBBACA/wiki/1.-Schema-Creation) was used for creating a whole genome schema starting from roary pangenome. The schema was initially composed by 4,112 loci and has been populated with the **4,558** *C. coli* genomes. The quality of the loci have been assessed using [*chewBBACA Schema Evaluation*](https://github.com/B-UMMI/chewBBACA/wiki/1.-Schema-Creation). Loci with single alleles and those with high length variability (i.e. if more than 1 allele is outside the mode +/- 0.05 size) have been removed. The wgMLST schema have been further curated, excluding all those loci detected as “Repeated Loci” and loci annotated as “non-informative paralogous hit (NIPH/ NIPHEM)” or “Allele Larger/ Smaller than length mode (ALM/ ASM)” by the [*chewBBACA Allele Calling*](https://github.com/B-UMMI/chewBBACA/wiki/2.-Allele-Calling) engine in more than 1% of the *C. coli* genomes dataset. 

## wgMLST schema
The **wgMLST *C. coli* schema** includes a total of **2,477 loci**.

* [schema *C. coli* (7z archive)](https://drive.google.com/open?id=1Pkqbl6RvRj7MLBxOJ15jmbbV13CrnVS6)
* [wgMLST allele profile of 4,558 *C. coli*](https://drive.google.com/open?id=1uBpE_G7GtBJRyQ7luUWbMqrtbvpfsPWn)

## core genome MLST (cgMLST) profile
The **cgMLST profile**, defined as the loci presence in at least the **99.9% of the samples**, consists of **528 loci**. Genomes have no more than 2% of missing loci.

* [cgMLST allele profile of 4,558 *C. coli*](https://drive.google.com/open?id=1iDDQ6QmYzOybYz_i9hL59ei_XeKgjxrs)
* [goeBURST clustering of the cgMLST profile of 4,558 *C. coli* at all possible thresholds](https://drive.google.com/open?id=1xol-xDpnOOK9--FRYoFPa7chliPaWKC7)
