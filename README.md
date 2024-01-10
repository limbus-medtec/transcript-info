# Transcript information for troubleshooting

The [varvis®](https://www.varvis.com) team often receives questions regarding the [HGVS](https://varnomen.hgvs.org/) notation of variants that are challenging to annotate because they are affected by alignment (mapping) 'gaps' between [RefSeq transcripts](https://www.ncbi.nlm.nih.gov/refseq/) and [reference genomes](https://www.ncbi.nlm.nih.gov/grc/human).

These gaps are one of the main reasons why bioinformatics tools may disagree with each other on predicted cDNA change, predicted protein change, or even exon count.

This repository provides lists RefSeq transcripts with mapping issues for specific transcript<->reference alignment versions. They allow to quickly check whether tools may disagree about a variant because of this issue, as a first step for troubleshooting.

## Overview

- [hg19 (GRCh37) RefSeq alignment 2022-03](./hg19/refseq-2022-03/)
- [hg38 (GRCh38) RefSeq alignment 2023-03](./hg38/refseq-2023-03/)

## How to contribute

If you find any issue regarding the transcript meta-data we provide, [please report it](https://github.com/limbus-medtec/transcript-info/issues).

## More details

More details on mapping gaps are given in the talk [_"Mind the gaps: Impact of transcript alignment on variant interpretation"_](https://www.youtube.com/watch?v=vLtuyRMIMoA) from the [varvis®  corporate satellite at ESHG 2022](https://www.varvis.com/ESHG-2022.html).
