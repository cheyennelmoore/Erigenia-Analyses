#Erigenia bulbosa conservation genetics repo

This repository contains analyses of SNP data for Erigenia bulbosa in PA. The following files are included

##vcf_code.txt
Contains our [vcf filtering](vcf_code.txt) code from command line. We used vcf tools and utilized information in this [tutorial](https://speciationgenomics.github.io/filtering_vcfs/).

##Erigenia_vcf_stats.Rmd
This is [visualization and summary of our filtered vcf](Erigenia_vcf_stats.Rmd). Again, this code is based on this tutorial [tutorial](https://speciationgenomics.github.io/filtering_vcfs/).

##Erigenia_vcf_to_genlight.Rmd
This markdown [creates and uses a genlight](Erigenia_vcf_to_genlight.Rmd). Aspects of this code include converting from .vcf to genlight and PCAs and a DAPC. 
We primarily use the package adegenet in this markdown, but also have code from dartR.

##Erigenia_Fstats_GenDiv.Rmd
Here we calculate [F statistics and heterozygosity statistics](Erigenia_Fstats_GenDiv.Rmd) with hierfstat. We also check these stats with other packages ad well as make a Fst heatmap.

##Erigenia_IBD_amova.Rmd
Contains code to do tests for [Isolation By Distance and Analysis of Molecular Variance](Erigenia_IBD_amova.Rmd) (IBD and AMOVA). We use our genlight for this. 
For IBD we used dartR and adegenet. For AMOVA we used dartR and poppr. This Rmd also uses a supplemental file [Erigenia.strata](Erigenia.strata) for use with poppr AMOVA. 

##Erigenia_sMNF_new.Rmd
Analysis similar to STRUCTURE called [sMNF in package LEA](Erigenia_sMNF_new.Rmd). It should be noted that this analysis takes a bit of computing power and may crash R. 
For this analysis ywe also convert our vcf to a .geno file. 

#Old Files
[old_files](Old files) is a folder of old Rmds containing largely the same analyses but with more lax filtering. The code is also a bit messier. 


SRA link: https://www.ncbi.nlm.nih.gov/sra/PRJNA545957
