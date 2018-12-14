Analysis of overenrichment of DNMs in post-transcriptional functional sites
(details of data and method description please refer to https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/piDNM_ana.md)

updates including:

1, add CLIP RBP that are reported to be related to human disorders based on OMIM records (CLIPdb(OMIM)), 
breifly, 157 RBP recorded in OMIM were obtained from Castello A et al work  (Trends Genet. 2013 ), as a result, 7 of total 56 RBP from CLIPdb are related to human disorders.

2, for neuronfunction related genesets, I simply use 7 genes sets collected from the Werling's CWAS work as positive control, and non-mental related gene as negative control; 

3, add new functional region: overlap between RNA folding (RNAfold) and RBP binding sites (RBP&RNAfold) in the WGS dataset analysis part, and for RBP binding sites, RNAfold sites, I include those without splicing signal predicted by spidex  

 Results:
 
 1, WES data analysis (comparison of DNM count in specific regions with background mutation rate, using synonymous DNMs for study-specific normalization)
 
 1.1, for all mutations
 
 https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/2018-12-13/tt.WES_all.dnm.enrich.pdf
 
 1.2, for mutations from within neurofunction related genes
 
 https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/2018-12-13/tt.WES_neurongenes.dnm.enrich.pdf
 
 2, WGS data analysis (comparison of DNM count in specific regions between case and control datasets, using synonymous DNMs for study-specific normalization)
 
 2.1, for all mutations
 
 https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/2018-12-13/tt.WGS_all.dnm.enrich.pdf
 
 2.2, for mutations from within neurofunction related genes
 
 https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/2018-12-13/tt.WGS_neurongenes.dnm.enrich.pdf
 
 
 Conclusions:
 
1, LOF, damaging Nonsynonymous and splicing site predicted by spidex tend to be highly mutable;
2, minor but nonsignificant mutation enrichment for RBP binding sites;
3, lower mutation burden in NonMental genesets (negative control);
4, caution when analysis of mutation burden using gene sets that was defined based on our DNM data collections (such as ASD_risk_genes_TADA_FDR0.3, Developmental_delay_DDD etc.)

 
 
