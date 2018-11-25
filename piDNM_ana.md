Analysis of overenrichment of DNMs in post-transcriptional functional sites

Data:
1, 25,035 SNV DNMs from about 50 neuropsychiatric WES studies (including ASD, EE, SCZ et al);
2, 9,657,613 and 8,453,935 RBPbinding sites collected from CLIPdb and Starbase2 databases respecteively; 
3, 8,005,040 predicted mutations on refGenes exon regions by RNAsnp software tool (Mode3, p value <=0.05);
4, predicted possible splicing change mutations on transcriptome prediceted by sipdex software tool 
5, genetic regions and mutation effect for each mutation were annotated using the annovar software tool.  
6, genome-wide DNM mutation rate data were obtained from Jedidiah Carlson's work
7, 2,555 neuron-psychiatric genes were obtain from AutismKB
FMRP targets, G2Cdb and SFARI etc. datasets
8, genes of lowest 10% average expression level from the brainspan database were taken as human brain low expression genes

Methods:
1, DNM distribution on different exonic regions according to mutation effect or post-transcriptional modifications were compared using WES and WGS datasets for each study sepretely. 
2, To estimate DNM overenrichment on possible post-transcriptional functional sites (including RBPbiding and Ribsnitch sites) specifically, LOF mutations (spilicing change, stop-gain/loss) and damaging nonsynonymous mutations (polyphen prediction as damaging) within these sites were excluded;
3, For each WES dataset, DNM overenrichent in each regions were compared against synonymous mutation regions, and the expected occrences rate were calculated from background mutation rate, then Binomial test were used for enrichment significnace and ratio calculation, 95% confidence interval for enrichment ratio also estimated;
4, for WGS dataset, we compare DNM rate in each genomic region in Case vs Control samples, and to DNM rate in synonymous mutation regions in Case vs Control were used as background, similarly binomial test were used for enrichment significnace and ratio calculation, 95% confidence interval for enrichment ratio also estimated;
5, Known neuron-psychiatric gene region and genes with NULL or low expression level in brain were used as positive and negative control 

Results:
1, for WES dataset:
a, fold change of DNM rate in different genomic regions compared to synonymous mutation regions in different studies, this figure show for all genes:

https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/tt.WES_all.dnm.enrich.pdf

Figure legends: each figure for one study, and each point represent one region, the y-axis is to show overenrichemnt using two-sided binomial test, the number on the figure represent the DNM counts observed in the regions, and * to indicate binomia test p value < 0.05, ** for < 0.001 and *** for <0.0001, the vertical line to show 95% confidence interval for overenrichment ratio based on binomial test results. 

b, fold change of DNM rate in different genomic regions compared to synonymous mutation regions in different studies, this figure show for neuron-spychaitric related genes:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/tt.WES_neurongenes.dnm.enrich.pdf

c, fold change of DNM rate in different genomic regions compared to synonymous mutation regions in different studies, this figure show for lowly expressed genes in human brain:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/tt.WES_brain_lowexprgenes.dnm.enrich.pdf

2, for WGS dataset:
a, fold change of DNM rate in different genomic regions in Case vs COntrol, compared to synonymous mutation regions, this figure show for neuron-spychaitric related genes:
https://github.com/lalzs1982/ASD_noncoding_DNM/blob/master/Presentation/tt.WGS_neurongenes.dnm.enrich.pdf


Summary:
1, we can see obvious DNM overenrichment on LOF and damaging mutation regions ,as expected, but minor enrichment for post-trnascription functional sites in most WES datasets
2, for neuron-psychiatric genes, we observe significant DNM overenrichment on LOF and damaging mutation regions as well as post-trnascription functional sites, which indicate potential effect of post-trnascription functional sites mutation on the neuron-psychiatric disorders we analyzed, but the effect is smaller compared to LOF/damaging mutations. 
3, for low brain expressed genes, we observe minor nonsignificant DNM overenrichment on the different genomic regions, which indicate small or none contribution of these genes to neuron-psychiatric disorders occurences
4, In general we cannot repeat the result in WGS datasets

