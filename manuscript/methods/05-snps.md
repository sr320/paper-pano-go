<<<<<<< HEAD
<<<<<<< HEAD
@paolabatta Testing

Cpg
=======
SNPS
>>>>>>> origin/master
=======
SNPS

Single nucleotide polymorphisms were identified in the transcriptome using SAMTools (converting SAM into VCF files)


Steve's original suggestion:

One good place to start with SNPs is to take SAM file from Trinity assembly - https://github.com/sr320/paper-pano-go/wiki/Raw-Data#trinity-output  **is this after trimming?**

and use Samtools to create VCF file. See http://www.htslib.org/doc/samtools.html

trimmed files are not in sam format they are in fastqc format

next steps:
- Convert file to SAm format
- best way to work with big files i.e. SAM and how to link them to be analized by SAMtools
- get samtools to work either on my computer (pinaple?) or Cyverse)
>>>>>>> origin/master
