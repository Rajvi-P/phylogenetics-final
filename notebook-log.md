Background:
Yersinia pestis is infamous for causing plague, such as the Bubonic plague and the Justinian plague, killing millions.
Several whole genome sequnces of bacteria in the Yersinia pestis genus was collected from NCBI's Genbank.
Sequences collected were comprised of strains isolated from various regions of the world, including the US, China, and Madagascar.

--Asia:
----Yersinia pestis Antiqua CP009906.1 (central asia/ Justinian plague): https://www.ncbi.nlm.nih.gov/nuccore/CP009906.1?report=fasta
----Yersinia pestis Antiqua CP000308.1 (central asia/ Justinian plague): https://www.ncbi.nlm.nih.gov/nuccore/CP000308.1?report=fasta
----Yersinia pestis str. Pestoides B (central asia/ Justinian plague): https://www.ncbi.nlm.nih.gov/nuccore/CP010023.1
----Yersinia pestis biovar Microtus str. 91001 chromosome (central asia/ rodent plague): https://www.ncbi.nlm.nih.gov/nuccore/AE017042.1
----Yersinia pestis strain S19960127 chromosome (Xinjiang China/ 1996 plague): https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP045640.1
----Yersinia pestis strain Harbin35 chromosome (China/ 1947 plague): https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP009704.1
----Yersinia pestis strain KIM5 (Manchuria/ 1947 plague): https://www.ncbi.nlm.nih.gov/nuccore/CP009836.1
----Yersinia pestis KIM10+ (Manchuria/ 1946 pneumonia plague): https://www.ncbi.nlm.nih.gov/nuccore/NC_004088.1
----Yersinia pestis strain Java9 chromosome (Java, Indonesia/ rodent plague): https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP009996.1
----Yersinia pestis strain Nicholisk 41 chromosome (Russia/ 1941 bubonic plague): https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP009991.1

North America:
Yersinia pestis strain Shasta chromosome (california/ mountain lion pneumonic olague 1994): https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP009723.1
Yersinia pestis strain El Dorado chromosome (california/ 2000 bubonic plague): https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP009785.1
Yersinia pestis CO92 (new mexico/ 1992 pneumonic plague): https://www.ncbi.nlm.nih.gov/nuccore/AL590842.1
Yersinia pestis strain Dodson (Nevada/ 1976 ground squirrel): https://www.ncbi.nlm.nih.gov/nuccore/CP009844.1
Yersinia pestis strain Cadman chromosome (Canada/ 1952 pneumonicplague: https://www.ncbi.nlm.nih.gov/nuccore/CP016273.1

Unknown I:
Yersinia pestis strain I-2998: https://www.ncbi.nlm.nih.gov/nuccore/LYMR01000013.1
Yersinia pestis strain I-3244: https://www.ncbi.nlm.nih.gov/nuccore/LZNB01000015.1

Unknown M:
Yersinia pestis strain M-549: https://www.ncbi.nlm.nih.gov/nuccore/LQBA01000022.1
Yersinia pestis strain M-1770: https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP064122.2

Unknown C:
Yersinia pestis strain C-830 chromosome: https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP064127.1
Yersinia pestis strain C-792 chromosome: https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP064119.2

Africa:
Yersinia pestis strain PBM19 chromosome (Madagascar/ 2013 pneumonic plague: https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP009492.1
Yersinia pestis strain M-1484 (Madagascar/ bubonic plague): https://www.ncbi.nlm.nih.gov/nuccore/LQAV01000015.1

Unknown:
Yersinia pestis strain KM 567 chromosome: https://www.ncbi.nlm.nih.gov/nuccore/NZ_CP064120.1

--------------------------------------------------------------------------------------------------------------------------------------------
Goal:
Explore genomes to identify any shared genetic factors associated with virulence
--------------------------------------------------------------------------------------------------------------------------------------------
Step 1: Collect data
Completed 2/14- data received from NCBI's GenBank and found in the raw data folder.
Revised 2/19- grouped data into certain categories

Step 2: Quality control
Completed 2/14- data received in FASTA form

Step 3: Alignment
Complete due 12/21- using ClustalW
clustalw2 -ALIGN -INFILE=pestis-all.md -OUTFILE=pestis-all-aligned.md -OUTPUT=FASTA
Description: ClustalW is a software used for multiple sequence alignment of nucleotides.
             It is the most user friendly and performs quality alignments using progressive
             alignment methods.
Assumptions: all aligned sequences are evolutionarily related, rate of change in sequences is constant
Limitations: struggles to align distantly related sequences, takes very long to align big number of sequences
