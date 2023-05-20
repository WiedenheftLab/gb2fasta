# gb2fasta

Author: Murat Buyukyoruk

Associated lab: Wiedenheft lab

        gb2fasta help:

This script is developed to fetch sequences from multifasta file by using a list of accession numbers to fetch. 

SeqIO package from Bio is required to fetch sequences. Additionally, tqdm is required to provide a progress bar since some multifasta files can contain long and many sequences.
        
Syntax:

        python gb2fasta.py -i demo.fasta 

seq_fetch dependencies:

	Bio module and SeqIO available in this package      refer to https://biopython.org/wiki/Download
	tqdm                                                refer to https://pypi.org/project/tqdm/
	
Input Paramaters (REQUIRED):
----------------------------
	-i/--input		Genbank		Specify a .gb file to convert into FASTA file 
	
Basic Options:
--------------
	-h/--help		HELP			Shows this help text and exits the run.

