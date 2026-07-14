# Oxford-Nanopore-Sequencing-Automated-Pipeline

Automated Oxford Nanopore RNA-Seq analysis pipeline for genome alignment and BLAST validation.

## Features

- Download SRA dataset
- Convert SRA to FASTQ
- NanoPlot quality control
- Adapter trimming using Porechop
- Alignment using Minimap2
- BAM sorting and indexing
- Alignment statistics
- Genome coverage
- BLAST database generation
- BLAST alignment

## Software

- SRA Toolkit
- NanoPlot
- Porechop
- Minimap2
- Samtools
- SeqKit
- BLAST+

## Usage

```bash
chmod +x ont_rnaseq_pipeline.sh

./ont_rnaseq_pipeline.sh
```

## Output

```
NanoPlot_raw/
NanoPlot_trimmed/
SRR33408712.bam
flagstat.txt
alignment.stats
coverage.txt
blast_results.tsv
```

## Citation

If you use this pipeline, please cite:

Li H. Minimap2...
Camacho et al. BLAST+...
