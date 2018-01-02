# chewBBACA_schemas
Whole genome MLST (wgMLST) schemas formated for [**chewBBACA**](https://github.com/B-UMMI/chewBBACA/wiki)

# *Salmonella enterica*
## Schema creation and validation
The wgMLST schema V2 from EnteroBase, including 21,064 loci, have been downloaded and curated using chewBBACA AutoAlleleCDSCuration for removing all alleles that are not coding sequences (CDS). The quality of the remain 21,032 loci have been assessed using chewBBACA Schema Evaluation and loci with single alleles, those with high length variability (i.e. if more than 1 allele is outside the mode +/- 0.05 size) and those present in less than 0.5% of the *Salmonella* genomes in EnteroBase at the date of the analysis (~81,000 genomes April 2017) have been removed. A total of 9,127 loci have been used as schema for calling alleles in the 4,590 *Salmonella* genomes using chewBBACA Allele Calling engine. The wgMLST schema have been further curated, excluding all those loci detected as “Repeated Loci” and loci annotated as “non-informative paralogous hit (NIPH/ NIPHEM)” or “Allele Larger/ Smaller than length mode (ALM/ ASM)” by the chewBBACA in more than 1% of the dataset. 

## wgMLST *Salmonella enterica*
The **wgMLST Salmonella enterica schema** included a total of **8,558 loci**. 

* [schema *Salmonella enterica* (7z file part 1)](https://drive.google.com/file/d/1WaYKk4bMe35BJMRuHx7nG82zFW8eHkXQ/view?usp=sharing)
* [schema *Salmonella enterica* (7z file part 2)](https://drive.google.com/file/d/1TgmEPukeu1vIuw-DlKU_GxcibDnUzkr1/view?usp=sharing) 

## Database information *Salmonella enterica*
As reference dataset, **4,313** public available draft or complete genome assemblies and available metadata of *Salmonella enterica* have been downloaded from public repositories (i.e. EnteroBase - https://enterobase.warwick.ac.uk/, National Center for Biotechnology Information NCBI - https://www.ncbi.nlm.nih.gov/ and The European Bioinformatics Institute EMBL-EBI - https://www.ebi.ac.uk/; accessed April 2017). The collection includes **1,465** *S.* Enteritidis, **2,410** *S.* Typhimurium, and **438** of other frequently isolated serovars in Europe (EFSA/ ECDC, 2016). The dataset includes also **148** *S.* Typhimurium variant 4,[5],12:i:- collected from different Italian regions between 2012 and 2014 during a surveillance study and  **129** *S.* Enteritidis belonging to the **[INNUENDO Sequence Dataset](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxpbm51ZW5kb2NvbnxneDo2YmYyOGU0MjE4ZGJiMmQ0)**.

## core genome MLST (cgMLST) profile *Salmonella enterica*
The **cgMLST profile**, defined as the loci presence in at least the **99% of the samples**, consists of **3,255 loci**.

* [cgMLST allele profile *Salmonella enterica*](https://drive.google.com/file/d/123gRLK4WzkQ6-zv1oO8_X1Q9Wn4QSPtH/view?usp=sharing) 

