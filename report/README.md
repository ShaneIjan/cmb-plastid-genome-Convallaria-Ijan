# Final Report

This folder contains the completed plastid genome characterization report for *Convallaria majalis*.

---

## Choosing and Recording a Plant Genus

The genus ***Convallaria*** was selected for this activity after confirming the availability of a complete plastid/chloroplast genome. After reserving the genus, *Convallaria majalis* was chosen as the species for plastid genome characterization because a complete and annotated chloroplast/plastid genome is available for this species.

---

## Data Source and Genome Selection

The complete chloroplast genome of *Convallaria majalis* was obtained from the **NCBI RefSeq** database. The selected record was verified as a complete and annotated chloroplast genome, and both the FASTA sequence and full GenBank annotation file were retained for the succeeding analyses.

| Information | Details |
|---|---|
| **Organism** | *Convallaria majalis* |
| **Chosen Genus** | *Convallaria* |
| **Family** | Asparagaceae |
| **Database Source** | NCBI RefSeq |
| **NCBI Accession/Version** | `NC_063623.1` |
| **Genome Type** | Chloroplast / plastid genome |
| **Genome Completeness** | Complete genome / full length |
| **Genome Length** | 162,198 bp |
| **Topology** | Circular |
| **NCBI Record** | `NC_063623.1` |
| **Associated Publication** | *Intracellular DNA transfer events restricted to the genus Convallaria within the Asparagaceae family: Possible mechanisms and potential as genetic markers for biogeographical studies* |
| **Authors** | Raman, G., Lee, E. M., & Park, S. |
| **Journal** | *Genomics*, 113(5), 2906–2918 (2021) |
| **FASTA File Retained** | `Convallaria_majalis_NC_063623.1.fasta` |
| **Annotated GenBank File Retained** | `Convallaria_majalis_NC_063623.1.gb` |

---

## Files to Obtain

The required genome files for *Convallaria majalis* were obtained from the selected NCBI RefSeq record. These files will be used for sequence analysis, genome annotation review, and documentation of the genome source.

| File | Format | File / Source | Purpose |
|---|---|---|---|
| Genome sequence | FASTA | `Convallaria_majalis_NC_063623.1.fasta` | Upload to Galaxy and obtain sequence statistics |
| Annotated genome | GenBank / RefSeq annotation | `Convallaria_majalis_NC_063623.1.gb` | Identify genes, coordinates, introns, pseudogenes, and other genome features |
| Source information | NCBI RefSeq record | `NC_063623.1` | Document the origin of the genome used |

---

## Galaxy Workflow and Sequence Statistics

The complete chloroplast genome FASTA file of *Convallaria majalis* was uploaded to Galaxy and analyzed using the **FASTA Statistics** tool. The analysis was used to confirm the genome length, number of sequence records, GC content, and whether the complete plastome was represented by a single sequence.

### Galaxy FASTA Statistics

| Statistic | Result |
|---|---:|
| Genome length | 162,198 bp |
| Number of sequence records | 1 |
| GC content | 37.88% |
| Number of gaps | 0 |
| Complete plastome represented by one sequence record? | Yes |

The Galaxy analysis showed that the *Convallaria majalis* plastome is represented by a single continuous sequence of 162,198 bp with a GC content of 37.88%. The absence of gaps suggests that the uploaded sequence is complete and suitable for further plastid genome characterization and annotation review.

### Galaxy History

- **History Name:** `Plastid_Convallaria_Ijan`
- **Tool Used:** FASTA Statistics
- **Galaxy History Link:** https://usegalaxy.org/u/ijanshane17/h/plastid-convallaria-ijan

---

## Required Plastid Genome Characterization

The chloroplast genome of ***Convallaria majalis*** was characterized using the NCBI RefSeq annotation, Galaxy FASTA Statistics results, and information from the associated publication. The genome is circular and contains the typical large single-copy (LSC), small single-copy (SSC), and two inverted repeat (IR) regions.

| Characteristic | Result |
|---|---|
| **Chosen genus** | *Convallaria* |
| **Chosen species** | *Convallaria majalis* |
| **Family** | Asparagaceae |
| **NCBI accession/version** | `NC_063623.1` |
| **Complete genome size** | 162,198 bp |
| **GC content** | 37.88% |
| **Genome topology** | Circular |
| **LSC size** | 85,431 bp |
| **SSC size** | 18,487 bp |
| **IR size** | 29,140 bp each |
| **Total annotated gene entries** | 132 |
| **Protein-coding genes (CDS entries)** | 86 |
| **tRNA genes** | 38 |
| **rRNA genes** | 8 |
| **Introns** | Present |
| **Pseudogenes** | None explicitly annotated in the RefSeq GenBank file |
| **Gene duplications** | Present, mainly within the inverted-repeat regions |
| **Other notable feature** | Presence of a mitochondrial-origin DNA segment within the plastid genome |

### Gene Groups Identified

The annotated chloroplast genome of *Convallaria majalis* contains genes belonging to the major functional groups commonly found in plastid genomes.

| Gene Group | Genes Identified |
|---|---|
| **Photosystem I (`psa`)** | `psaA`, `psaB`, `psaC`, `psaI`, `psaJ` |
| **Photosystem II (`psb`)** | `psbA`, `psbB`, `psbC`, `psbD`, `psbE`, `psbF`, `psbH`, `psbI`, `psbJ`, `psbK`, `psbL`, `psbM`, `psbN`, `psbT`, `psbZ` |
| **ATP synthase (`atp`)** | `atpA`, `atpB`, `atpE`, `atpF`, `atpH`, `atpI` |
| **Cytochrome b6f (`pet`)** | `petA`, `petB`, `petD`, `petG`, `petL`, `petN` |
| **Rubisco large subunit** | `rbcL` |
| **RNA polymerase (`rpo`)** | `rpoA`, `rpoB`, `rpoC1`, `rpoC2` |
| **Large ribosomal proteins (`rpl`)** | `rpl2`, `rpl14`, `rpl16`, `rpl20`, `rpl22`, `rpl23`, `rpl32`, `rpl33`, `rpl36` |
| **Small ribosomal proteins (`rps`)** | `rps2`, `rps3`, `rps4`, `rps7`, `rps8`, `rps11`, `rps12`, `rps14`, `rps15`, `rps16`, `rps18`, `rps19` |
| **rRNA genes (`rrn`)** | `rrn16`, `rrn23`, `rrn4.5`, `rrn5` |
| **tRNA genes (`trn`)** | Multiple `trn` genes are present, including `trnH-GUG`, `trnK-UUU`, `trnM-CAU`, `trnL-UAA`, `trnI-GAU`, `trnA-UGC`, and `trnN-GUU` |
| **Other conserved plastid genes** | `matK`, `clpP`, `accD`, `cemA`, `ycf1`, `ycf2`, `ycf3`, `ycf4` |

## Questions for the Student Report

### 1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.

The selected organism is *Convallaria majalis*, which belongs to the family Asparagaceae. Its chloroplast genome was obtained from NCBI RefSeq with accession/version **NC_063623.1**. The complete plastid genome is **162,198 bp** long.

### 2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?

The NCBI record identifies the sequence as ***Convallaria majalis chloroplast, complete genome*** and specifies the organelle as **plastid:chloroplast**. It is also described as full length and circular, showing that it represents the complete chloroplast genome rather than a barcode marker or genome fragment.

### 3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.

Yes. The chloroplast genome has the typical quadripartite arrangement composed of a large single-copy region (LSC), a small single-copy region (SSC), and two inverted repeat regions (IRs).

- **LSC:** 85,431 bp
- **SSC:** 18,487 bp
- **IR:** 29,140 bp each

### 4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.

The RefSeq GenBank annotation contains **132** annotated gene entries, including **86** CDS entries, **38** tRNA genes, and **8** rRNA genes. No pseudogene is explicitly annotated in the downloaded RefSeq file.

Some genes appear in two copies because they are located within the two inverted repeat regions, IRa and IRb. Since these regions are duplicated, the genes found within them are also duplicated.

### 5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.

- **`psaA`** – Encodes a core Photosystem I protein involved in light-driven electron transfer.
- **`psbA`** – Encodes the D1 protein of Photosystem II, which participates in photosynthetic electron transport.
- **`atpB`** – Encodes a subunit of ATP synthase involved in ATP production.
- **`petA`** – Encodes cytochrome f, which helps transfer electrons between Photosystem II and Photosystem I.
- **`rbcL`** – Encodes the large subunit of RuBisCO and is involved in carbon fixation.
- **`rpoB`** – Encodes a subunit of plastid RNA polymerase used in transcription.
- **`rpl2`** – Encodes a protein of the large ribosomal subunit.
- **`rps16`** – Encodes a protein of the small ribosomal subunit.
- **`matK`** – Encodes a maturase involved in the splicing of some chloroplast introns.
- **`clpP`** – Encodes a protease involved in protein degradation and maintenance.

### 6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.

The chloroplast genome contains the rRNA genes **`rrn16`, `rrn23`, `rrn4.5`, and `rrn5`**. Examples of tRNA genes include **`trnH-GUG`, `trnK-UUU`, `trnM-CAU`, `trnL-UAA`, `trnI-GAU`, and `trnA-UGC`**.

Genes with introns include **`rps16`, `atpF`, `rpoC1`, `petB`, `petD`, `rpl16`, `ndhB`, `clpP`, and `ycf3`**. The **`rps12`** gene is also notable because it is trans-spliced.

### 7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome.

No pseudogene is explicitly annotated in the downloaded RefSeq GenBank file. Several genes are duplicated because they occur within the inverted repeat regions. One unusual feature reported for the *Convallaria majalis* plastome is the presence of a **3,322-bp DNA segment of mitochondrial origin** within the chloroplast genome.

### 8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.

The GC content obtained from the Galaxy FASTA Statistics analysis was **37.88%**. Two prominent observation are that the complete plastome is represented by a single sequence record with a total length of 162,198 bp. It also shows the typical LSC-IR-SSC-IR organization, with several genes duplicated within the inverted repeat regions.

### 9. Compare plastid and mitochondrial genomes.

Plastid and mitochondrial genomes share several similarities. Both are organelle genomes, contain their own DNA, occur in multiple copies within a cell, encode some of their own rRNAs and tRNAs, and are commonly inherited through the cytoplasm in plants (Birky, 2001; Smith & Keeling, 2015).

However, they also differ in several ways. Plastid genomes are located in plastids such as chloroplasts and mainly contain genes related to photosynthesis and plastid function, while mitochondrial genomes are found in mitochondria and mainly contain genes involved in cellular respiration and energy production (Wicke et al., 2011; Smith & Keeling, 2015). Plastid genomes are generally smaller and more structurally conserved, whereas plant mitochondrial genomes are usually larger and show more frequent recombination and structural rearrangements (Wicke et al., 2011; Sakamoto et al., 2020). Plastid gene order is also usually more conserved, while mitochondrial genome organization can vary greatly among plant species (Smith & Keeling, 2015). In terms of evolution, plastid genomes generally show more stable genome organization, while plant mitochondrial genomes often undergo extensive structural change despite relatively low nucleotide substitution rates (Sakamoto et al., 2020).

### 10. Explain the practical value of plastid genomes in research. Include advantages, limitations, and examples of research questions.

Plastid genomes are useful because they are relatively small, compact, abundant, and easier to analyze than large nuclear genomes. Their structure and gene content are also fairly conserved, making them useful in plant identification, phylogenetics, evolutionary studies, and biogeography. Other advantages include easier genome assembly, high copy number in plant cells, and relatively conserved gene order. Plastid genomes are also useful for maternal lineage studies and DNA barcoding. 

However, plastid genomes also have limitations. They represent only the plastid lineage and cannot provide the full genetic history of an organism. They are also less useful for studying nuclear-controlled traits, biparental inheritance, sex-linked genes, or complex traits.

**Research question suitable for plastid data:**  
How are different *Convallaria* species evolutionarily related based on their chloroplast genomes?

**Research question more suitable for nuclear genomic data:**  
Which nuclear genes are associated with differences in flower development or other complex traits among *Convallaria* populations?

---

## Plastid vs Mitochondrial Genome Comparison

Plastid and mitochondrial genomes are both organelle genomes, but they differ in their functions, organization, inheritance, and evolutionary behavior. The table below summarizes the major similarities and differences using information from the selected *Convallaria majalis* plastome and reliable references.

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| **Cellular location** | Found in plastids, especially chloroplasts (Wicke et al., 2011). | Found in mitochondria (Smith & Keeling, 2015). |
| **Main biological functions** | Mainly involved in photosynthesis, carbon fixation, and plastid gene expression (Wicke et al., 2011). | Mainly involved in cellular respiration, electron transport, and ATP production (Smith & Keeling, 2015). |
| **Typical genome organization** | Usually relatively compact and conserved; many land-plant plastomes have LSC, SSC, and two IR regions (Wicke et al., 2011). | Plant mitochondrial genomes are often structurally complex and show frequent rearrangements and recombination (Sakamoto et al., 2020). |
| **Relative genome size** | Generally smaller and more compact than plant mitochondrial genomes (Smith & Keeling, 2015). | Usually much larger and highly variable in size among plant species (Smith & Keeling, 2015). |
| **Gene content** | Contains photosynthesis-related genes, ribosomal protein genes, rRNA genes, tRNA genes, and other plastid genes (Wicke et al., 2011). | Contains genes mainly related to respiration, along with rRNA and tRNA genes (Smith & Keeling, 2015). |
| **Copy number** | Present in multiple copies within plastids and plant cells (Birky, 2001). | Also present in multiple copies within mitochondria and cells (Birky, 2001). |
| **Inheritance** | Commonly maternally inherited in angiosperms, although paternal or biparental inheritance can occur (Birky, 2001). | Commonly maternally inherited in plants, although exceptions occur (Birky, 2001). |
| **Recombination / structural change** | Generally more structurally conserved, although rearrangements can occur (Wicke et al., 2011). | Shows frequent recombination and structural rearrangements, especially in plants (Sakamoto et al., 2020). |
| **Mutation / substitution pattern** | Plastid genomes generally show moderate sequence evolution, with rates varying among genes and regions (Wicke et al., 2011). | Plant mitochondrial genomes often have relatively low nucleotide substitution rates despite high structural variability (Sakamoto et al., 2020). |
| **Common research applications** | Commonly used in plant phylogeny, species identification, comparative genomics, and biogeography (Wicke et al., 2011). | Used in studies of mitochondrial evolution, cytoplasmic inheritance, genome rearrangement, and respiration (Smith & Keeling, 2015; Sakamoto et al., 2020). |

---

## References

Birky, C. W., Jr. (2001). The inheritance of genes in mitochondria and chloroplasts: Laws, mechanisms, and models. Annual Review of Genetics, 35, 125–148. https://doi.org/10.1146/annurev.genet.35.102401.090231

National Center for Biotechnology Information. (n.d.). Convallaria majalis chloroplast, complete genome (NC_063623.1). NCBI Nucleotide. https://www.ncbi.nlm.nih.gov/nuccore/NC_063623.1

Raman, G., Lee, E. M., & Park, S. (2021). Intracellular DNA transfer events restricted to the genus *Convallaria* within the Asparagaceae family: Possible mechanisms and potential as genetic markers for biographical studies. Genomics, 113(5), 2906–2918. https://doi.org/10.1016/j.ygeno.2021.06.033

Sakamoto, W., Takami, T., & Beppu, T. (2020). DNA repair and the stability of the plant mitochondrial genome. International Journal of Molecular Sciences, 21(2), 328. https://doi.org/10.3390/ijms21020328

Smith, D. R., & Keeling, P. J. (2015). Mitochondrial and plastid genome architecture: Reoccurring themes, but significant differences at the extremes. Proceedings of the National Academy of Sciences, 112(33), 10177–10184. https://doi.org/10.1073/pnas.1422049112

Wicke, S., Schneeweiss, G. M., dePamphilis, C. W., Müller, K. F., & Quandt, D. (2011). The evolution of the plastid chromosome in land plants: Gene content, gene order, gene function. Plant Molecular Biology, 76, 273–297. https://doi.org/10.1007/s11103-011-9762-4
