## UCSC Cell Browser Activity

**Name:** Duhaylongsod, Jil M. 

**Assigned Gene:** F9

**Associated Disease:** Hemophilia B

**Date:** September 24, 2026

## Part B. Organ/Tissue Choice and Dataset Information

| **Item** | **Information** |
|---|---|
| **Dataset** | Human Liver Cell Atlas – All Cells |
| **Organ/Tissue** | Human liver |
| **Cell Types** | Hepatocytes, cholangiocytes, endothelial cells, lymphocytes, mesenchymal cells, and myeloid cells |
| **Gene** | F9 |
| **Associated Disease** | Hemophilia B |
| **Reason for Selection** | The liver is relevant to F9 because F9 is associated with blood coagulation. Studying liver cells allows us to observe the expression of F9 in different liver cell types. |
| **Dataset URL** | https://cells.ucsc.edu/?ds=human-liver-cell-atlas+all-cells |

<img width="954" height="451" alt="image" src="https://github.com/user-attachments/assets/abb9179b-c89e-47e3-ad99-3a64c53ad6c9" />

**Figure 1.** Human Liver Cell Atlas showing the different cell types and clusters in the All Cells dataset.

## Part C - Understanding the Cell Map

| **Item** | **Observation** |
|---|---|
| **Visualization** | UMAP |
| **What does one dot represent?** | One individual cell measured in the single-cell dataset. |
| **What do the clusters represent?** | Groups of cells with similar gene-expression profiles, representing different cell types or cell populations in the liver. |
| **Cell-type/cluster labels** | Pericentral Hepatocyte, B Cell, MAIT T Cell |

## Part D - Assigned Gene Expression

| Part | Answer |
|------|--------|
| **a. Assigned gene symbol** | F9 |
| **b. Dataset used** | Human Liver Cell Atlas – All Cells |
| **c. Is expression widespread, restricted, or low/undetected?** | Restricted – mainly in liver cells, not widespread |
| **d. Which cluster(s) appear to contain cells with stronger expression?** | Hepatocyte clusters (Pericentral Hepatocyte, SERPINE1+ Hepatocyte) |
| **e. Which cluster(s) appear to contain little or no detectable expression?** | Immune clusters (B Cell, T Cell, NK Cell, Monocytes) |

<img width="688" height="493" alt="image" src="https://github.com/user-attachments/assets/b62334a3-c9fa-4b85-a38b-22c6ad62cd58" />

**Figure 2.** Cell‑type annotation map of the Human Liver Cell Atlas dataset showing the major annotated cell clusters, including Pericentral Hepatocyte, SERPINE1+ Hepatocyte, Periportal LSEC, CD8 T Cell, MAIT T Cell, and other liver‑related cell populations. 

## Part E - Cell Types and Clusters

| Requirements | Observation |
|---------------|-------------|
| **a. Cell type/cluster with the strongest visible expression** | Hepatocyte clusters (Pericentral Hepatocyte, SERPINE1+ Hepatocyte) show the highest F9 expression. |
| **b. Another cell type/cluster with detectable expression** | UGT+ Hepatocyte cluster also shows some detectable expression. |
| **c. Cell type/cluster with relatively low or undetected expression** | Immune clusters such as B Cell, T Cell, NK Cell, and Monocytes show very low or no expression. |
| **d. Is the expression pattern broad or cell-type restricted?** | The expression pattern is cell-type restricted, mainly in hepatocytes. |
| **e. Biological explanation** | F9 encodes Factor IX, a blood-clotting protein produced in the liver. It makes sense that hepatocytes express F9 strongly because they synthesize plasma proteins, while immune cells do not need this gene for their functions. |

<img width="956" height="442" alt="image" src="https://github.com/user-attachments/assets/def13a54-9110-4492-a9e0-427250a1bba6" />

**Figure 3.** Gene expression map of the Human Liver Cell Atlas dataset showing annotated cell clusters. The F9 gene is mainly expressed in hepatocyte clusters such as Pericentral Hepatocyte and SERPINE1+ Hepatocyte, while immune clusters like B Cells and T Cells show little or no expression. 

## Part F – Expression Plot

| Question | Answer |
|-----------|---------|
| **a. Which cells/cluster did you select?** | Pericentral Hepatocytes. |
| **b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?** | The Pericentral Hepatocytes show similar expression overall compared with the nearby hepatocyte groups based on the displayed plot. |
| **c. What does the expression plot add that was not obvious from the UMAP/t‑SNE map?** | The expression plot shows how strongly the gene is expressed within the selected cell group, while the UMAP mainly shows how the cells are grouped and related to each other. |

<img width="439" height="394" alt="image" src="https://github.com/user-attachments/assets/d13a57f3-32fb-4900-8869-d8b52e564425" />

**Figure 4.** Dot plot showing F9 gene expression across annotated liver cell types. The Pericentral Hepatocyte cluster displays the highest average expression and proportion of expressing cells, followed by moderate expression in Periportal and Ribosomal+ Hepatocytes.

## Part G - Marker Genes

| **Item** | **Answer** |
|---|---|
| **a. Cluster/cell type examined** | Pericentral Hepatocyte |
| **b. Marker gene 1** | CYP3A4 |
| **c. Marker gene 2** | CYP2E1 |
| **d. Marker gene 3** | ADH4 |
| **e. Does the assigned gene behave like a cell-type marker?** | No. F9 is the assigned disease-associated gene, but it is not listed among the marker genes shown for the Pericentral Hepatocyte cluster. Therefore, F9 does not appear to uniquely characterize the Pericentral Hepatocyte cell type in this dataset. |

<img width="860" height="383" alt="image" src="https://github.com/user-attachments/assets/b6c6c0a4-6930-4412-8b33-856a248b91aa" />

**Figure 5.** Table showing marker genes for the Pericentral Hepatocyte cluster. Genes such as CYP3A4, CYP2E1, ADH4, GLUL, and BCHE have positive marker scores, indicating strong association with this hepatocyte subtype. 

## Part H - Disease Gene vs. Marker Gene

| **Item** | **Answer** |
|---|---|
| **a. Assigned disease gene** | F9 |
| **b. Marker gene** | CYP3A4 |
| **c. Which gene shows a more cell-type-restricted expression pattern?** | CYP3A4 |
| **d. Which gene appears more broadly expressed?** | F9 |
| **e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?** | A cell-type marker gene such as CYP3A4 shows a more characteristic expression pattern in specific cell populations, particularly hepatocyte-related cells such as Pericentral Hepatocytes. A disease-associated gene such as F9 can be biologically relevant without being specific to one cell type. Therefore, disease-associated genes and cell-type marker genes can have different expression patterns and purposes. |

## Part I  - Connection to Genome Browser and ClinVar

**1. On which chromosome is F9 located?**
F9 is located on the X chromosome.

**2. What disease-associated variant did you examine previously?**
F9 c.52T>C (p.Cys18Arg) — a single-nucleotide variant in the F9 gene that causes a Cys18Arg (C18R) protein change.

3. In the current Cell Browser dataset, which cell type(s) express F9?
F9 was detected in the Pericentral Hepatocyte cell type.

4. Does the observed cell expression make biological sense based on what you know about F9?
Yes. F9 is associated with Hemophilia B, and its expression in liver cells makes sense because the liver is involved in producing blood-clotting factors. The expression of F9 in Pericentral Hepatocytes is therefore consistent with its biological function.

5. Can this single Cell Browser dataset prove that F9 causes Hemophilia B? Why or why not?
No. The Cell Browser only shows where F9 is expressed in the selected dataset. It cannot prove that F9 causes Hemophilia B because other genetic, clinical, and functional evidence is needed.

## Part J -  Reflection

**1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?**
The UCSC Cell Browser showed me where F9 is expressed at the single-cell level and which cell types express it. The Genome Browser mainly showed the gene’s location and structure in the genome.

**2. Why can the same gene have different expression levels among different cell types?**
Different cell types have different functions, so they do not need to use the same genes at the same level. For example, F9 showed expression in liver cells because the liver is involved in producing blood-clotting factors.

**3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?**
Zero or low expression does not always mean that the gene is completely inactive. It can be affected by the type of tissue, the number of cells analyzed, and the method used to collect the data.

**4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?**
Combining these types of information gives a better understanding of how a gene may be related to a disease. For F9, I could connect its location on the X chromosome, the c.52T>C (p.Cys18Arg) variant, and its expression in liver cells.

**5. What was the most interesting observation you made about your assigned gene?**
The most interesting observation was that F9 was detected in the Pericentral Hepatocyte cell type. This made sense because F9 is involved in blood clotting and is produced mainly by liver cells.

## References and Links

UCSC Cell browser. (n.d.). https://cells.ucsc.edu/?ds=human-liver-cell-atlas

UCSC Cell browser. (n.d.-a). https://cells.ucsc.edu/?ds=human-liver-cell-atlas%2Ball-cells 

U.S. National Library of Medicine. (n.d.-b). Vcv000010568.2 - clinvar - NCBI. National Center for Biotechnology Information. https://www.ncbi.nlm.nih.gov/clinvar/variation/10568/
