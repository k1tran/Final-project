# Final-project
Final project
Project 3
Scientific Question: Is there a common ancestor with the Périgord black truffle (Tuber melanosporum) and Homo Sapiens?
Housekeeping genes are constitutively active genes that perform basal cellular functions that are required for the cell to properly function. In order for eukaryotic organisms to perform essential cellular duties, specific molecular genes are conserved along their evolutionary lineage to properly function within their respective ecosystem. 18S rRNA is a gene used to indicate the cell number in order to derive the standardization in gene expression analysis. Elongation Factor 1 alpha is another housekeeping gene that can guage lineage because of its enzymatic functional delivery of aminoacyl tRNAs to the ribosome, which is needed in the central dogma of biology.

Phylogeny is the study of relationships among organisms and their evolutionary divergences from one another. By connecting species together and finding common ancestry, biologists are able to get an idea of a possible traits, symbiosis, and medicinal that have yet to be seen in the molecular studies of the species. These relationships can be mapped out by mnitoring the significant changes in the sequencing of these housekeping and looking at continuities and differences via a NCBI BLAST gene database (https://blast.ncbi.nlm.nih.gov/Blast.cgi)

"NCBI gene is a searchable database of genes, focusing on genomes that have been completely sequenced and that have an active research community to contribute gene-specific data. Information includes nomenclature, chromosomal localization, gene products and their attributes (e.g., protein interactions), associated markers, phenotypes, interactions, and links to citations, sequences, variation details, maps, expression reports, homologs, protein domain content, and external databases."

Scientific Hypothesis: If the proteins of interest (18S rRNA and EF1 alpha) from the NCBI database between the two species demonstrate a statistically significant sequence similarity, then the protein gene sequence can be used to retrace the lineage to choanoflagellates.

Part 1: Load the Packages
os: portable way of using operating system dependent functionality Bio: helps with the dealing of biological data in Python.

Part 2: Load in the data and perform Bioinformatics Analyses (Sequence Allginments & Similarity Analyses)
Within each FASTA file, the sequencing data for both the genes of the proteins will be loaded into a variable storage. Once this is complete. The code will then see if the sequences are numerically capable of being compared to one another. Then BLAST will be imported from biopython to compare and output a similarity report about the sequences.

Part 3: Create a Phylogenetic Tree showing evolutionary lineage.
Here we use biopython to create a Phylogenetic tree that is printed below. The axis of time are represented on the x-axis and the end of each branch represents a species. The commas represent a node or branch point. In this code, two graphics (EF and 18s rRNA) were produced to examine evolutionary relationships. By retracing the lineage and representing the data this way, it can be used to determine common ancestors,convergent evolution, homologies.

Part 4 Analysis of the results
The two graphics illustrate the evolutionary relationship between the black perigold truffle and homo sapiens. As seen in the graphics, the tree tells very different stories about the lineage of these two species. From the 18s RNA tree, it is determined that the tuber melonsporum is more evolutionarily similar to Octodon than to a homo sapien. The common ancestor to these species would then have to be retraced to the ancestor the progenated Homo Sapiens and Callorhinus. From the Elongation factor tree, it is determined that the tuber melonsporum is more evolutionarily similar to the homo sapiens and Heterocephalus. The common ancestor to these species would then have to be retraced to the ancestor the progenated homo sapiens and Heterocephalus. These datasets tell different stories. Thus, my hypothesis was proven wrong because the phylogenetic trees have shown that the protein sequences do not show a drastic relationship to choanoflagellates. This could possibily be due to the difference in gene sequences, and how long it took for the organism to gain it. A possible exploration that this dataset could provide is adding more species to be compared.
