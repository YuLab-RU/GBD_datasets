# Codon Usage


## About this dataset
We examined codon usage frequencies in the genomic coding DNA of a large sample of diverse organisms from different taxa tabulated in the CUTG database, where we further manually curated and harmonized these existing entries.

## Data Description
Column 1: Kingdom. The 'Kingdom' is a 3-letter code corresponding to `xxx' in the CUTG database name: 'arc'(archaea), 'bct'(bacteria), 'phg'(bacteriophage), 'plm' (plasmid), 'pln' (plant), 'inv' (invertebrate), 'vrt' (vertebrate), 'mam' (mammal), 'rod' (rodent), 'pri' (primate), and 'vrl'(virus) sequence entries. Note that the CUTG database does not contain 'arc' and 'plm' (these have been manually curated ourselves).

Column 2: DNAtype. The 'DNAtype' is denoted as an integer for the genomic composition in the species: 0-genomic, 1-mitochondrial, 2-chloroplast. 

Column 3: SpeciesID. The species identifier ('SpeciesID') is an integer, which uniquely indicates the entries of an organism. It is an accession identifier for each different species in the original CUTG database, followed by the first item listed in each genome.

Column 4: Ncodons. The number of codons (`Ncodons') is the algebraic sum of the numbers listed for the different codons in an entry of CUTG. Codon frequencies are normalized to the total codon count, hence the number of occurrences divided by 'Ncodons' is the codon frequencies listed in the data file.

Column 5: SpeciesName. The species' name ('SpeciesName') is represented in strings purged of comma (which are now replaced by a space). This is a descriptive label of the name of the species for data interpretations.

Columns 6-69: codon. The headers are nucleotide bases ('UUU', 'UUA', 'UUG', 'CUU', etc.). The values are frequency of the codon usage (5 digit floating point numbers).


## Acknowledgements
Bohdan Khomtchouk, Ph.D. University of Chicago, Department of Medicine, Section of Computational Biomedicine and Biomedical Data Science. Email: bohdan '@' uchicago.edu

