# CRC
## Contents in local computer
<pre>
$ tree ChIP-seq/
ChIP-seq/
├── crup
│   ├── islets.HI-32.CRUP.clusterEnh.bed
│   ├── islets.HI-32.CRUP.prediction.bw
│   ├── islets.HI-32.CRUP.prediction.rds
│   └── islets.HI-32.CRUP.singleEnh.bedGraph
├── fastq
│   └── HM
│       ├── H3K27ac_HI-32.fq.gz
│       ├── H3K27ac_HI-45.fq.gz
│       ├── H3K4me1_HI-21.fq.gz
│       ├── H3K4me1_HI-25.fq.gz
│       ├── H3K4me1_HI-32.fq.gz
│       ├── H3K4me3_HI-21.fq.gz
│       ├── H3K4me3_HI-25.fq.gz
│       ├── H3K4me3_HI-32.fq.gz
│       └── unconcatnated
│           ├── H3K4me1_HI-21-lane1.fq.gz
│           ├── H3K4me1_HI-21-lane2.fq.gz
│           ├── H3K4me1_HI-25-lane1.fq.gz
│           ├── H3K4me1_HI-25-lane2.fq.gz
│           ├── H3K4me1_HI-32-lane1.fq.gz
│           ├── H3K4me1_HI-32-lane2.fq.gz
│           └── H3K4me1_HI-32-lane3.fq.gz
├── fastqc
│   └── HM
│       ├── H3K27ac_HI-32_fastqc.html
│       ├── H3K27ac_HI-32_fastqc.zip
│       ├── H3K27ac_HI-45_fastqc.html
│       ├── H3K27ac_HI-45_fastqc.zip
│       ├── H3K4me1_HI-21_fastqc.html
│       ├── H3K4me1_HI-21_fastqc.zip
│       ├── H3K4me1_HI-25_fastqc.html
│       ├── H3K4me1_HI-25_fastqc.zip
│       ├── H3K4me1_HI-32_fastqc.html
│       ├── H3K4me1_HI-32_fastqc.zip
│       ├── H3K4me3_HI-21_fastqc.html
│       ├── H3K4me3_HI-21_fastqc.zip
│       ├── H3K4me3_HI-25_fastqc.html
│       ├── H3K4me3_HI-25_fastqc.zip
│       ├── H3K4me3_HI-32_fastqc.html
│       └── H3K4me3_HI-32_fastqc.zip
├── mapping
│   ├── STAR
│   │   ├── regex_test.ipynb
│   │   ├── rmdup_bam
│   │   │   ├── H3K27ac_HI-32.bam
│   │   │   ├── H3K27ac_HI-32.bam.bai
│   │   │   ├── H3K27ac_HI-45.bam
│   │   │   ├── H3K27ac_HI-45.bam.bai
│   │   │   ├── H3K4me1_HI-21.bam
│   │   │   ├── H3K4me1_HI-21.bam.bai
│   │   │   ├── H3K4me1_HI-25.bam
│   │   │   ├── H3K4me1_HI-25.bam.bai
│   │   │   ├── H3K4me1_HI-32.bam
│   │   │   ├── H3K4me1_HI-32.bam.bai
│   │   │   ├── H3K4me3_HI-21.bam
│   │   │   ├── H3K4me3_HI-21.bam.bai
│   │   │   ├── H3K4me3_HI-25.bam
│   │   │   ├── H3K4me3_HI-25.bam.bai
│   │   │   ├── H3K4me3_HI-32.bam
│   │   │   └── H3K4me3_HI-32.bam.bai
│   │   └── unsorted_bam_logs
│   │       ├── H3K27ac_HI-32_Log.final.out
│   │       ├── H3K27ac_HI-32_Log.out
│   │       ├── H3K27ac_HI-32_Log.progress.out
│   │       ├── H3K27ac_HI-32_Log.std.out
│   │       ├── H3K27ac_HI-32_SJ.out.tab
│   │       ├── H3K27ac_HI-45_Log.final.out
│   │       ├── H3K27ac_HI-45_Log.out
│   │       ├── H3K27ac_HI-45_Log.progress.out
│   │       ├── H3K27ac_HI-45_Log.std.out
│   │       ├── H3K27ac_HI-45_SJ.out.tab
│   │       ├── H3K4me1_HI-21_Log.final.out
│   │       ├── H3K4me1_HI-21_Log.out
│   │       ├── H3K4me1_HI-21_Log.progress.out
│   │       ├── H3K4me1_HI-21_Log.std.out
│   │       ├── H3K4me1_HI-21_SJ.out.tab
│   │       ├── H3K4me1_HI-25_Log.final.out
│   │       ├── H3K4me1_HI-25_Log.out
│   │       ├── H3K4me1_HI-25_Log.progress.out
│   │       ├── H3K4me1_HI-25_Log.std.out
│   │       ├── H3K4me1_HI-25_SJ.out.tab
│   │       ├── H3K4me1_HI-32_Log.final.out
│   │       ├── H3K4me1_HI-32_Log.out
│   │       ├── H3K4me1_HI-32_Log.progress.out
│   │       ├── H3K4me1_HI-32_Log.std.out
│   │       ├── H3K4me1_HI-32_SJ.out.tab
│   │       ├── H3K4me3_HI-21_Log.final.out
│   │       ├── H3K4me3_HI-21_Log.out
│   │       ├── H3K4me3_HI-21_Log.progress.out
│   │       ├── H3K4me3_HI-21_Log.std.out
│   │       ├── H3K4me3_HI-21_SJ.out.tab
│   │       ├── H3K4me3_HI-25_Log.final.out
│   │       ├── H3K4me3_HI-25_Log.out
│   │       ├── H3K4me3_HI-25_Log.progress.out
│   │       ├── H3K4me3_HI-25_Log.std.out
│   │       ├── H3K4me3_HI-25_SJ.out.tab
│   │       ├── H3K4me3_HI-32_Log.final.out
│   │       ├── H3K4me3_HI-32_Log.out
│   │       ├── H3K4me3_HI-32_Log.progress.out
│   │       ├── H3K4me3_HI-32_Log.std.out
│   │       └── H3K4me3_HI-32_SJ.out.tab
│   ├── STAR_script
│   └── bowtie2
│       ├── H3K27ac_HI-32.sorted.bam
│       ├── H3K27ac_HI-32.sorted.bam.bai
│       ├── H3K27ac_HI-32.unsorted.bam
│       └── hg19
│           ├── hg19.1.bt2
│           ├── hg19.2.bt2
│           ├── hg19.3.bt2
│           ├── hg19.4.bt2
│           ├── hg19.fa
│           ├── hg19.rev.1.bt2
│           └── hg19.rev.2.bt2
├── multiqc
│   └── HM
│       ├── multiqc_data
│       │   ├── multiqc.log
│       │   ├── multiqc_citations.txt
│       │   ├── multiqc_data.json
│       │   ├── multiqc_fastqc.txt
│       │   ├── multiqc_general_stats.txt
│       │   └── multiqc_sources.txt
│       └── multiqc_report.html
└── stat_bam

16 directories, 110 files

</pre>

## TODOs
- [x] download fastq files from [E-MTAB-1919](https://www.ebi.ac.uk/arrayexpress/experiments/E-MTAB-1919/) and [E-MTAB-1294](https://www.ebi.ac.uk/arrayexpress/experiments/E-MTAB-1294/), 8 files in total
- [x] fastqc & multiqc
- [x] mapping with STAR
- [x] mapping with Bowtie2 (partially done)
- [x] CRUP - sample 32
- [x] CRUP - merged
- [ ] deeptools

## Tutorials
- [ChIP-seq dibsi2018 tutorial](https://angus.readthedocs.io/en/2019/chip-seq.html)
- [SAMTools](https://davetang.org/wiki/tiki-index.php?page=SAMTools)
- [Gene expression units explained: RPM, RPKM](https://www.reneshbedre.com/blog/expression_units.html)
- **[github:  Introduction to ChIP-seq using high performance computing](https://github.com/hbctraining/Intro-to-ChIPseq)**
- [Plasmids 101: The Promoter Region – Let's Go!](https://blog.addgene.org/plasmids-101-the-promoter-region)