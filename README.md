Scanning_for_CAZymes
====================

A simple Python script that implements a pipeline to translate, run an HMM for CAZymes and compile results


Dependencies : 

Download the following from : <http://csbl.bmb.uga.edu/dbCAN/download.php>
 
all.hmm.ps.len      dbCAN-fam-HMMs.txt.h3f  dbCAN-fam-HMMs.txt.h3m  hmmscan-parser.sh
dbCAN-fam-HMMs.txt  dbCAN-fam-HMMs.txt.h3i  dbCAN-fam-HMMs.txt.h3p  README.txt

Save to directory, then run dbCAN_HMM_Genomes.py to perform the annotation of CAZymes, followed by 
CAZy_compile_post_annotation.py to filter according to e-value and coverage and, if desired, tabulate according to CAZyme family.

