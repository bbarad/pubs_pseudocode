# Getting from start to finish for 1-pot EMPIRIC data analysis.
## Computational Project Summary (for part 1)
For the 2014 pubs class, the students will be tasked with identifying the 
changing levels of different mutants of Ubiquitin in a complex population. To 
this end, they will take timepoints along a growth curve and sequence those
timepoints to get the number of each barcode at each timepoint. The barcodes
have previously been associated with a single point mutation by Iggy. The task
for the students will be to associate their barcodes with changes over time in
codon and ultimately amino acid space.

## Converting codon space to amino acid space. 
The day one project for the students will be to convert the barcode coverage 
heatmap from codon to amino acid space. To this end, they will be given a pair 
of Pickle files. The first contains a dictionary relating barcodes to the 
position and codon they refer to. The second contains a dictionary which has a 
translation between codon space and amino acid space. The ultimate goal is to 
have a heatmap showing the number of barcodes in the library which read to each
amino acid at each position of Ubiquitin.