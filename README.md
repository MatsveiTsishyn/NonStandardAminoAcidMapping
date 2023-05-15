
# Mapping of non-standard amino acids to their corresponding standard amino acid

## Introduction

Evolutionary information is central in Structural Bioinformatics through the use of Multiple Sequence Alignments (MSA).

While protein structure files (PDB) reference amino acids by their 3-letter name (which allow the specifications of a wide range of non-standard amino acids), sequence databases generally uses the 1-letter name and consider only the 20 standard proteogenic amino acids.

To simplify the 'translation' from protein structure to protein sequence, here is a mapping of 741 non-standard amino acids to their corresponding 'closest' standard amino acid (3-letter name).

## Method

Non standard amino acids list was found by scanning the `SEQRES` lines in 199.374 PDB structures from the [RCSB: Protein Data Bank](https://www.rcsb.org/).

The corresponding standard amino acid was assigned using the '[Chemical Components in the PDB](https://www.ebi.ac.uk/pdbe-srv/pdbechem/)' database.

Only entries which `Polymer type` property is `Amino Acid` and which `Standard parent` property corresponds to one of the 20 standard proteogenic amino acids were kept.

The scanning was made on 15/05/2023.

## Licence

GPL-3 or later.

## Contact

Matsvei Tsishyn, Université Libre de Bruxelles, 3BIO-BioInfo: Computational Biology and Bioinformatics.
