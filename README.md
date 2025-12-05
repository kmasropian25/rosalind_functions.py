# DNA: Counting DNA Nucleotides
## Given: A DNA string s of length at most 1000 nt.
## Return: Four integers (separated by spaces) counting the respective number of times that the symbols 'A', 'C', 'G', and 'T' occur in s.
### (20, 12, 17, 21)
# RNA: Transcribing DNA into RNA
## Given: A DNA string t having length at most 1000 nt.
## Return: The transcribed RNA string of t.
### GAUGGAACUUGACUACGUAAAUU
# REVC: Complementing a Strand of DNA
## Given: A DNA string s of length at most 1000 bp.
## Return: The reverse complement sc of s.
### ACCGGGTTTT
# GC: Computing GC Content
## Given: At most 10 DNA strings in FASTA format (of length at most 1 kbp each).
## Return: The ID of the string having the highest GC-content, followed by the GC-content of that string. Rosalind allows for a default error of 0.001 in all decimal answers unless otherwise stated; please see the note on absolute error below.
### 53.75, 53.57142857142857, 60.91954022988506
# HAMM: Counting Point Mutations
## Given: Two DNA strings s and t of equal length (not exceeding 1 kbp).
## Return: The Hamming distance dH(s,t).
### 7
# PROT: Translating RNA into Protein
## Given: An RNA string s corresponding to a strand of mRNA (of length at most 10 kbp).
## Return: The protein string encoded by s.
### MAMAPRTEINSTRING
# SUBS: Finding a Motif in DNA
## Given: Two DNA strings s and t (each of length at most 1 kbp).
## Return: All locations of t as a substring of s.
### 2, 4, 10
# PRTM: Calculating Protein Mass
## Given: A protein string P of length at most 1000 aa.
## Return: The total weight of P . Consult the monoisotopic mass table.
### 821.3919199999999
# REVP: Locating Restriction Sites
## Given: A DNA string of length at most 1 kbp in FASTA format.
## Return: The position and length of every reverse palindrome in the string having length between 4 and 12. You may return these pairs in any order.
### [4, 6], [5, 4], [6, 6], [7, 4], [17, 4], [18, 4], [20, 6], [21, 4]
# TRAN: Transitions and Transversions
## Given: Two DNA strings s1 and s2 of equal length (at most 1 kbp).
## Return: The transition/transversion ratio R(s1,s2) .
### 1.2142857142857142
