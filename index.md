# How to preprocess miRNA-seq with FastQC and cutadapt

Aim: conduct research on miRNA 

Data: SRR .fastq directly from EBI 

The data also can be downloaded from NCBI-SRA, followed by type transform (from .SRA to .fasta/fastq); or Download with SRAtools.

[Reference](https://www.jianshu.com/p/cf0a7b937413)

## FastQC / Fastp
Deal with miRNA sequence, Fastp tool can not detect adapters, which can be detected by FastQC. Here is an example.

Tips:
1.If you run FastQC with Linux command, run with file names; otherwise it will print errors

![Image](/1.png)

## Cutadapt
- Search for standard adapter sequence, [Here](http://www.eurofinsgenomics.eu/media/1610545/illumina-adapter-sequences.pdf) is Illumina Adapter Sequence.

"TruSeq Small RNA"

1.RNA 5’ Adapter (RA5): 
5’ GUUCAGAGUUCUACAGUCCGACGAUC

2.**RNA 3’ Adapter (RA3)**: 
5’ TGGAATTCTCGGGTGCCAAGG

3.Stop Oligo (STP): 
5’ GAAUUCCACCACGUUCCCGUGG

4.RNA RT Primer (RTP): 
5’ GCCTTGGCACCCGAGAATTCCA

5.RNA PCR Primer (RP1): 
5’ AATGATACGGCGACCACCGAGATCTACACGTTCAGAGTTCTACAGTCCGA




- Run with -a parameter



```markdown
Syntax highlighted code block

### Cutadapt
- Search for standard adapter sequence.


- Run with -a parameter

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).



### Support or Contact

xzhangxmu@gmail.com
