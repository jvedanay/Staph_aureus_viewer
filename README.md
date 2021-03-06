# Staph_aureus_viewer
A NYGC Hackathon Project to Create a JBrowse Viewer for Staph aureus genomes

The aim of this project is to develop a genome browser for Staphylococcus aureus genomes. NCBI genome database currently lists genome sequence data from 7968 stains, with varying degree of genome assembly qualities. 165 strains have near-complete whole-genome sequence, while a majority of sequences exist as either scaffolds (4711) or contigs (3086). Our genome browser pipeline aims to achieve the following goals:

1. Develop a pipeline to take fragmented scaffolds/contigs and identify the best complete genome sequence to assemble and visualize using Jbrowse

2. Annotate the newly assembled genome and visualize with Jbrowse

3. Predict orthologs and report recent gene duplications, reaarangements and other structural variation between Staphylococcus aureus strains


Dependencies:

pyfasta (https://pypi.python.org/pypi/pyfasta/)
