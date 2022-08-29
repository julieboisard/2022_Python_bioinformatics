

# Introduction to python programming and bioinformatics

September 26-30, 2022 - Week 39

Course leader: Sara Behnamian & Julie Boisard (Dept. of Biology, Lund University)

sara.behnamian@biol.lu.se
julie.boisard@biol.lu.se


## Location and Time

We will meet from 9-16 with breaks around 1030 and 1430.

All meetings will be held in the B and D Houses of the Biology Building located on Sölvegatan 35. We suggest entering the building from the main entrance on the south side of the building (facing the new LTH tram stop). Once inside, you are on the ‘second floor’ (floor 2), turn left to access the B and D houses. https://maps.app.goo.gl/GDTBdNb1kQpW2FDo8

* B327 Syndpunkten - Conference room on the third floor of House B
* D227 Retina - Second floor of House D
* D107 Etiketten - First floor of House D

For lunch, there is a canteen in the Ecology House that will be open. There are also multiple lunchrooms we will have access to with microwaves.


## Format & Evaluation

We think that coding is best learned by doing!
Therefore there will be very few formal ‘lecturers’ in this course.
Instead, we will have guided exercises and tutorials ending in a mini-project for you to complete to apply what you learned.
Attendance in mandatory each day to receive credits (3 hp). Evaluation is pass/fail based on participation and completion of the exercises.  


## Schedule at a glance


### Day1: September 26th 2022

Room ???

Morning (Julie)

* Personal introductions
* Introduction to Jupyter Lab
* Basic python tutorial
* Code Discussion
* Debugging exercises
* Hand-in exercises

Afternoon (Sara)

*
*
*
*
*

### Day2: September 27th 2022

Room ???

Morning (Sara)

*
*
*
*

Afternoon (Julie)

* Databases and how to interact with them
* Tour of online databases (EggNOG, NCBI, PFAM, Interpro)
* Local installation of databases
* Local BLAST


### Day3: September 28th 2022

Room ???

Morning (Julie)

* Introduction to biopython
* Biopython - build a fasta parser
* Biopython - e-utilities (API)
* Exercises
* Code discussion

Afternoon (Sara)
*
*
*
*


### Day4: September 29th 2022

Room ???

Morning (Sara)
*
*
*
*


Afternoon (Julie)
* Matplotlib
* Exercices
* Code discussion
* Useful tools: alignment and phylogeny
* Exercices
* Exam Prep


### Day5: September 30th 2022

Room ???

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
