# CattleSexChromosomesAssembly

Some custom scripts to analyse scaffolds and validate cattle sex chromosome assembly

chr-contigs-identification

This file contains codes for indentification of sex chromosome contigs from contig level assembly. the resources I used here are RH map markes downloaded from BovGen RH map,SUNbRH7000-rad map, USDA-MARC Bovine linkage Map and RH marrkers from Liu etal 2002.

processopticalmap-comparetoHiC

This file contains codes for Hi-C and optical map scaffolding comparisons. Hi-C scaffolds are longer than optical map scaffolds, but optical map can scaffold short and long contigs very well. 

checking-missingtranscript-fromX

We align the transcripts from ARSUCD-1.2 and Bos indicus 1.0 to our primary brahman X chromosome to checking ant protential X chormosome contigs we missed in primary assembly. 

XYalignments

Codes for cattle X/Y chromosome vs other X/Y chromosoem from other mammals using lastz.

process-par-otherspecies

We downloaded X chormosome annoation from reference genomesprocess and process them for  PAR genes comparison plots.

PARgenesplot-inmammals

We use the gff files we got from process-par-otherspecies to compared the PAR gene and plot the tracks using the gviz R package. 
