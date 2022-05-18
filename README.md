## ReadMe

The repo contains the bioinformatic pipeline used to analyse amplicon data generated in the following study :

XXXXXXX


**Example data + scripts are provided in the example directory :**

- **adapters.fas** = sequencing adapters (Illumina)

- **fastq.gz files** = raw sequence data for 2 samples JRAS07930_0104 and JRAS07930_0105 (paired end sequencing 2*250 bp Illumina Miseq)

- **leuA_primers.txt** = possible combinations of forward+reverse specific primers

- **leuA_referenceDB.fas** = reference database composed of all leuA alleles available from [PubMLST](http://pubmlst.org/xfastidiosa/) (last access may 2022) + the synthetic target used in the study

- **mineamplicon.sh** = script to mine amplicon from raw data

- **trimprimer.sh** = script to trim primers from amplicon


**Expected outputs are provided in the outdir directory :**

- **leuA_allseqdef.fasta** = leuA sequences obtained from the 2 samples provided as examples (fasta format)

- **leuA_swarmselectremchimera_table** = final output table obtained for the 2 samples provided as examples (field separator = tab)


If you find something useful in there, please cite our paper ! Thanks :+1:
