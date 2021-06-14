# Predicting the subcellular location of proteins
## Motivation: 
The recent advances in technology and genome sequencing, has resulted in large availability of sequence
data and complete sequence has been determined for over 3000 genomes. As a consequence, the need for automated
and efficient methods for analyzing huge amounts of data is evident. Finding homology in the function of proteins is a
difficult task and a close approximation is to find the subcellular location of a protein and mapping its function. In this
paper, different machine learning algorithms have been experimented and results are discussed.

## Results: 
Ensemble methods performed the best compared to clustering, non-linear classifiers. Results emphasize the
Gradient Boosting classifier is able to effectively classify with a test accuracy of 66.7%.

## Problem:

The problem is defined as a classification task of categorizing eukaryotic proteins into one of 4 subcellular locations. These are:
1. Cytosolic - within the cell itself, but not inside any
organelles
2. Secreted - proteins which are transported out of a
cell
3. Nuclear - proteins found / used within the cell’s
nucleus
4. Mitochondrial - proteins transported to the cell’s
mitochondria

## Dataset:

The dataset consists of 9222 amino acids sequences for the
above four locations in the FASTA format (4) and 2002
amino acid sequences of prokaryotic proteins that
sometimes contaminate samples during sequencing. For
this exercise, only the 9222 amino acid sequences are
considered. FASTA as described in (4) is a text-based
format for representing either nucleotide sequences or
peptide sequences. These sequences are made of singleletter
codes which are either base pairs or amino acids. In
addition, a set of 20 blind sequences was provided to check
the overall performance in generalizing the sequences.
