##Phylogenetic analysis of 2014 Ebolavirus outbreak in Guinea.

This repository contains three alignments (nexus format) and three trees (FigTree format) that were used by [@rambaut](https://github.com/rambaut) and [I](https://github.com/evogytis) in the [PLOS Currents Outbreaks paper](http://currents.plos.org/outbreaks/article/phylogenetic-analysis-of-guinea-2014-ebov-ebolavirus-outbreak-2/):
- `ebolavirus_cds.nex` - contains 7 concatenated protein coding sequences from 49 ebolavirus genomes. This alignment was analyzed using MrBayes. The resulting tree `ebolavirus_cds.nex.con.tre` was used to make Figures 2 and 3.
- `ebolavirus_intergenic.nex` - contains concatenated non-coding sequences from 49 ebolavirus genomes. This alignment was also analyzed in MrBayes. The resulting tree `ebolavirus_intergenic.nex.con.tre` was used to make Figure 4.
- `ebolavirus_raw.nex` - contains 49 aligned complete ebolavirus genomes. This alignment was analyzed in PhyML and the resulting tree, `ebolavirus_raw.phyml.tree` was used to make Figure 1.

==============
###Acknowledgments

We would like to thank Stephan Günther at the Bernhard Nocht Institute for Tropical Medicine, Hamburg and his co-authors for sending the 2014 Guinea outbreak sequences ahead of their publication on Genbank.
