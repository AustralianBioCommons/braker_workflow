# *GENEMARK-ES suite*

## Description
GENEMARK-ES suite is a gene prediction in Eukaryotes. The novel genomes can be analyzed by GENEMARK-ES which uses an algorithm utlitizing modles parameterized by unsupervised training.

# USAGE
GeneMark-ET takes FASTA and GFF3 file format as input.

* Usage:
  * gmes_petap.pl [options] --sequence [filename]

* GENERAL OPTIONS
	* see [link](https://wiki.gacrc.uga.edu/wiki/GeneMarkES-Teaching)

* Input  
  * a fasta file and gff3
* QUICK START 
  * Usage Example 
  	* gmes_petap.pl --sequence input.fasta --ET intron.gff --et_score
		* input.fasta = genomic sequence file in FASTA format
		* intron.gff = RNA-seq mapped intron coordinates in GFF format
		* et_score = the number of reads covering the intron region.

- More examples can be found in this link_.


## Link(s)
  * [GENEMARK-ES link](http://exon.gatech.edu/GeneMark/gmes_instructions.html)


## Diagram
   * Not Available

## Version notes
   * GENEMARK-ES/ET/EP versionn 4 or latest
   * [Download] (http://exon.gatech.edu/GeneMark/license_download.cgi)

## Installation
   * Copy the content of distribution to desired location.
   * Install the key: copy key "gm_key" into users home directory as:
   		cp gem_key ~/.gm_key
   * Program is ready for execution.
   * Default location of PERL is /usr/bin/perl

## Third party tools / dependencies
   * Perl scripts are configured with default Perl location at "/usr/bin/perl". Default path to Perl can be changed by script "change_path_in_perl_scripts.pl" from GeneMark* distribution folder.
   * The following Perl modules are required:
   	 * YAML
	 * Hash::Merge
	 * Logger::Simple
	 * Parallel::ForkManager

## Tutorials
   * Eukaryotic gene prediction using GeneMark.hmm-E and GeneMark-ES (https://europepmc.org/article/PMC/3204378)
   * GeneMark (http://topaz.gatech.edu/GeneMark/)

## Tool infrastructure requirements
   * To Be Investigated

### Scheduler
   * To Be Investigated

### Hardware
   * To Be Investigated

## Tool Install
   * Not available via Anaconda

## *Compute infrastructure name* optimisation (**LINK**)

## Help / FAQ / Troubleshooting

## Licence

## Acknowledgements / citations / credits
