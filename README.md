# Bioinformatics Stronghold Problems [Rosalind problems] 
### Note: All Projects are written in Python 3
#### These problems may not be in order as they appear on Rosalind. 
##### The point of these Bioinformatic problems is to implement my own algorithm or implement an existing one. <br /> For that reason, I am not using the Biopython package

**1st Project** - Count nucleotides (A, C, G, T) in a given DNA sequence. Must provide a sample.txt to read the nucleotides. 

**2nd Project** - Transcribe a DNA sequence into a RNA sequence. Must provide a sample.txt to read the DNA sequence. 

**3rd Project** - Find the reverse complement of a DNA sequence. This reverse complement is the non-coding strand while the DNA sequence is the coding strand. Must provide a sample.txt to read the DNA sequence.

**4th Project** - This is a bottom-up approach applied to a Dynammic Programming problem. The problem is called "Rabbits and Recurrence Relation." The project calculates the total number rabbits that are present after n months if every pair reproduction-age rabbits produce k litters. Reproduction age rabbits are ready to produce after the first month. Must provide n and k inputs.   

**5th Project** - Find number of point mutations given two DNA sequences where the second sequnce is right below the first one. Must provide a sample.txt where the first DNA sequence is on the first line and second one is right beneath it. 

**6th Project** - Calculate the dominant allele ratio given a population of k, m ,n. k represents the homozygous dominant organisms. m represent the heterozygous organisms, and n represents the homozygous recessive organisms. The population is given by k+m+n. The problem outputs a probability (decimal format) without replacement. 

**7th Project** - Translate a given RNA sequence into a peptide (peptide consists of one-letter amino acids). Must provide a sample.txt to read the RNA sequence. 

**8th Project** - Find the motif in a DNA sequence. Here, the motif acts as a pattern, and I am trying to find the locations at which the motif is a substring of the DNA sequence. I am using Knuth Morris Pratt algorithm since its performance is O(N). Must provide a DNA sequence and a motif beneath it. 

(Example taken from Rosalind as an illustration of the sample.txt should look like)

For example:

GATATATGCATATACTT <br />
ATAT

**9th Project** - Given at most 10 DNA strings in FASTA format. Return the label of the sequence, and the highgest GC content percentage (without the %). Must provide a sample.txt that at has at most 10 DNA strings in FASTA format.

**10th Project** - "Given a collection of at most 10 DNA strings of equal length (at most 1 kbp) in FASTA format. Returns a consensus string and profile matrix for the collection. (If several possible consensus strings exist, then you may return any one of them.)" The algorithm runs in polynomial run-time. Must give a sample.txt with the collection of at most 10 DNA strings of equal length
