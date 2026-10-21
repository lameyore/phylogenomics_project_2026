# Phylogenomic Analysis of *Carnobacterium* sp. from a Pleistocene Wolf

## Overview

This project investigates the evolutionary relationships of *Carnobacterium* sp. MAG 17681, reconstructed from the stomach metagenome of a Pleistocene wolf approximately 45,000 years old.

The study combines genome quality assessment, average nucleotide identity (ANI), ortholog identification, and phylogenomic analysis to investigate the relationship between the ancient MAG and its closest known relatives.

## Research question

Does *Carnobacterium* sp. MAG 17681 represent a distinct genomic lineage closely related to *Carnobacterium pleistocenium* FTR1ᵀ?

## Hypothesis

MAG 17681 represents a distinct genomic lineage closely related to *C. pleistocenium*. This relationship will be evaluated using comparative genomics and phylogenomic analysis based on single-copy orthologous genes.

## Preliminary results

- **Genome completeness:** 91.4%
- **Contamination:** 1.2%
- **Number of contigs:** 496
- **ANI to *C. pleistocenium* FTR1ᵀ:** approximately 94%
- **Preliminary phylogeny:** MAG 17681 clusters closely with *C. pleistocenium* FTR1ᵀ.
- **Bootstrap support:** 100 for the split separating this pair from the other sampled *Carnobacterium* taxa in the preliminary tree.
- **Orthology analysis:** 504 single-copy orthologous families identified using OrthoFinder for broader phylogenomic analysis.

The ANI result is below the commonly used 95–96% species-level reference range and suggests that MAG 17681 may represent a distinct species-level genomic lineage. This interpretation requires further investigation and cannot establish a new species on its own.

## Methods and tools

| Step | Tool | Purpose |
|---|---|---|
| Ortholog identification | OrthoFinder | Identify orthologous gene families |
| Sequence alignment | MAFFT | Align orthologous sequences |
| Alignment trimming | trimAl | Remove unreliable alignment regions |
| Concatenation | AMAS | Build a concatenated alignment |
| Phylogenetic inference | IQ-TREE | Infer a maximum-likelihood tree |
| Tree visualization | iTOL | Visualize and annotate phylogenies |

ANI and genome quality estimates are evaluated separately using the corresponding analysis outputs.

## Repository structure

- `data/` — documentation describing input data and accessions
- `scripts/` — analysis scripts
- `results/figures/` — selected figures
- `environment/` — software versions
- `docs/` — methods and additional documentation

## Reproducibility

The repository will document the software, parameters, and commands used for the analysis. Scripts for analyses that are still in progress will be identified as work in progress.

Large raw sequencing files and sensitive or restricted data are not included in this repository. Data accessions and availability will be added when confirmed.

## Project status

**In progress.** Preliminary ANI and phylogenetic results are available. A broader phylogenomic analysis based on single-copy orthologous genes is planned to evaluate the robustness of the preliminary topology.

## Acknowledgements

This project uses comparative genomic and phylogenomic approaches to study microbial diversity preserved in a Pleistocene sample.

## License

The repository license and reuse terms will be specified once the project’s data and code-sharing requirements have been confirmed.
