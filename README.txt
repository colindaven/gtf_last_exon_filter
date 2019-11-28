@author Fabian Friedrich
@date 2019.10.09

This script was designed to facilitate comparisons between RNA-seq covering the whole gene body and 3 prime tag RNA-seq. This is not ideal, but if you can restrict the employed GTF to the last three exons in the input file for featureCounts you can reduce the effect of the different protocol.

filter_last_exon.py 
Takes only the last x exons of your file(Tested with Gencode.V31.basic.annotation only!)

for help just enter:
python3 filter_last_exon.py
