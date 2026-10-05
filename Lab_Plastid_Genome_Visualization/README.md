# Visualize Plastid Genome Structure

## Student Information

**Name:** Shane Mae B. Ijan
**Section**: A 


## Selected Plastid Genome

- **Scientific Name:** *Convallaria majalis*
- **NCBI Accession Number:** `NC_063623.1`
- **Plastid Genome Length:** 162,198 bp
- **Genome File Source:** NCBI RefSeq
- **Annotated GenBank File:** `Convallaria_majalis_NC_063623.1.gb`


## Software Used

The plastid genome map was generated using **OGDRAW (OrganellarGenomeDRAW)** through the CHLOROBOX platform.


## OGDRAW Settings and Visualization Procedure

The annotated GenBank file of *Convallaria majalis* was uploaded to OGDRAW using the **Standard** map mode. The genome map was set to **Circular**, while the sequence source was set to **Plastid**. Inverted repeat regions were detected automatically.

The **GC content graph**, **direction of transcription**, and **full legend** were displayed on the map. The option to mark intron-containing genes with an asterisk was also enabled. The final genome map was generated in **PNG format** with the resolution selected as **superfine** for a high-quality output.


## Plastid Genome Map

![Plastid genome map](figures/Convallaria_majalis_plastid_map.png)


**Figure 1. Circular plastid genome map of *Convallaria majalis*.**  

The OGDRAW map shows the organization of the complete plastid genome, including the **large single-copy region (LSC)**, **small single-copy region (SSC)**, and the two inverted repeat regions, **IRa** and **IRb**. Different colored gene blocks represent functional gene groups distributed around the genome. The direction of the gene blocks indicates transcriptional orientation, while the inner graph shows changes in GC content across the plastid genome.


## Main Structural Features Observed

The *Convallaria majalis* plastid genome shows the typical quadripartite structure of many plant plastomes. The LSC occupies the largest portion of the genome, while the SSC is smaller and is located between the two inverted repeat regions, IRa and IRb. Protein-coding genes, tRNA genes, and rRNA genes are distributed throughout the genome, while some genes occur more than once because they are located within the duplicated inverted repeat regions.

The OGDRAW map also makes the direction of transcription easier to observe because genes are arranged in different orientations around the circular genome. The inner GC-content graph shows that GC content varies slightly across different regions rather than being completely uniform.


## Answers to Part E

The complete answers to the plastid genome visualization questions are available in:

[`answers/Lab_plastid_genome_answers.md`](answers/Lab_plastid_genome_answers.md)


## References

Greiner, S., Lehwark, P., & Bock, R. (2019). OrganellarGenomeDRAW (OGDRAW) version 1.3.1: Expanded toolkit for the graphical visualization of organellar genomes. *Nucleic Acids Research, 47*(W1), W59–W64. https://doi.org/10.1093/nar/gkz238

National Center for Biotechnology Information. (n.d.). *Convallaria majalis chloroplast, complete genome (NC_063623.1).* NCBI Nucleotide. https://www.ncbi.nlm.nih.gov/nuccore/NC_063623.1

OGDRAW - OrganellarGenomeDRAW. CHLOROBOX, Max Planck Institute of Molecular Plant Physiology. https://chlorobox.mpimp-golm.mpg.de/OGDraw.html
