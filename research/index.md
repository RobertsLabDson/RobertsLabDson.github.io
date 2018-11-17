---
title: Research in the Roberts Lab
layout: default
group: research
---

## Research in the Roberts lab is focused on AML and the Gene Regulatory Network behind the disease.

### Why do we do what we do?

Acute Myeloid Leukemia (AML) is the most common form of acute leukemia in adults, and is also seen in children (1). In the United States, AML is the leading cause of death from leukemia, with over 20,000 new diagnoses and 10,000 deaths annually (2). Like most cancers of a particular tissue type, there are multiple subtypes of AML defined by cytological, genetic and clinical criteria. All AML subtypes have a limited number of recurrent oncogenic driver mutations, but no one driver mutation is shared by all AMLs, in fact the most common recurrent gene mutation, NPM1, is observed in only a third of AML patients (3). The focus of our lab is not on these well-defined oncogenic driver mutations, but rather on the transcriptomes they produce. If an AML cell harbors 10 oncogenic gene mutations, this means that the remaining ~20,000 genes are normal. So why is a leukemia cell so different from the normal hematopoietic progenitor from which it was derived? The answer is in the types, forms, amounts, and locations of proteins and regulatory RNAs produced, directed by the transcriptome. Indeed, AML subtypes can be defined by gene expression signatures of normal genes that are differentially expressed in the cancer cells (4). We seek to understand which genes most impact the complex cancer phenotype and are predictive of clinical outcome. By identifying these key genes, we hope to define novel therapeutic targets for directed drug intervention.

### Our Model System: The Phorbol Ester Response Of AML Cell Lines

Several AML cell lines have been established, which show the capacity to undergo myeloid differentiation in response to chemical inducers that activate signaling pathways leading to changes in the transcriptome (5). Phorbol esters irreversibly activate PKC in AML cell lines like HL-60, enabling signaling systems that genetically reprogram the cells to undergo cell cycle arrest, macrophage-like differentiation, and apoptosis (6).  We have determined changes in gene expression at the transcriptional level in HL-60 cells treated with PMA for various times (0.5, 1, 3, 6, 12, 24 hours) by DNA microarray analysis (7). These studies have identified ~1,250 genes that are significantly (>2-fold) up- or down-regulated at two or more time points. The ability to provoke cell cycle arrest, differentiation and apoptosis by altering the transcriptome, suggests that gene expression reprogramming can override oncogenic mutations in clinically relevant ways. We hope to understand the key genes and mechanisms involved in the reversion of acute myeloid leukemia cells into cells that have regained the capacities for proliferative control, myeloid differentiation, and apoptosis.

To this end, we are exploring the function of specific PMA-responsive genes in HL-60 cells by individually over-expressing or knocking down the expression of genes hypothesized to contribute to the phenotypic changes of interest through transfection experiments. Our focus in understanding PMA-induced reprogramming is on those genes encoding transcription factors (TFs), with the rationale that the differential expression of a few TF genes could be driving the expression changes of many/most of the genes of the PMA response. Perhaps, changing the expression of key TF genes results in the up- or down-regulation of genes that affect cell cycle arrest, and/or macrophage differentiation, and/or apoptosis. The transfection experiments in progress involve confirmation of over-expression or knockdown by RT-qPCR (for RNA level changes) and Western blotting (for protein level changes), followed by evaluation of transcriptome and phenotypic changes.

QUESTIONS:
1. How does the PMA-altered transcriptome of HL-60 cells override the oncogenic mutations and drive a program of anti-proliferation, differentiation and apoptosis?
2. Can turning the expression of a single gene on or off change the leukemic phenotype to a more “normal” cell phenotype?


### Predicting/Validating Target Gene Expression In TF Gene Transfection Experiments

Approximately 100 of the 1,250 genes showing altered expression in response to PMA encode transcription factors. The expression pattern changes include transient or sustained up-regulation or down-regulation that is initiated rapidly (<1 hour), with a delay (3-6 hours) or late (>6 hours) in the PMA response. Our working hypothesis is that existing, inactive transcription factors are activated rapidly by PMA treatment causing the transcriptional activation of genes (immediate early responders), some of which encode TFs (ex. EGR1) that go one to transcriptionally control a second wave of expression (delayed early responders), that again include TF genes (ex. MAFB), which regulate a third wave (late), and so on. We propose that the activation of key immediate early TF genes may set into motion many/most of the observed expression changes, suggesting that the up- or down-regulation of one or a few TF genes could significantly alter the leukemia cell transcriptome and mediate complete or partial growth arrest, myeloid differentiation and/or apoptosis.

To test this hypothesis, we apply both computational and experimental approaches. A database containing the ~1,200 base pairs of sequence surrounding the transcription starts sites of the 1,250 changing genes has been assembled (-1,000 bp to +200 bp), along with known binding site position weight matrices (PWMs) for a large number of TFs. Bioinformatically, we can score potential binding sites for each TF within the proximal promoter regions. In this way, we can predict possible target genes for the TFs in the database. For example, we can query the promoter sequences for EGR1 bindings sites with determined confidence levels and the identity of genes with specific numbers of sites in their promoters and their relative positions. Experimentally, we are transfecting overexpression constructs or shRNAs for TF genes of interest and evaluating their impact on predicted target gene expressions by qPCR. Additionally, overexpression and knockdown samples are being sequenced to provide a global view of transcriptome changes, independent of candidate gene identification. In this way, we seek to discover how turning on or off specific TF genes alters the HL-60 transcriptome. In concert with measuring gene expression changes post-transfection, we are evaluating changes in cell phenotype related to proliferation, myeloid differentiation, and apoptosis by flow cytometry analyses.

QUESTIONS:
1. How does the up- or down-regulation of specific TF genes affect the HL-60 transcriptome.
2. What are the TF target genes? Can we predict targets and do our predictions match experimental results? Can we refine our predictive models?
3. Can changing the expression of individual TF genes change the leukemia phenotype? Can we identify a TF gene(s) that induce a more normal (less oncogenic) cell state?


### Clinical Correlations: Mining Aml Patient RNA-seq Data

The AML database of the Human Cancer Genome Atlas (TCGA - LAML), consists of a cohort of 200 patients and includes RNAseq gene expression data as well as mutational and clinical data for each patient sample (8). We are “mining” these data to explore correlations between clinically relevant gene expression signatures and the PMA response of HL-60 cells. For example, a TF gene showing rapid up-regulation in response to PMA, like EGR1, might be changing the HL-60 transcriptome in ways that facilitate cell cycle arrest, differentiation and/or apoptosis. We predict that genes playing such roles might show expression level differences correlative of survival outcomes. In fact, AML patient samples with the 20% lowest EGR1 expression when compared to the 20% of highest expressing samples show a statistically significant difference in survival by Kaplan-Meier analysis, with the highest expressing samples identifying patients with decelerated mortality rates and higher overall survival (9).
QUESTIONS:
1. Does the expression of PMA responsive genes in HL-60 cells correlate with AML subtypes and/or clinical outcomes?
2. Does the comparison of the AML cohort expression data with the HL-60 PMA response data identify novel therapeutic targets?

REFERENCES

(1) Dohner, H. et al. (2015). *Acute Myeloid Leukemia*. NEJM 373(12): 1136-52.
(2) Noone AM, et al. *SEER Cancer Statistics Review*, 1975-2015, National Cancer Institute. Bethesda, MD, https://seer.cancer.gov/csr/1975_2015/, based on November 2017 SEER data submission, posted to the SEER web site, April 2018.
(3) Yohe, S. (2015). *Molecular Genetic Markers in Acute Myeloid Leukemia*, J. Clin. Med 4: 460-478.
(4) Bullinger, L., et al. (2004). *Use of Gene-Expression Profiling to Identify Prognostic Subclasses in Adult Acute Myeloid Leukemia*. NEJM 350(16): 1605-16.
(5) Ramirez, RN, et al. (2017). *Dynamic gene regulatory networks of human myeloid differentiation*. Cell Syst. 4(4): 416-29.
(6) Gobbi, G. et al. (2009). *Phorbol ester–induced PKC down-modulation sensitizes AML cells to TRAIL-induced apoptosis and cell differentiation*.  Blood 113(13): 3080-87.
(7) Roberts, M., et al. (manuscript in preparation) *Genetic re-programming of the acute myeloid leukemia cell line HL-60 by phorbol esters: regulation of cell proliferation, differentiation, and programmed cell death*.
(8) Cancer Genome Atlas Research Network, Ley, TJ, et al. (2013). *Genomic and epigenomic landscapes of adult de novo acute myeloid leukemia*. NEJM 369(1): 98-119.
(9) Anaya, J. (2016). *OncoLnc: linking TCGA survival data to mRNAs, miRNAs, and lncRNAs*. PeerJ Comput. Sci. 2: e67; DOI 10.7717/peerj-cs.67 
