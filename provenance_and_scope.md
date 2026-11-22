# Documentation and provenance

**Source materials supplied by the project contributors:**
- `RNAseq3_presentation.pptx` (25-slide original project presentation)
- `RNAseq3.html` / HackMD notes (`RNAseq3`)
- `multiqc_report.html` (pipeline QC report)

## Included in this public portfolio

The `figures/` directory contains cropped images exported directly from slides **6, 14, 17, 18, and 21** of the original group presentation. No figures were recreated using estimated or generated data.

## What is not supplied

Raw FASTQ/BAM files, full nf-core output, full R/Bash scripts, internal cluster locations, and unrestricted input annotations. No complete reproduction is possible from this repository alone.

## Reproducibility note

The recorded run specifies **nf-core/rnaseq v3.14.0** with `star_rsem`, the Singularity profile, and downstream analysis in **edgeR** using `calcNormFactors`, `estimateDisp`, `glmQLFit` and `glmQLFTest`. The details in the course notes are not polished, validated scripts and should not be presented as a ready-to-execute workflow. The documented differential expression comparison used a tissue-only group model; the available work also explored both E14.5 and E15.5 samples.

## Ethics and data sharing

Before distributing original course presentations, code or underlying data, confirm permission from course collaborators and the data owner. The starter repository intentionally excludes large input/output files and source files that include internal computational paths and workstation details.
