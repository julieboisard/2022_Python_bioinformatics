* Project - from sequence to annotation. Combine what you have learned. Write a script or Jupyter notebook to help you annotate an unknown protein locally - that is, do not simply BLAST your sequence using BLAST online. Your workflow should include at least 4 of the following outputs:
    * The protein sequence in a fasta file
    * The taxonomy of the origin of the sequence
    * A small FASTA file of the top 50 related sequences from local database.
        * Challenge: consult the biopython cookbook on how to do a remote look up!
    * A table describing each of the top 50 related sequences. For e.g.,
        * Description of the sequence (annotation)
        * Length in amino acids
        * Organism, other taxonomy?
    * Multiple sequence alignment of your mystery sequence and the top 50 proteins - this should have reformatting FASTA headers for easy reading.
        * Challenge: Worried about identical sequences? Try installing ‘cd-hit’ in your conda environment and learning more about the tool..
    * Phylogenetic tree of these 50 proteins (keep the model simple)
        * Challenge: before making the alignment, think about what you would like in your Sequence names. Could taxonomy be helpful?
