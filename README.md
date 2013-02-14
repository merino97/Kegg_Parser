Kegg_Parser
===========

KEGG is a database resource for understanding high-level functions and utilities of the biological system, 
such as the cell, the organism and the ecosystem, from molecular-level information, 
especially large-scale molecular datasets generated by genome sequencing and other 
high-throughput experimental technologies.  

This program takes in ec numbers and species names in the form:

HSA 1.1.1.25  1.1.1.30

where the first value is the speacies name followed by ec numbers.  The program takes those ec numbers and builds 
the proper url's from them example:
Convert kegid to uniprot
http://rest.kegg.jp/conv/UniProt/hsa:259230

Obtaining the AA sequence info
http://rest.kegg.jp/get/hsa:166929/aaseq

Obtaining the NT sequence info
http://rest.kegg.jp/get/hsa:166929/ntseq

The results from the api calls are stored in 3 text files. 