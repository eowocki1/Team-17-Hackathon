# Team 17 Hackathon

# Technical Report
## Task B
### Disease: Breast Cancer

Breast cancer is a complex disease characterized by the uncontrolled growth of cells in the breast tissue. It's the most common cancer in women worldwide and can also occur in men, though much less frequently. Symptoms include a new lump or mass in the breast or armpit, thickening or swelling of part of the breast, skin irritation or dimpling, breast or nipple pain, nipple retraction (turning inward), redness, scaliness, or thickening of the nipple or breast skin, nipple discharge other than breast milk. These symptoms can also be caused by benign conditions, and not all breast cancers cause noticeable symptoms in early stages. While breast cancer originates in breast tissue, it can affect multiple organ systems including the lymphatic system, bones, lungs, liver, brain, skin, endocrine system, and immune system if it metastasizes.

A clinical breast examination is used to diagnose breast cancer through mammography, ultrasound, Magnetic Resonance Imaging (MRI), and potentially a biopsy.Treatment for breast cancer is usually multimodal and may include surgery, radiation therapy, or systemic therapy. Treatment is considered successful when there is complete remission (no detectable cancer), partial remission (reduction in tumor size), disease-free survival, overall survival, improved quality of life, and minimal side effects and complications. If treatment fails, alternative chemotherapy regimens, clinical trials of new drugs or combinations, targeted therapies based on genetic profiling of the tumor, and palliative care to manage symptoms may be utilized.

## Task C
### Genes
Several genes have been identified as being associated with breast cancer. The most well-known and studied include:

a) BRCA1 and BRCA2: These tumor suppressor genes are the most common hereditary breast cancer genes. Expressed in many tissues, particularly during embryonic development and in adult breast and ovarian tissues. They play crucial roles in DNA repair and cell cycle regulation. In breast epithelial tissue, loss of function mutations lead to decreased expression or non-functional proteins. This impairs DNA repair, causing genomic instability, which contributes to cancer development.

b) TP53: A tumor suppressor gene that regulates cell division and prevents tumor formation. Expressed in all tissues, with increased expression during cellular stress or DNA damage. Often mutated in breast epithelial cells, leading to loss of function or altered function. The mutated p53 fails to regulate the cell cycle and apoptosis, allowing damaged cells to survive and proliferate.

c) PIK3CA: Often mutated in breast cancer, affecting cell growth and survival. Widely expressed in various tissues, playing a role in cell signaling and growth. Frequently mutated in breast cancer cells, leading to increased activity. Activating mutations result in increased cell survival and proliferation through the PI3K/AKT pathway.

d) PTEN: Another tumor suppressor gene frequently mutated in breast cancer. Expressed in multiple tissues, regulating cell cycle and growth. Expressed in many epithelial tissues during development, playing a role in cell growth and differentiation. Frequently downregulated or lost in breast cancer cells, leading to uncontrolled activation of the PI3K/AKT pathway. This promotes cell survival and proliferation, contributing to tumor growth.

e) HER2 (ERBB2): Amplification or overexpression of this gene occurs in about 20-30% of breast cancers. Expressed in many epithelial tissues during development, playing a role in cell growth and differentiation. Amplified or overexpressed in about 20-30% of breast cancers. Overexpression of HER2 leads to increased cell proliferation and survival through multiple signaling pathways.

f) ESR1 and PGR: Genes encoding estrogen and progesterone receptors, respectively.Primarily expressed in reproductive tissues, including breast, ovary, and uterus. Their expression increases during puberty and pregnancy. Altered expression of these genes, either overexpressed or underexpressed, defines different breast cancer subtypes. The misexpression affects hormone-responsive gene regulation, influencing cell growth and survival.

g) CCND1: Encodes Cyclin D1, often amplified in breast cancer. Expressed in various tissues during cell cycle progression. Often amplified and overexpressed in breast cancer cells. This promotes cell cycle progression and uncontrolled cell division, contributing to tumor growth. 

h) MYC: A proto-oncogene frequently amplified in breast cancer. Widely expressed during embryonic development and in adult tissues, regulating cell proliferation and differentiation.  Frequently amplified and overexpressed in breast cancer cells. MYC amplification leads to increased expression of genes involved in cell proliferation and metabolism, further promoting cancer development.

i) HOX genes: Several HOX genes, including HOXA5, HOXA9, and HOXD10, have been implicated in breast cancer development. Expressed during embryonic development in specific spatial and temporal patterns, crucial for body patterning and organ development. In adult tissues, they maintain tissue-specific functions. Various HOX genes, including HOXD10, are misexpressed in breast cancer, often downregulated in breast cancer tissues. This misexpression can lead to altered cell differentiation, increased proliferation, and enhanced invasive capabilities.

### Three hypotheses explaining how the misexpression of these genes leads to breast cancer:

#### Hypothesis 1: Genomic Instability and DNA Repair Deficiency
The misexpression of BRCA1, BRCA2, and TP53 leads to impaired DNA repair mechanisms and genomic instability. This results in an accumulation of genetic mutations, including those in other cancer-related genes. The inability to correct these mutations allows cells to acquire additional cancer-promoting characteristics, such as uncontrolled proliferation and resistance to apoptosis, ultimately leading to breast cancer development.

#### Hypothesis 2: Dysregulation of Cell Signaling Pathways
Misexpression of genes like PIK3CA, PTEN, and HER2 leads to hyperactivation of key signaling pathways, particularly the PI3K/AKT and MAPK pathways. This dysregulation results in increased cell survival, proliferation, and resistance to apoptosis. Additionally, altered expression of hormone receptors (ESR1 and PGR) disrupts normal hormone-responsive gene regulation. The combined effect of these signaling abnormalities creates a cellular environment conducive to breast cancer initiation and progression.

#### Hypothesis 3: Altered Cell Cycle Control and Differentiation
Misexpression of cell cycle regulators like CCND1 and MYC, combined with altered expression of developmental regulators such as HOX genes, leads to a state of aberrant cell cycle control and impaired differentiation. This results in a population of breast epithelial cells that continue to proliferate but fail to terminally differentiate. These cells are more susceptible to additional genetic and epigenetic changes, increasing the likelihood of malignant transformation. Furthermore, the altered expression of HOX genes may contribute to the acquisition of stem cell-like properties, promoting tumor initiation and progression.

## Task D

### Building a protein:protein interaction network (PPI)

PPI and gene co-expression networks differ when it comes to how their data is sourced and derived, their focus, and their significance from a biological standpoint. A PPI network works by mapping interactions, both physical and functional, between proteins and shows how they collaborate to effectively function. This network uses experimental methods to identify hub proteins critical to diseases with Yeast two-hybrid screening (Y2H) and the coupling of affinity purification with mass spectrometry (AP-MS) being the two most common. Gene co-expression network highlights similar expression patters of genes across differing conditions and/or tissues to suggest co-regulation or shared functions. This network uses RNA-seq, microarrays, or other transcriptomic data to show tissue or disease-specific gene activity.
## Task E
### Tissue-specific eQTLs DNA polymorphisms that could alter the expression of the candidate genes
#### Tissue-Specific eQTLs in Breast Tissue:
The GTEx (Genotype-Tissue Expression) project provides data on eQTLs specific to breast tissue 1. These eQTLs are genetic variants that influence gene expression in breast tissue, which is crucial for understanding breast cancer risk.
#### Identification of Candidate Genes:
Several studies have used eQTL data from both tumor and normal breast tissues to identify candidate target genes for breast cancer 2. This approach helps in understanding how genetic variations might contribute to breast cancer risk.
#### Variable eQTLs (veQTLs):
A study by Wiggins et al. (2021) focused on significant (p < 5 × 10–8) variable eQTLs (veQTLs) unique to breast tissue to predict candidate genes involved in breast cancer risk 3. These veQTLs represent genetic variants that not only affect gene expression but also its variability.
#### Multi-Tissue Transcriptome-Wide Association Studies (TWASs):
Recent studies have employed multi-tissue TWASs to identify candidate genes for breast cancer. These studies consider both expression-based and splicing-based approaches, providing a comprehensive view of genetic influences on breast cancer risk 4.
#### Cis and Trans eQTLs:
Both cis-eQTLs (affecting nearby genes) and trans-eQTLs (affecting distant genes) have been identified in breast cancer studies. A recent study by Head et al. (2024) found that the median number of estimated eQTLs per gene was 1.14, with trans-eQTLs also playing a significant role.
#### Cancer Cell-Specific eQTLs:
Interestingly, a study by Geeleher et al. (2018) found that only about one-third of breast cancer risk variants identified as eQTLs from conventional analysis could be confidently attributed to cancer cells 6. This highlights the importance of cell-type-specific eQTL analysis in cancer research.

## Task F
Hypothesis:
The dysregulation of a specific PPI network involving BRCA1, BRCA2, and TP53 leads to aberrant gene expression patterns, resulting in the breast cancer phenotype through mechanism X, where X is defined as impaired DNA damage repair and cell cycle checkpoint control.

Experimental Design:

Model System Selection:
Use MCF-10A cells (non-tumorigenic human breast epithelial cells) as the primary model system, along with MCF-7 and MDA-MB-231 (breast cancer cell lines) for comparison 1.

Identification of Target PPI Network:
Focus on the PPI network involving BRCA1, BRCA2, and TP53, which are known to be crucial in DNA repair and cell cycle regulation 2.

Gene Manipulation:
a) Use CRISPR-Cas9 to create single and combinatorial knockouts of BRCA1, BRCA2, and TP53 in MCF-10A cells 3.
b) Generate overexpression lines for each gene.
c) Create cell lines with specific mutations found in breast cancer patients (e.g., BRCA1 185delAG, BRCA2 6174delT, TP53 R175H) 4.

RNA-Seq Analysis:
a) Perform RNA-Seq on wild-type and mutant cell lines under normal conditions and after DNA damage induction (e.g., ionizing radiation) 5.
b) Include at least 3 biological replicates for each condition.
c) Analyze differential gene expression, focusing on genes involved in DNA repair, cell cycle control, and apoptosis.

Protein-Protein Interaction Assays:
a) Use co-immunoprecipitation followed by mass spectrometry to identify and quantify protein interactions in the network 6.
b) Perform proximity ligation assays to visualize PPIs in situ, comparing wild-type and mutant cells.

Phenotypic Analysis:
a) Assess cell proliferation rates, cell cycle distribution, and apoptosis in all cell lines.
b) Measure DNA damage repair efficiency using comet assays and γ-H2AX foci formation 7.
c) Evaluate genomic instability through chromosome spreads and FISH analysis.

Network Modeling:
a) Construct a computational model of the PPI network using the experimental data.
b) Use systems biology approaches to predict how network perturbations affect gene expression and cellular phenotypes 8.

Validation Experiments:
a) Perform ChIP-seq for BRCA1, BRCA2, and TP53 to identify changes in their genomic binding sites across different cell lines 9.
b) Use qRT-PCR to validate expression changes in key target genes identified from RNA-Seq.

Protein Level Analysis:
a) Conduct Western blot analysis for key proteins in the network and their post-translational modifications.
b) Use RPPA (Reverse Phase Protein Array) to quantify changes in protein levels and phosphorylation states across the cell lines 10.

Functional Assays:
a) Perform homologous recombination and non-homologous end joining assays to assess DNA repair efficiency 11.
b) Use flow cytometry to analyze cell cycle checkpoints after DNA damage induction.
c) Assess cellular transformation using soft agar colony formation assays.

3D Culture and In Vivo Models:
a) Grow cells in 3D Matrigel cultures to assess acini formation and polarization 12.
b) Implant cells into immunodeficient mice to evaluate tumor formation and growth in vivo.

Multi-omics Integration:
a) Integrate transcriptomics, proteomics, and interactomics data using advanced bioinformatics approaches.
b) Use machine learning algorithms to identify key network features that correlate with the cancer phenotype.

Drug Response Profiling:
a) Test the response of wild-type and mutant cells to PARP inhibitors and platinum-based drugs 13.
b) Perform high-throughput drug screening to identify compounds that specifically target cells with disrupted PPI networks.

Control Experiments:
a) Include isogenic controls for each genetic manipulation.
b) Perform rescue experiments by reintroducing wild-type genes into knockout cell lines.

**Expected Outcomes:

A comprehensive dataset linking PPI network perturbations to changes in gene expression, DNA repair efficiency, and cancer-related phenotypes.
Identification of key nodes and edges in the PPI network that are critical for maintaining normal gene expression and preventing the cancer phenotype.
Potential discovery of novel regulatory mechanisms within the BRCA1/BRCA2/TP53 network.
A refined model of how disruptions in this PPI network lead to breast cancer through aberrant gene expression and impaired DNA repair.
Potential Challenges and Considerations:

Some genetic manipulations may be lethal, requiring the use of inducible systems.
The complexity of the PPI network may make it challenging to isolate the effects of individual interactions.
In vitro results may not fully recapitulate the in vivo tumor microenvironment.
This experimental design provides a comprehensive approach to testing the hypothesis that alterations in the PPI genetic subsystem network involving BRCA1, BRCA2, and TP53 can lead to non-wild-type gene expression and ultimately to the breast cancer phenotype. By combining multiple levels of analysis from genomics to phenotypic assays, we can build a detailed understanding of how this PPI network influences gene expression, DNA repair, and cellular transformation in breast cancer.
