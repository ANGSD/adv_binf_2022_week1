# Advanced Bioinformatics for Next-Generation Sequencing 2022: Week 1




Day | Time |  Subject | Lecturer
--- | --- | --- | ---
Day 1 - Monday | 9:15 - 12 | NGS data - Workflow, formats and programs | Thorfinn Sand Korneliussen
Day 2 - Tuesday | 13:15 - 16 | Mapping - Suffix arrays and Burrows-Wheeler Transform | Rasmus A. Henriksen
Day 3 - Friday | 9:15 - 12 | K-mers and metagenomic sequence classification | Abigail Ramsøe


# Getting started
## Connecting to the server via SSH


X11 forwarding method will allow you to start a graphical application on the remote system and forward this application's windows to your local system. We need to enable X11 forwarding to view the plots we will be generating for the exercises.

We use `-X` option to enable X11 forwarding over SSH:

```sh
$ ssh -X <your_username>@<server_name_or_ip>
```

Replace with your remote server username. For example:


```sh
$ ssh -X isin@emily.popgen.dk
```




## Setting up the working environment


If you are working on the emily server, all commands in the following seven exercises will be relative to the base directory called `/TEACHING/BIOINF23/adv_binf_2023_week1`

```sh
day1
├── data
│   ├── alignment
│   ├── fasta
│   ├── fastq
│   ├── reference_fasta
│   └── reference_fasta_hs37d5
├── exercises
│   ├── alignment_formats
│   ├── mapdamage
│   ├── trimming
│   └── variant_call_format
├── Makefile
└── README.md
```


