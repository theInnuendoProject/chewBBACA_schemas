# chewBBACA_schemas
Whole genome MLST schemas formated for [**chewBBACA**](https://github.com/B-UMMI/chewBBACA/wiki)

# *Salmonella enterica*
The wgMLST schema V2 from EnteroBase, including 21,064 loci, have been downloaded and curated using chewBBACA AutoAlleleCDSCuration for removing all alleles that are not coding sequences (CDS). The quality of the remain 21,032 loci have been assessed using chewBBACA Schema Evaluation and loci with single alleles, those with high length variability (i.e. if more than 1 allele is outside the mode +/- 0.05 size) and those present in less than 0.5% of the *Salmonella* genomes in EnteroBase at the date of the analysis (~81,000 genomes April 2017) have been removed. A total of 9,127 loci have been used as schema for calling alleles in the 4,590 *Salmonella* genomes using chewBBACA Allele Calling engine. The wgMLST schema have been further curated, excluding all those loci detected as “Repeated Loci” and loci annotated as “non-informative paralogous hit (NIPH/ NIPHEM)” or “Allele Larger/ Smaller than length mode (ALM/ ASM)” by the chewBBACA in more than 1% of the dataset. The final wgMLST schema included a total of 8,558 loci. The core genome MLST profile, defined as the loci presence in at least the 99% of the samples, consisted of 3,255 loci.

* [schema *Salmonella enterica* (7z file part 1)](https://drive.google.com/file/d/1WaYKk4bMe35BJMRuHx7nG82zFW8eHkXQ/view?usp=sharing)
* [schema *Salmonella enterica* (7z file part 2)](https://drive.google.com/file/d/1TgmEPukeu1vIuw-DlKU_GxcibDnUzkr1/view?usp=sharing) 
* [cgMLST allele profile *Salmonella enterica*](https://drive.google.com/file/d/123gRLK4WzkQ6-zv1oO8_X1Q9Wn4QSPtH/view?usp=sharing) 

