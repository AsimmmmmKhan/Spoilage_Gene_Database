# Custom Meat Spoilage Gene Database

This repository contains the custom-curated reference database for meat spoilage-related bacterial genes, as described in our associated manuscript.

# Overview

This database was constructed to improve the functional profiling of metagenomic data from meat processing environments, meat products, and other food-related ecosystems.
The database is built from two main components:

1. A core set of 336 spoilage-related genes curated from an extensive review of scientific literature.

2. An expanded set of 4,653 orthologous sequences sourced from the NCBI protein database to enhance detection sensitivity.

# All genes in this database are categorised into eight main functional pathways:

* Protein Metabolism
* Lipid Metabolism
* Sulphur Metabolism
* Regulatory Pathways
* Siderophore Production
* Biofilm Formation
* Stress Adaptation
* Quorum Sensing

# Files in this Repository

1. spoilage_genes_database.fa: The FASTA file containing all 4,653 de-duplicated protein sequences (336 core genes + 4,317 orthologs).
2. spoilage_annotations.csv: A spreadsheet containing detailed metadata for each sequence in the database.

# FASTA Header Format (spoilage_genes_database.fa)

The FASTA headers are formatted in a single, pipe-delimited (|) line for easy parsing.

* Example: >gi|1096123828|gb|APA31905.1|adnA|Flagellar and Biofilm Transcriptional Regulator|Pseudomonas fluorescens

# Breakdown:
* Field 1 (e.g., gi|1096123828): GenInfo Identifier (gi) from NCBI.
* Field 2 (e.g., gb|APA31905.1): GenBank Accession number for the protein.
* Field 3 (e.g., adnA): The gene symbol.
* Field 4 (e.g., Flagellar and Biofilm Transcriptional Regulator): The functional description of the protein.
* Field 5 (e.g., Pseudomonas fluorescens: The source organism name.

# Annotation File Legend (spoilage_annotations.csv)

# The annotation file contains the following columns:

* Species: The species name as described in the source article.
* Function_Category: The broad metabolic pathway the gene belongs to (e.g., Quorum Sensing, Biofilm Formation, etc.).
* Gene_Symbol: The common name or symbol of the gene (e.g., luxS, pfaA).
* Functional_Code_from_NCBI: The specific metabolic product or function of the gene as described in the NCBI database.
* Encoded_protein_from_articles: The specific product or function as described in the original publication.
* Cellular_Component: The specific location of the gene product (e.g., "Cell membrane"), sourced from UniProt.
* Molecular_Function: The specific molecular activity of the gene product (e.g., "ATP binding"), sourced from UniProt.
* Biological_Process: The biological process the gene is involved in (e.g., "siderophore biosynthetic process"), sourced from UniProt.

# Citation
If you use this database in your research, please cite both this data repository and our associated manuscript.
* Data Repository (Cite this): Asim ur Rahman, Vincenzo Valentino, José F. Cobo-Díaz, Avelino Álvarez Ordóñez, Danilo Ercolini, Francesca De Filippis. (2025). Custom Meat Spoilage Gene Database.
* Associated Manuscript (Please check for updates): Asim ur Rahman, Vincenzo Valentino, José F. Cobo-Díaz, Avelino Álvarez Ordóñez, Danilo Ercolini, Francesca De Filippis. (2025). [Season, Sanitation, and Bacteriophages Govern Microbial Ecology Across Beef Processing and Maturation Stages]. (Manuscript submitted for publication).


# Key References for Gene Curation
The core set of 336 genes was curated based on information from several key publications, including:

* https://doi.org/10.1016/j.ijfoodmicro.2021.109232

* https://doi.org/10.1016/j.ijfoodmicro.2024.110675

* https://doi.org/10.1016/j.foodchem.2024.139045

* https://doi.org/10.1016/j.fm.2024.104466

* https://doi.org/10.1016/j.tifs.2021.11.007

* http://doi.org/10.26599/FSHW.2022.9250118

* http://dx.doi.org/10.1080/08905436.2014.963601

* https://doi.org/10.1016/j.tifs.2021.11.007

# Contact

For questions regarding this database, please contact: Asim ur Rahman ([asimur.rahman@unina.it] or [arahman@bs.qau.edu.pk])