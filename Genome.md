# Whole Human Genome Sequencing Project

## Introduction

We have sequenced the CEPH1463 (NA12878/GM12878, Ceph/Utah pedigree) human genome reference standard on the Oxford Nanopore MinION using 1D ligation kits (450 bp/s) using R9.4 chemistry (FLO-MIN106).

Human genomic DNA from GM12878 human cell line (Ceph/Utah pedigree) was either purchased from Coriell - "DNA" - (cat no NA12878) or extracted from the cultured cell line - "cells".  As the DNA is native, modified bases will be preserved.

# Data reuse and license

We encourage the reuse of this data in your own analysis and publications which is released under the Creative Commons CC-BY license. Therefore we would be grateful if you would cite the reference below if you do.

# Citation

Miten Jain, Sergey Koren, Karen H Miga, Josh Quick, Arthur C Rand, Thomas A Sasani, John R Tyson, Andrew D Beggs, Alexander T Dilthey, Ian T Fiddes, Sunir Malla, Hannah Marriott, Tom Nieto, Justin O'Grady, Hugh E Olsen, Brent S Pedersen, Arang Rhie, Hollian Richardson, Aaron R Quinlan, Terrance P Snutch, Louise Tee, Benedict Paten, Adam M Phillippy, Jared T Simpson, Nicholas J Loman & Matthew Loose. Nanopore sequencing and assembly of a human genome with ultra-long reads. Nature Biotechnology doi: <a href="https://doi.org/10.1038/nbt.4060">doi:10.1038/nbt.4060</a>.

# Preprint

Miten Jain, Sergey Koren, Josh Quick, Arthur C Rand, Thomas A Sasani, John R Tyson, Andrew D Beggs, Alexander T Dilthey, Ian T Fiddes, Sunir Malla, Hannah Marriott, Karen H Miga, Tom Nieto, Justin O'Grady, Hugh E Olsen, Brent S Pedersen, Arang Rhie, Hollian Richardson, Aaron Quinlan, Terrance P Snutch, Louise Tee, Benedict Paten, Adam M. Phillippy, Jared T Simpson, Nicholas James Loman, Matthew Loose. Nanopore sequencing and assembly of a human genome with ultra-long reads. bioRxiv. doi: <a href="https://doi.org/10.1101/128835">https://doi.org/10.1101/128835</a>.

# rel6 (genomic DNA)

Since the initial release of Guppy basecalling improvements have continued as well as optimisations in file formats (the introduction of mutifast5 files ).

To this end, we have updated the data set to incorporate the latest basecalling improvements as well as file formats.

Earlier releases should now be considered deprecated and not representative of the current state-of-the-art for nanopore sequencing.

We consider rel6 to be a significant update and so are releasing these data as we did the original rel3&4 data flowcell by flowcell.

The total dataset is now:

* 53 flowcells
* 132,931,102,331 bases
* 15,666,888 reads
 
Data were basecalled using:
 * Guppy Version: ONT Guppy basecalling software version 2.3.8+498297c
 * config file: dna_r9.4.1_450bps_flipflop.cfg
 * model file: template_r9.4.1_450bps_large_flipflop.jsn
 
 
 Note: One run (FAB23716) generated using R9 has currently failed rebasecalling.
 
 
Fastq Data (gz) from the entire rel6 dataset is available here: [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/rel_6.fastq.gz)

A sequencing summary file for the entire dataset is available here: [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/rel_6_sequencing_summary.txt.gz)
 
 
Individual Flowcells of data can be downloaded below. These are complete with sequencing summary files and guppy logs. FastQ files are gzipped within the tar files.

The entire set of FastQ tar data can be downloaded by using the aws client and downloading from s3://nanopore-human-wgs/rel6/FastQTars/



 
## Recalled rel3:
 
| flowcell_id | reads   | bases         | Date     | Centre  | SampleType | Kit         | Pore | Links                                                                                            | 
|-------------|---------|---------------|----------|---------|------------|-------------|------|--------------------------------------------------------------------------------------------------| 
| FAB23716    |         |               | 14/07/16 | UBC     | DNA        | Rapid       | R9   | Data Not Available [FASTQ]()                                                      nnn            | 
| FAB39088    | 668,016 | 3,929,822,468 | 19/09/16 | Notts   | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB39088-288418386_Multi.tar)  | 
| FAB39075    | 477,495 | 3,014,355,946 | 20/09/16 | UBC     | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB39075-4246400039_Multi.tar) | 
| FAB39043    | 442,132 | 2,574,202,451 | 23/09/16 | Bham    | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB39043-3709921973_Multi.tar) | 
| FAB42706    | 431,694 | 2,434,471,643 | 12/10/16 | UBC     | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42706-4111103328_Multi.tar) | 
| FAB41174    | 117,140 | 739,850,920   | 13/10/16 | Bham    | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB41174-3976885577_Multi.tar) | 
| FAB42260    | 269,507 | 1,583,530,766 | 13/10/16 | UBC     | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42260-4177064552_Multi.tar) | 
| FAB42804    | 16,688  | 91,150,705    | 14/10/16 | Bham    | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42804-84744914_Multi.tar)   | 
| FAB42316    | 573,736 | 4,047,383,848 | 14/10/16 | Notts   | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42316-216722908_Multi.tar)  | 
| FAB42205    | 318,133 | 2,076,803,569 | 14/10/16 | Notts   | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42205-3573838535_Multi.tar) | 
| FAB42561    | 234,228 | 1,693,451,959 | 19/10/16 | Notts   | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42561-356443753_Multi.tar)  | 
| FAB42473    | 646,945 | 3,794,243,146 | 19/10/16 | UBC     | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42473-4179682758_Multi.tar) | 
| FAB42395    | 38,335  | 200,553,219   | 20/10/16 | Norwich | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42395-4178605061_Multi.tar) | 
| FAB42476    | 435,934 | 2,655,496,773 | 27/10/16 | UBC     | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42476-3843483077_Multi.tar) | 
| FAB42451    | 818,420 | 5,228,838,859 | 28/10/16 | Notts   | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42451-4239353418_Multi.tar) | 
| FAB42704    | 276,653 | 2,015,520,974 | 28/10/16 | UBC     | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42704-87746129_Multi.tar)   | 
| FAB42828    | 33,633  | 206,649,131   | 01/11/16 | Norwich | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42828-288548394_Multi.tar)  | 
| FAB42810    | 322,286 | 2,433,213,020 | 02/11/16 | Norwich | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42810-352384898_Multi.tar)  | 
| FAB42798    | 193,679 | 1,543,052,592 | 03/11/16 | Norwich | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB42798-3306352129_Multi.tar) | 
| FAB45280    | 128,314 | 895,679,449   | 11/11/16 | Norwich | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB45280-222619780_Multi.tar)  | 
| FAB46664    | 491,945 | 2,335,386,447 | 15/11/16 | UBC     | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB46664-288286712_Multi.tar)  | 
| FAB46683    | 72,713  | 447,658,919   | 17/11/16 | Bham    | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB46683-4246923067_Multi.tar) | 
| FAB45332    | 531,764 | 3,267,600,534 | 17/11/16 | UBC     | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB45332-551111640_Multi.tar)  | 
| FAB43577    | 427,215 | 2,776,702,333 | 18/11/16 | UCSC    | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB43577-3574887596_Multi.tar) | 
| FAB44989    | 558,539 | 3,962,530,064 | 18/11/16 | UCSC    | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB44989-2567311907_Multi.tar) | 
| FAF01169    | 339,948 | 3,196,399,021 | 22/11/16 | Bham    | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF01169-4245879798_Multi.tar) | 
| FAF01441    | 255,326 | 2,457,162,654 | 22/11/16 | Bham    | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF01441-3910073345_Multi.tar) | 
| FAB45277    | 336,653 | 3,287,605,917 | 22/11/16 | Notts   | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB45277-86567043_Multi.tar)   | 
| FAB45321*   | 299,306 | 2,817,977,026 | 22/11/16 | Notts   | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB45321-19064779_Multi.tar)   | 
| FAF01127    | 633,129 | 5,441,337,578 | 25/11/16 | Bham    | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF01127-353303576_Multi.tar)  | 
| FAF01132    | 719,983 | 6,269,018,010 | 25/11/16 | Bham    | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF01132-84868110_Multi.tar)   | 
| FAB49712    | 632,305 | 5,376,464,744 | 28/11/16 | Bham    | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB49712-622291475_Multi.tar)  | 
| FAF01253    | 471,792 | 4,034,085,735 | 28/11/16 | Bham    | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF01253-83756522_Multi.tar)   | 
| FAB45321*   | 123,061 | 1,123,014,497 | 28/11/16 | Notts   | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB45321-285174896_Multi.tar)  | 
| FAB49914    | 309,335 | 3,066,878,031 | 28/11/16 | Notts   | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB49914-3775529215_Multi.tar) | 
| FAB45271    | 467,701 | 3,959,651,805 | 28/11/16 | Notts   | Cells      | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB45271-152889212_Multi.tar)  | 
| FAB49164    | 747,060 | 4,997,920,867 | 06/12/16 | UCSC    | DNA        | Ligation    | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB49164-4045668814_Multi.tar) | 
| FAB49908    | 227,767 | 4,416,647,293 | 09/12/16 | Bham    | Cells      | Rapid       | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAB49908-481119249_Multi.tar)  | 
| FAF04090    | 94,833  | 2,337,803,872 | 09/12/16 | Bham    | Cells      | Rapid       | R9.4 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF04090-3842965088_Multi.tar) | 


## Recalled rel4:

| asic_id    | nreads  | mn     | count         | n50     | flowcell | centre | kit         | date       | sequence data                                                                                   | 
|------------|---------|--------|---------------|---------|----------|--------|-------------|------------|-------------------------------------------------------------------------------------------------| 
| 16056159   | 83,299  | 25,931 | 2,160,064,589 | 105,528 | FAF15665 | Notts  | Ultra       | 10/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF15665-16056159_Multi.tar)  | 
| 17958431   | 55,051  | 25,921 | 1,427,000,374 | 75,193  | FAF13748 | Notts  | Ultra       | 10/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF13748-17958431_Multi.tar)  | 
| 2901545329 | 43,709  | 24,578 | 1,074,279,009 | 60,128  | FAF10039 | Bham   | Ultra       | 01/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF10039-2901545329_Multi.tar)| 
| 3439856925 | 21,947  | 30,006 |  658,551,981  | 125,607 | FAF09968 | Bham   | Ultra       | 03/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF09968-3439856925_Multi.tar)| 
| 3709819546 | 78,080  | 28,651 | 2,237,071,487 | 118,062 | FAF09277 | Bham   | Ultra       | 03/06/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF09277-3709819546_Multi.tar)| 
| 3976726082 | 101,222 | 20,578 | 2,082,960,600 | 88,613  | FAF14035 | Notts  | Ultra       | 08/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF14035-3976726082_Multi.tar)| 
| 4109802543 | 63,850  | 27,303 | 1,743,301,488 | 103,541 | FAF15694 | Bham   | Ultra       | 06/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF15694-4109802543_Multi.tar)| 
| 4111860526 | 67,968  | 27,114 | 1,842,932,107 | 93,737  | FAF09713 | Bham   | Ultra       | 07/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF09713-4111860526_Multi.tar)| 
| 4178920553 | 272,029 | 11,060 | 3,008,840,150 | 25,583  | FAF18554 | UBC    | Rapid       | 06/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF18554-4178920553_Multi.tar)| 
| 4244782843 | 13,406  | 26,448 | 354,563,221   | 107,403 | FAF15630 | Notts  | Ultra       | 09/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF15630-4244782843_Multi.tar)| 
| 4245291640 | 77,481  | 22,319 | 1,729,363,584 | 89,354  | FAF09640 | Bham   | Ultra       | 07/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF09640-4245291640_Multi.tar)| 
| 4249180049 | 71,733  | 27,867 | 1,998,980,799 | 116,126 | FAF09701 | Bham   | Ultra       | 03/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF09701-4249180049_Multi.tar)| 
| 82266371   | 82,411  | 24,158 | 1,990,923,468 | 116,036 | FAF15586 | Bham   | Ultra       | 08/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF15586-82266371_Multi.tar)  | 
| 87644245   | 451,359 | 8,623  | 3,892,152,689 | 14,576  | FAF05869 | UBC    | Ligation    | 08/03/2017 | [FASTQ](http://s3.amazonaws.com/nanopore-human-wgs/rel6/FastQTars/FAF05869-87644245_Multi.tar)  | 


# rel5 (genomic DNA) *now deprecated*

rel5 was a merger of NA12878 DNA sequencing data from rel3 (regular sequencing protocols) and rel4 (ultra-read set), recalled with Albacore 2.1 and guppy 0.3.

## Notes on chunk size

Mike Schatz (Johns Hopkins) and Fritz Sedlazeck (CSHL) noticed that the Albacore 2.1 had a high frequency of long false positive deletions that were confounding SV prediction.  This was tracked down with the help of Chris Wright and Tim Massingham at ONT to the "chunk size" setting and the computation of signal scaling. Changing this value to 10000 should remove this problem and was performed for the Guppy calls.


## Reference

GRCh38 with decoys was used as the reference file: [GRCh38_full_analysis_set_plus_decoy_hla.fa](http://ftp.1000genomes.ebi.ac.uk/vol1/ftp/technical/reference/GRCh38_reference_genome/GRCh38_full_analysis_set_plus_decoy_hla.fa).


## Guppy

Data was downloaded from the ENA raw submission. Guppy was run on the GridION X5. Calling took approximately 48 hours on dual GPUs (1080 Ti), therefore basecalling speed was ~2.4Gb/hour.

### Downloads

   - <a href="https://s3.amazonaws.com/nanopore-human-wgs/rel5-guppy-0.3.0-chunk10k.fastq.gz">Guppy 0.3 gDNA dataset (10kb chunk size)</a>

Minimap2 alignments (``minimap2 -t 12 -ax map-ont -L GRCh38_full_analysis_set_plus_decoy_hla.fa``) and samtools 1.6 with new -L flag:

   - <a href="https://s3.amazonaws.com/nanopore-human-wgs/rel5-guppy-0.3.0-chunk10k.sorted.bam">BAM</a>, <a href="https://s3.amazonaws.com/nanopore-human-wgs/rel5-guppy-0.3.0-chunk10k.sorted.bam.bai">BAI</a>
   
   Please note that all fast5 files for this project are available from the European Nucletide Archive under the following project.
   
   - <a href="http://www.ebi.ac.uk/ena/data/view/PRJEB23027">PRJEB23027</a>

## Albacore 2.1

These basecalls are not recommended due to the above mentioned chunk size problem, but are
included for completeness.

### Downloads

   - <a href="http://s3.amazonaws.com/nanopore-human-wgs/NA12878-Albacore2.1.fastq.gz">Albacore 2.1</a>

Minimap2 alignments (``minimap2 -t 12 -ax map-ont -L GRCh38_full_analysis_set_plus_decoy_hla.fa``):

   - <a href="http://s3.amazonaws.com/nanopore-human-wgs/NA12878-Albacore2.1.sorted.bam">BAM</a>, <a href="http://s3.amazonaws.com/nanopore-human-wgs/NA12878-Albacore2.1.sorted.bam.bai">BAI</a>.

## Assembly

Adam Phillippy and Sergey Koren have posted a new [Canu 1.7 + WTDBG + Nanopolish](https://gembox.cbcb.umd.edu/triobinning/albacore_canu_wtdbg_nanopolish2.fasta) assembly using a dataset equivalent to the Albacore 2.1 reads above over on their [blog](https://genomeinformatics.github.io/na12878update/).

## Previous versions

For previous versions of data (rel3 and rel4), please go to: [rel_3_4](nanopore-human-genome/rel_3_4.md)

# Acknowledgements

We would like to acknowledge the support of Oxford Nanopore Technologies in generating this dataset, with particular thanks to Rosemary Dokos, Oliver Hartwell, Jonathan Pugh and Clive Brown. We would like to thank Radoslaw Poplawski and Simon Thompson for technical assistance with configuration and optimising of the CLIMB platform file system. We are grateful to Angel Pizarro and Jed Sundwall at Amazon Web Services for hosting this dataset as an <a href="https://aws.amazon.com/government-education/open-data/">AWS Open Data</a> set.

