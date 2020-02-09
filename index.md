# How to preprocess miRNA-seq with FastQC and cutadapt

Aim: conduct research on miRNA 

Data: SRR .fastq directly from EBI 

The data also can be downloaded from NCBI-SRA, followed by type transform (from .SRA to .fasta/fastq); or Download with SRAtools.

[https://www.jianshu.com/p/cf0a7b937413]Reference

## FastQC / Fastp
Deal with miRNA sequence, Fastp tool can not detect adapters, which can be detected by FastQC. Here is an example.

Tips:
1.If you run FastQC with Linux command, run with file names; otherwise it will print errors

![Image](/1.png)

## Cutadapt
- Search for standard adapter sequence.


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
