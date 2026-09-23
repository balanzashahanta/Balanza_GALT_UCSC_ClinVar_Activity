# Exploring a Human Disease Gene Using UCSC Genome Browser and NCBI ClinVar

**Name:** Shahanta Dawn B. Balanza  
**Previously Assigned Gene:** GALT  
**Associated Disease:** Classic Galactosemia  
**Date:** September 23, 2026

## Activity Purpose

This activity investigates the human **GALT** gene using the **UCSC Genome Browser** and **NCBI ClinVar**. The activity focuses on locating the GALT gene in the human genome, examining its exon-intron structure and transcripts, exploring genome annotation and clinical variant tracks, and investigating a clinically reported GALT variant.

### Activity Workflow

1. Located the **GALT** gene in the UCSC Genome Browser using the **GRCh38/hg38** assembly.
2. Examined the **exon-intron structure and transcript models** using the GENCODE and NCBI RefSeq tracks.
3. Enabled the **ClinVar** and **conservation** tracks to examine clinical variants and conserved regions.
4. Selected the **GALT c.563A>G (p.Gln188Arg/Q188R)** variant from ClinVar.
5. Used the GRCh38 genomic coordinate **chr9:34648170** to locate the selected variant in UCSC.
6. Compared the variant location with the GALT gene model and interpreted its possible effect using the available genomic and clinical information.

## 1. Assigned Gene and Disease
The assigned gene is **GALT (galactose-1-phosphate uridylyltransferase)**, and the associated disease is **Classic Galactosemia**.

## 2. UCSC Gene Location

The **GALT** gene was located using the **UCSC Genome Browser** with the human **GRCh38/hg38** assembly. The gene is located on **chromosome 9 (chr9)** at genomic coordinates **chr9:34,646,675–34,651,035**. The GALT gene is approximately **4,361 bp (4.36 kb)** in genomic length and is located on the **positive (+) DNA strand**.

| **Gene Location Information** | **Details** |
|---|---|
| **Official gene symbol** | **GALT** |
| **Full gene name** | **galactose-1-phosphate uridylyltransferase** |
| **Chromosome** | **9 (chr9)** |
| **Genome assembly** | **GRCh38/hg38** |
| **Genomic coordinates** | **chr9:34,646,675–34,651,035** |
| **DNA strand** | **Positive (+) strand** |
| **Approximate gene size** | **4,361 bp (~4.36 kb)** |

![Figure 1 - GALT gene location](images/01_gene_location.png)

**Figure 1.** UCSC Genome Browser showing the genomic location of the human **GALT** gene on chromosome 9.

## 3. Exons, Introns, and Transcripts

### a. Number of Exons

**11 exons** are identified in the selected **NM_000155.4 (GALT)** transcript.

### b. Multiple Transcripts/Isoforms

**Yes.** Multiple transcripts/isoforms of the **GALT** gene are visible in the UCSC Genome Browser.

### c. Difference Between an Exon and an Intron

An **exon** is a part of a gene that remains in the mature RNA after splicing, while an **intron** is an intervening part of the gene that is removed during RNA splicing.

### d. Intron vs. Exon Length

The **introns generally appear longer than the exons** in the **GALT** gene, as the regions connecting the exon blocks are generally more extensive than the exon regions themselves.

![Figure 2 - GALT gene structure](images/02_gene_structure.png)

**Figure 2.** UCSC Genome Browser showing the exon-intron structure and transcript models of the human **GALT** gene.

## 4. UCSC Annotation Tracks

### a. Which gene annotation track did you use?

The **GENCODE V50** and **NCBI RefSeq** tracks were used to view the gene and transcript annotations of the **GALT** gene.

### b. Were ClinVar-related variant marks visible within or near your gene?

**Yes.** Multiple ClinVar-related variant marks are visible within and near the **GALT** gene region.

### c. Were some regions more conserved than others?

**Yes.** The conservation track shows that some regions of the **GALT** gene are more strongly conserved than others.

### d. Did conserved regions correspond mainly to exons, introns, both, or another region?

The stronger conserved regions appear mainly around **exonic and coding regions**, although some conservation is also visible in non-coding regions.

### e. Why can strong conservation suggest biological importance?

Strong conservation suggests that a DNA region may have an important biological function because it has remained similar across different species. Regions that are important for normal gene or protein function are more likely to be preserved through evolution.

![Figure 3 - GALT gene with ClinVar and conservation tracks](images/03_tracks.png)

**Figure 3.** GALT gene with ClinVar and conservation tracks in UCSC Genome Browser.

## 5. Selected ClinVar Variant

The selected ClinVar variant is the **GALT c.563A>G (p.Gln188Arg)** variant, also known as **Q188R**, associated with galactosemia.

| Variant Information | Result |
|---|---|
| Gene | **GALT** |
| HGVS notation | **NM_000155.4(GALT):c.563A>G (p.Gln188Arg)** |
| rsID | **rs75391579** |
| ClinVar Variation ID | **3614** |
| Chromosome | **Chromosome 9** |
| Genomic position | **Chr9:34648170 (GRCh38)** |
| Condition | **Galactosemia** |
| Clinical significance | **Pathogenic** |
| Review status | **Criteria provided, multiple submitters, no conflicts** |
| ClinVar accession | **RCV000825563.20** |


![Figure 4 - ClinVar record for GALT Q188R](images/04_clinvar_variant.png)

**Figure 4.** ClinVar record for the **GALT c.563A>G (p.Gln188Arg)** variant associated with galactosemia.

**ClinVar:** https://www.ncbi.nlm.nih.gov/clinvar/RCV000825563/

## 6. Locating the Variant in UCSC

The selected ClinVar variant **NM_000155.4(GALT):c.563A>G (p.Gln188Arg)** was located in the UCSC Genome Browser using the GRCh38 genomic coordinate **chr9:34648170**.

### a. Where is the variant located relative to your gene?

The variant is located **within the GALT gene** at **chr9:34648170 (GRCh38)**.

### b. Is it in an exon, intron, UTR, splice region, or another region?

The variant is located in an **exon** of the GALT gene. ClinVar identifies the variant as occurring in **exon 6**.

### c. Is it likely in a coding or non-coding region?

The variant is likely in a **coding region**. The UCSC view shows **Q188** in the GALT protein annotation, consistent with the variant affecting amino acid 188.

### d. Based on its location and ClinVar information, how might the variant affect the gene or gene product?

The variant changes **c.563A>G**, resulting in the amino-acid substitution **p.Gln188Arg (Q188R)**. Because it changes an amino acid in the GALT protein and is classified as **pathogenic for galactosemia in ClinVar**, it may alter GALT protein function.

### e. What additional evidence would be needed before concluding that the variant causes disease?

Additional evidence could include **functional studies showing reduced GALT enzyme activity, observations in affected individuals, genetic segregation data, and population-frequency data**. These types of evidence help establish whether the variant has a disease-causing effect rather than relying only on its genomic location.


![Figure 5 - GALT variant in UCSC](images/05_variant_in_ucsc.png)

**Figure 5.** GALT gene model showing the selected ClinVar variant in UCSC Genome Browser.

## 7. Interpretation

The selected **GALT c.563A>G (p.Gln188Arg)** variant is located within an **exon and coding region** of the GALT gene. Its location corresponds to the **Q188** amino-acid position in the GALT protein, and ClinVar classifies the variant as **pathogenic** for galactosemia. However, genomic location alone is not sufficient to determine the complete biological effect of a variant, so functional and clinical evidence are also important.

## 8. Reflection

### 1. What did UCSC show you about your gene that was not obvious from simply reading about the gene's function?

UCSC showed me the actual **genomic structure and location of the GALT gene**, including its exons, introns, transcripts, and nearby genetic variants. It also allowed me to see how the gene is positioned on chromosome 9 and how different regions are conserved across species.

### 2. Why is knowing the exact genomic location of a disease-associated variant useful?

Knowing the exact genomic location helps determine where the variant occurs within the gene, such as in an exon, intron, or coding region. It also makes it easier to connect the variant to gene annotations and other genomic evidence.

### 3. What is one limitation of predicting a variant's effect only from its genomic location?

The location of a variant alone does not show exactly how it affects the gene or protein. Additional evidence, such as functional studies, clinical observations, and genetic data, is needed to determine its actual effect.

### 4. What was the most interesting feature you observed about your assigned gene?

The most interesting feature I observed was the presence of many **ClinVar variants** within the GALT gene region. I also found it interesting that the conservation track showed regions of different conservation levels across vertebrate species.

## 9. References and Links

- **UCSC Genome Browser:** https://genome.ucsc.edu/
- **NCBI ClinVar:** https://www.ncbi.nlm.nih.gov/clinvar/
- **NCBI Gene – GALT:** https://www.ncbi.nlm.nih.gov/gene/2592
- **NCBI ClinVar – GALT c.563A>G (p.Gln188Arg):** https://www.ncbi.nlm.nih.gov/clinvar/RCV000825563/
