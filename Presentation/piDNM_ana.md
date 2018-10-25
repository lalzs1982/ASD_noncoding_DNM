
Aim of the this work is to analyze coding region DNM overenrichment that may not be contributed by codon changes, we collect DNMs from tens of neuro-psychaitric disorders family WES studies, calculate over enrichemnt of DNMs on possible functional coding regions (such as RBP binding, Ribsnitche, RBP-var2 predictions et al) across all stduies, with focus on DNMs from neuropsychiatric disease (such as ASD, ID, SCZ et al). The Data, Methods and main results are described as bellow: 

1, Data:
(1), DNM lists from several WES stduies of neuropsychiatric disorders:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/sample_sizes.xls

(2), RBP binding sites downloaded from the CLIPdb dataset
9,657,613 binding sites for 56 RBPs 

(3), Potential functional mutation predicted by the RBP-var2 software tool
4,189,690 mutations predicted as RBPvar cate 1/2 along the human coding gene transcripts regions

(4), Ribsnitch predicted by the RNAsnp software (p<0.05)
8,005,039 mutations on the human coding gene transcripts regions predicted as RNA structure change by the RNAsnp software.

(5), damaging nonsynonymous mutations was predicted by Polyphen2_HVAR (classified as P or D) and CADD (phered score > 30)
4,674,343 nonsynonymous mutations on the human coding gene transcripts regions predicted as damaging

(6), genome-wide DNM rate was obtained from published work of Jedidiah Carlson

(7), Coding regions excluding consensus splicing sites or splicing sites predcited by SPIDEX software tool (p<0.01)
according to the ENCODE gene annotation was analyzed in this work, there're are more than 200 million of them.
 

2, Methods:
Rate of DNM for specified genomic regions (for example RBP binding sites) vs rest of coding regions analyzed (as mentioned above)
was compared and the binomial test was used to estimate the difference significance. The expected DNM rate differences between genomic
regions was calculated using the sum of point DNM rates across region.         

3, Results:
In each plot bellow, we want to show the overenrichment of DNMs within each potantial genomic regions for each study seperately. Considering different mutation effect for different coding regions, we seperate the coding regions to different categories (synonymous, nonsynonymous, damaging) for DNM overenrichment analysis, with aim to distinguish different mutation effects.

The title on the plot show the DNM data used, which include data name (first author/organization), publication year/journal and followed by the specific diseases. the x-axis show different genomic regions and the y-axis show the over-enrichment of DNMs (fold change) in each region compared with control region (regions not annotated as functional from any known resources). Each red circle represent one potantial genomic region, with region name and overenrichment test p value (binomial) labeled.

(1), Overenrichmen of synonymous DNMs within potential functional regions:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/func_reg.syn_nonsplicing.dnm.enrich.pdf

Explaination: missing data because of small datasets

(2), Overenrichmen of nonsynonymous DNMs predicted as nondamaging by Polyphen and CADD within potential functional regions:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/func_reg.nondam_nsy.dnm.enrich.pdf
Explaination: a, overall we found over enrichment DNMs in RBP binding sites (CLIPdb) across all studies, and this is especially true for neuron function related genes; b, unfortunately there's no DNM overenrichment for ribsnitch or RBPvar2; c, we observed low DNM overenrichment on normal samples comapred with disease samples. 

(3), Overenrichmen of nondamaging nonsynonymous DNMs (same as above) and synonymous DNMs together within potential functional regions:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/func_reg.syn_nondam_nsy.dnm.enrich.pdf
Explaination: similar to nonsynonymous DNMs only analysis considering synonymous mutations only take up small part.

(4), comparison of DNM overenrichment on damaging nonsynonymous mutations with other regions:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/func_reg.damagNS_included.syn_nsy.dnm.enrich.pdf
Explaination: 
damaging nonsynonymous mutations was not show high impact on DNM overenrichment.

4, Conclusions
We found overenrichment of DNMs on RBP binding regions, and among neuropsychaitric related genes.

5, supplementary data
all detailed analysis data was put in table files that can be viwed or downloaded:

(1), Overenrichmen of synonymous DNMs within potential functional regions:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/func_reg.syn_nonsplicing.dnm.enrich

(2), Overenrichmen of nonsynonymous DNMs predicted as nondamaging by Polyphen and CADD within potential functional regions:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/func_reg.nondam_nsy.dnm.enrich

(3), Overenrichmen of nondamaging nonsynonymous DNMs (same as above) and synonymous DNMs together within potential functional regions:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/func_reg.syn_nondam_nsy.dnm.enrich

(4), comparison of DNM overenrichment on damaging nonsynonymous mutations with other regions:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/func_reg.damagNS_included.syn_nsy.dnm.enrich

