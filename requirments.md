#readme.md for macs2Tutorial.zip file bundle

*Written by: Julie Pelletier, John Harada, Siobhan Brady, and Ciera Martinez* 

##Programs Needed to Run Tutorial 

####[MACS2](https://pypi.python.org/pypi/MACS2/2.0.10.09132012) 
written with version PIF4_macs2_peaks.xls

####Install MACS2

1.  Install pip
[http://www.pip-installer.org/en/latest/installing.html#install-or-upgrade-pip](http://www.pip-installer.org/en/latest/installing.html#install-or-upgrade-pip)

2. Installing MACS2 with one line command:
[https://github.com/taoliu/MACS/wiki/Install-macs2](https://github.com/taoliu/MACS/wiki/Install-macs2)

####[BEDTOOLS](http://bedtools.readthedocs.org/en/latest/) 
written with version 2.19.1

####[R-Studio](https://www.rstudio.com/) 
written with v0.98

##Bundle Contents

This is the bundle that contains all the files needed to run **Lab 4: Using Chromatin Immunoprecipitation – DNA Sequencing Data to Identify Genes Directly Regulated by Phytochrome Interacting Factors**, for BIS180L, Spring 2014. 

##Files in wetransfer-02a16b.zip (these are large):

    Col-0_ChiPSeq.bam 
    PIF4_ChIPSeq.bam 
    Athaliana_167.fa

##Required Files

fromStep1 directory contains files that are generated from command  `macs callpeak -t PIF4_ChiPSeq.bam -c Col-0_ChiPSeq.bam -n PIF4 -g 1.118e8 -q 0.05`

    fromStep1 
        PIF4_model.r
        PIF4_peaks.narrowPeak
        PIF4_peaks.xls
        PIF4_summits.bed

These are the files that are retrieved from TAIR.

    fromTAIR
        Ath.genome.txt
        TAIR10_genes.bed
        TAIR10_TSS.bed

These are the files that make up the tutorial.

    tutorial
        chipSeq_bis180l_2014.md
        chipSeq_bis180l_2014.pdf


