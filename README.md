# RepFinder

> blastn to find repeats in a single or multiple sequences

> Designed to find shared repeats between mitochondrial genomes

# Requirements:

- [x] blastn in [BLAST+](ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/)

- [x] Python3: [biopython](https://biopython.org/)

# Options

```bash
repfinder.py [options] infile
```
Options

    infile                Input multifasta file: *.fasta


    -h, --help            Show this help message and exit

    --out <PREFIX>, -o <PREFIX>

                        Output prefix, default: MyOut

    --minlen <INT>, -m <INT>

                        Minimum length of matches to keep, default: 50

    --wordsize <INT>, -w <INT>

                        Word_size for blast, should <= -m, default: 28

    --dbfasta <FILE>, -f <FILE>

                        Optional: Repeat database in fasta format

    --identity 0-100    Percentage of identity, default: 90

    --reward <INT>      Reward for match, default: 1

    --penalty <INT>     Penalty for mismatch, default: -20

    --keep, -k          True to keep temp files

    --gbff              True to write GenBank GBFF format file

    --embl              True to write EMBL format file

    --gff3              True to write GFF3 format file

    --version           Display version

# Issues

> Please report any problem in the Issues part. And if you need any more function / option, do it there as well.

# Acknowledgements

- [x] This program was inspired by the script [ROUSfinder2](https://github.com/flydoc2000/ROUSfinder) and its [publication](https://doi.org/10.1534/g3.118.200948)

# Author:

    Fu-Hao Lu

    Professor, PhD

    State Key Labortory of Crop Stress Adaptation and Improvement

    College of Life Science

    Jinming Campus, Henan University

    Kaifeng 475004, P.R.China

    E-mail: LUFUHAO@HENU.EDU.CN
