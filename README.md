# Pathway or gene set enrichment analysis


## Introduction
Pathway and Gene Set Enrichment Analysis (GSEA) is a powerful computational technique widely used in the field of genomics and bioinformatics. It helps researchers uncover the biological significance of large-scale gene expression or omics data by identifying which biological pathways or sets of genes are statistically overrepresented in a given dataset.

This GitHub repository houses a collection of tools, scripts, and resources that enable you to perform pathway/GSEA analysis efficiently. Whether you are a biologist, bioinformatician, or data scientist, this repository provides the resources you need to conduct meaningful pathway/GSEA analysis on your own data.

## What is Pathway/Gene Set Enrichment Analysis?
Pathway/Gene Set Enrichment Analysis is a statistical method used to interpret large-scale genomics or omics data by assessing whether predefined sets of genes (gene sets or pathways) are significantly enriched among differentially expressed or relevant genes. It helps researchers gain insights into the biological processes, functions, and pathways that are perturbed in their experiments. 

## Why Use Pathway/Gene Set Enrichment Analysis?
Pathway/GSEA analysis offers several advantages:

**Biological Interpretation**: It provides biological context to high-throughput data by identifying the underlying biological processes and pathways affected.

**Reduced Multiple Testing**: Instead of testing each gene individually, it tests gene sets, reducing the multiple testing burden and increasing statistical power.

**Biologically Meaningful Results**: It enables researchers to focus on biologically relevant results, making it easier to generate hypotheses and prioritize further investigations.


## Resources to understand Pathway analysis 

1. Ten Years of Pathway Analysis: Current Approaches and Outstanding Challenges

https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002375​

2. Nine quick tips for pathway enrichment analysis

​https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010348​

3. Multiple sources of bias confound functional enrichment analysis of global-omics data
 http://ncbi.nlm.nih.gov/pmc/articles/PMC4561415/​


4. Identifying significantly impacted pathways: a comprehensive review and assessment

https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1790-4​

5. Toward a gold standard for benchmarking gene set enrichment analysis
https://academic.oup.com/bib/article/22/1/545/5722384​

6. Recurrent functional misinterpretation of RNA-seq data caused by sample-specific gene length bias

​https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3000481​

7. How to choose background genes
https://twitter.com/mdziemann/status/1626407797939384320​

8. Blog post on GSEA
https://crazyhottommy.blogspot.com/2016/08/gene-set-enrichment-analysis-gsea.html 

## Standard tools to analyze differentially expressed genes
1. An R package: Enrichr https://maayanlab.cloud/Enrichr/

Documentation page: https://cran.r-project.org/web/packages/enrichR/vignettes/enrichR.html

2.  clusterprofiler
https://bioconductor.org/packages/release/bioc/html/clusterProfiler.html

Some tutorials on clusterprofiler with example: 

https://learn.gencore.bio.nyu.edu/rna-seq-analysis/gene-set-enrichment-analysis/

https://rpubs.com/jrgonzalezISGlobal/enrichment

3. LIGER
   Tutorial: https://github.com/JEFworks/liger

4. GSEA in Python (GSEAPY: Gene Set Enrichment Analysis in Python)
   https://gseapy.readthedocs.io/en/latest/introduction.html?ck_subscriber_id=2225048918&utm_source=convertkit&utm_medium=email&utm_campaign=Resending%3A+15+links+for+gene+set+enrichment+analysis%21%20-%2011766833#gseapy-prerank-module-output

   Youtube demonstration: https://www.youtube.com/watch?v=yOQcrUMCALw (WIth Jupyter notebook : https://github.com/mousepixels/sanbomics_scripts/blob/main/GSEA_in_python.ipynb)



5. msigdbr
   
https://cran.r-project.org/web/packages/msigdbr/vignettes/msigdbr-intro.html?ck_subscriber_id=2225048918&utm_source=convertkit&utm_medium=email&utm_campaign=Resending%3A+15+links+for+gene+set+enrichment+analysis%21%20-%2011766833   


## Keypoints to remember while running a Pathway analysis.

Running a pathway analysis can be a powerful way to gain insights into the biological significance of your genomics or omics data. Here are some key points to remember when conducting pathway analysis:

1. **Data Preprocessing is Crucial**: Ensure that your data is properly preprocessed and quality-controlled before performing pathway analysis. This includes normalizing, filtering, and handling missing data as necessary.

2. **Choose the Right Pathway Database**: Select an appropriate pathway database or gene set collection that matches the species and biological context of your data. Common databases include KEGG, Reactome, and Gene Ontology.

3. **Statistical Methods**: Understand the different statistical methods available for pathway analysis, such as over-representation analysis (ORA) and gene set enrichment analysis (GSEA). Choose the method that best suits your data and research question.

4. **Multiple Testing Correction**: Apply multiple testing correction methods (e.g., Bonferroni, Benjamini-Hochberg) to control for false positives when assessing pathway significance.

5. **Threshold Selection**: Decide on appropriate significance thresholds (e.g., p-value or false discovery rate) for identifying enriched pathways. The choice of threshold can impact the number of pathways considered significant.

6. **Biological Interpretation**: Interpretation is key. Once you have a list of enriched pathways, delve into their biological significance. Consider the direction of gene regulation (upregulated or downregulated) within each pathway.

7. **Visualize Results**: Use visualization tools like pathway diagrams, heatmaps, or enrichment plots to better understand the relationship between your data and enriched pathways.

8. **Adjust for Multiple Comparisons**: If you perform multiple pathway analyses (e.g., for different experimental conditions), correct for multiple comparisons at the analysis level to maintain statistical rigor.

9. **Pathway Crosstalk**: Explore crosstalk between pathways. Some genes may be involved in multiple pathways, and understanding these interactions can provide deeper insights.

10. **Biological Validation**: Experimentally validate the findings from your pathway analysis using techniques such as qPCR, Western blotting, or functional assays to confirm the biological relevance of identified pathways.

11. **Consider Sample Size**: The statistical power of your analysis depends on sample size. Larger sample sizes can provide more reliable results.

12. **Reproducibility**: Document your analysis steps, including software packages and parameter settings used. This ensures the analysis can be reproduced and validated by others.

13. **Biological Context**: Keep the biological context of your study in mind. Interpret the pathway results in light of your specific research question and the biological system under investigation.

14. **Stay Updated**: Pathway databases and analysis methods are continually evolving. Periodically update your analysis tools and databases to ensure you're using the latest information.

15. **Consult with Experts**: If you're unsure about any aspect of pathway analysis or need help interpreting results, don't hesitate to consult with experts in the field of genomics or bioinformatics.

Remember that pathway analysis is a valuable tool for generating hypotheses and understanding the biological mechanisms underlying your data. Properly executed, it can provide meaningful insights that advance your research.

   



   


