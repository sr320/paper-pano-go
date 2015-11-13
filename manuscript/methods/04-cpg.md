CpG-methods

Germline methylation levels were inferred based on the hypermutability of methylated cytosines, which convert to thymines over evolutionary time. This results in a reduction in CpG dinucleotides, meaning that heavily methylated genomic regions are associated with reduced numbers of CpGs. Thus, methylation patterns that have been inherited through the germline over evolutionary time can be estimated using the ratio of observed to expected CpG, known as CpG O/E. Germline DNA methylation estimated by analysis of CpG O/E is highly correlated with direct assays of methylation ((Suzuki 2007), (Sarda 2012), (Gavery 2013)). CpG O/E was defined as:

CpG O/E = (number of CpG / number of C x number of G) x (l2/l-1)

where l is the number of nucleotides in the contig.

Only annotated sequences were used for calculation of CpG O/E to increase the likelihood that sequences were oriented in the 5' to 3' direction. For subsequent analyses, we set minimum and maximum limits for CpG O/E at 0.001 and 1.5, respectively, to exclude outliers. Details of germline methylation prediction methods are provided in jupyter notebooks