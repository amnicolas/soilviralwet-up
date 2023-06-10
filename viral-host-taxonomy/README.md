This directory contains csv files generated using the python notebook here. 

1. all_vOTU_host_predictions_xsource.csv contains for each vOTU a host prediction and the source of the host prediction:

* MAG (CRISPR spacer match)
* Kaiju (Kaiju taxonomy predicted per vOTU sequence)
* unbinned (Kaiju taxonomy of an unbinned contig containing a CRISPR spacer from metagenome sequences)
* spacerDB (NCBI taxonomy from a sequence containing a spacer identified in Shmakov et al., 2017)

2. consensus_host_taxa.csv contains the domain and taxon used in analyses of each vOTU determined based on the consensus of all host taxonomic predictions. 
