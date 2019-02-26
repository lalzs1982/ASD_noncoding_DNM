Analysis of DNM overenrichment on miRNA and binding sites

AIM:

	To identify miRNA or the binding sites with more than expected DNMs in ASD samples than Control samples, 
	which indicate the de novo mutation affect miRNA regulatory functions and may cause the ASD

DATA:

1, DNMs: DNMs produced from WGS for several different studies collected, which include DNMs from ASD subjects 
and also normal sibling or other unrelated normal subjects 

Pool DNMs:

	302,937 DNMs for ASD

	324,208 for Normal(Siblings or other health individuals in different studies)

Simons 1902 ASD families data:

	128,641 DNMs for ASD

	126,129 DNMs for Normal 
 
2, pre-miRNA: 

	1877 pre-miRNA annotations(length about 50-100 bp) from miRBase

3, promoter for miRNAs:

	1157 pre-miRNA TSS collected from FANTOM project, and 1kbp flanking the TSS was used as candidate 
	pre-miRNA promoters in this analysis

4, miRNA binding sites:

	538,548 miRNA bidning sites (about 10 bp length) for 2,283 miRNAs that are used here. They are constructed as bellow: 
	predicted binding sites on genes by targetscan(all), and the gene-miRNA relationship was experimentally verified based 
	on mirTarbase,  and at same time, only for target genes expressed in prenatal human brain(14,284 genes with FPKM>1 in 
	any brain region, brainspan database)

5, miRNAs dis-regulated in ASD brain:

146 miRNAs significantly differentially expression between ASD/Normal human brain (p value<0.05) obtained from Geschwind_NN_2016

6, ASD related genes:

	429 ASD_coexpression_networks_Willsey2013
    104 ASD_genes_Betancu_2011BR
    195 ASD_genes_Pinto_AJHG2014
    172 AutismKB
   	1845 CHD8_targets_Cotney2015_Sugathan2014
    843 FMRP_targets
   	1557 G2Cdb
     83 SFARI_I_II
     61 TADA0.1
    109 TADA0.2

METHODS:

	DNM overenrichment with each regions such as pre-miRNA body, promoters, miRNA binding sites for one specific miRNA, 
	or for binding sites within specific gene set was tested. 

	Simply Chi-square test used to estimate significance of DNM overenrichment within analyzed region, and using total 
	DNMs in ASD or Control group as background.  

RESULTS:

1, 0 pre-miRNA with >=2 DNMs

2, miRNA promoters: 

       2 miRNAs: miR-6723(7 vs 0) and miR-4800(5 vs 0) with significantly more ASD DNMs than Normal, 
	and 1 miRNAs: miR-3616 (1 vs 7) with significantly more Normal DNMs than ASD.
	and no DNM enrichment for promoters of miRNA differentially expressed in ASD brain 
3,  miRNA binding sites:
	
	binding sites for 2 miRNAs (miR-5011-5p, miR-190a-3p) with significantly enriched ASD DNMs, and another 7 miRNAs 
	with slightly enriched ASD DNMs (miR-6785-5p, miR-6825-5p, miR-567, miR-149-3p,miR-6883-5p,miR-8485 and miR-4728-5p, 
	all for 4 vs 0 DNMs in ASD and Normal), but NONE miRNA with significantly more Normal DNMs compared to ASD.

4,	DNM overenrichment analysis on miRNA binding sites for neuropsychiatric 	genes:
	
	Slight overenrichment on ASD_coexpression_networks_Willsey2013 (15 vs 7) geneset observed; unexpectedly, 
	normal DNMs overenrichment on SFARI_I_II geneset (1 vs 8 ) and ASD_genes_Betancu_2011BR (2 vs 8) genesets;

5,	Above analysis is based on DNMs pool, while analyze using Simons dataset:
	
	miR-4800 promoter, binding sites for 2 miRNAs (miR-5011-5p, miR-190a-3p), could still show nonsignificant ASD DNM overenrichment; 
	
	miRNA binding sites for FMRP_targets genes was found to show nonsignificant ASD DNM overenrichment (12 vs 7);
	
	Overall overenrichment of DNMs within miRNA binding sites disapeared
	
