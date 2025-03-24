# sacCer3-annotation
evolving gtf files describing the locations of ORFs, ncRNAs, and common splicing events in the sacCer3 genome assembly for Saccharomyces cerevisiae.

Version 11 and version 13 are avaialable.
A difference file is included.
Main changes between 11 and 13 are removal of some dubious orfs, extensions of exons for some intron-containing genes based on cap site and transcript evidence, and simplification of alternatively spliced genes to represent the major isoforms that can be reasonably quantified using kallisto.

The first line provides track information for loading into a UCSC style genome browser. This line should be commented out when used for indexing for kallisto
