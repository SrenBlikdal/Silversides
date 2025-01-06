# Silversides
WGBS analysis of Atlantic silversides 

## Atlantic silversides analysis

###Chapter 1 (to do: images from fastqc & attach the multiQC report) 
Processing of fastq files to obtain cytosine reports for input in R 
-Adapter removal
-Hardtrimming
-Adjust reference genomes
-(bsgenome stuff)
-Mapping
-Deduplication 
-Output

###Chapter 2 (to do: ...) 
What does the data tell us about the methylation level 
- Read in the data and metadata
- Problem with insufficient data (binomial)
- CpG coverage 
- Number of CpGs Covered at different thresholds
- Output >=2 in most samples 

###Chapter 3 ( to do: move local analysis to part 8)
Filtering potential SNPs from methylation data 
-Problem with SNPs in WGBS data
-Indications (mean methylation levels)  
-Data available 
-Analysis 
-SNP-free output

###Chapter 4 
#Removal of batch effects from methylation data
#-Problem with batch effects in WGBS data
#-Indications (PCA and mean methylation levels)
#-DMRs between batches
#-After ComBat
#-Indications (PCA and mean methylation levels)
#-DMRs between batches => none

###Chapter 5
Exploratory data analysis (PCA and mean methylation levels)
-PC1 vs length 
-lm()

###Chapter 6
Differential methylation analysis (BSseq analysis)
-Smoothing of methylation levels
-fstat for DMRs between groups incl. fwer
#-Remove batch effects from smoothed values - rewrite 2 fstat and tstat
#-Rewrite plot functions to include batch adjusted values
#-fstat for DMRs between groups  incl. fwer
-overlaps between DMRs groups and DMRs batches
-tstat R1 vs groups 
-log10 vs pos for each group 

-Fst and mean methylation


###Chapter 7 
Annotation of mean methylation
Annotation of DMRs
Table of candidate genes and DMRs
Size + methylation correlation

###Chapter 8
genetic structure within groups
-D2 chr24 inversion analysis
-NN -> NS -> SS t-test 
-plot DMR including the snp differences.

###Chapter 9
Nanopore chr24 inversion analysis

Methylation calling 
Mapping to ref genome
Whatshap and haplotagging 
Import to BSseq
CpG likelihood filtering - 
T-test 
