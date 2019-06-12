# LEI
## Lancaster Estimator of Independence 
LEI is a measure of marker informativeness comparing multiple ancestral populations. LEI algorithm can be useful to find ancestry informative markers (AIMs) for two-way and multi-way admixed populations using the reference allele frequency data. The R codes provided here are free to download, use, and distribution for non-commercial purpose. The online PAMAM tool can be accessed from https://research.cchmc.org/mershalab/LEI/login.html. 

To compute LEI from the reference genotype-level data, use the R-function 
          
          lie_geno(x, y)
      
      where, x = vector of genotypes coded as 0, 1, or 2 based on # of reference alleles, length of x = total numbers of ancestral samples genotyped in the reference panels and y = vector of population membership. Length of y = length of x.
To compute LEI from the reference genotype-level data, use the R-function 
          
          lie_freq(k, frq_pop, count_pop)
       
       where, k = number of poulations, frq_pop = a vector of reference allele frequencies for the k populations, count_pop = corresponding population size, a vector of length k.
