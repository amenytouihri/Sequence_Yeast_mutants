# Compensatory Mutations Restoring fMAPK Pathway Activity in ste4Δ Saccharomyces cerevisiae

In the yeast _Saccharomyces cerevisiae_, the filamentous growth mitogen-activated protein kinase (fMAPK) pathway is an essential signaling cascade that controls responses to environmental stress, mating cues, and nutritional deprivation. Like other MAPK pathways, the fMAPK pathway comprises a sequence of phosphorylation events that ultimately regulate gene expression, enabling cells to adapt and survive. The fMAPK pathway enables morphological changes during filamentous development, allowing the yeast to search for nutrients in suboptimal circumstances. The expression of the FUS1 gene (FUS1-lacZ), frequently used as a reporter to measure pathway activity, indicates the fMAPK pathway activation. This project focuses on the genetic phenomenon of suppressor mutations, where one or more secondary mutations restore the viability or fitness lost due to a primary mutation, a process known as a synthetic rescue. Suppression can reveal different functional routes or mechanisms and provide a better understanding of genetic network compensations. Specifically, the suppression in the ste4Δ strain was examined, where the yeast cannot grow due to the deletion of STE4, an essential activator of the fMAPK pathway. Ste4Δ strains can exhibit improved growth, suggesting the emergence of suppressor mutations that compensate for the deletion. Four strains (A2c3, E20c1, K49c1, and H35c2) exhibited medium levels of FUS1-LacZ expression and were investigated to understand their phenotype. The medium level of reporter gene activity indicates partial reactivation of the fMAPK pathway, likely due to suppressor mutations. The processes that allow the yeast to bypass the need for STE4 can be described by locating and characterizing these mutations, leading to a deeper understanding of the fMAPK pathway in _S. cerevisiae_.

The main steps of this project are: 
  1) Quality control the reads
  2) Trim and clean if required
  3) Remap onto reference genome (R64-1-1)
  4) Call the variants
  5) Annotate variants
  6) Filter for: variants in coding genes (exclude synonymous) found in max 2 strains.
  7) Identify possible suppressor mutation and the gene it affects.
