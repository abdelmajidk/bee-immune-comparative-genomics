# Comparative Immune Genomics and Genomic Organization of Immune-Related Genes in Four Bee Species

This repository accompanies a comparative genomics study of putative immune-related genes in four bee species:

- *Megachile rotundata* — solitary alfalfa leafcutting bee
- *Apis mellifera* — highly eusocial honey bee
- *Bombus terrestris* — primitively eusocial bumblebee
- *Bombus impatiens* — primitively eusocial bumblebee

## Study overview

The study integrates protein annotation, conserved-domain evidence, immune-associated protein-family classification, and orthogroup analysis to investigate similarities and differences in computationally identified immune-related gene repertoires.

A separate analysis of *M. rotundata* examines the genomic distribution of immune-related annotations, including sequence-level enrichment, local gene proximity, genomic gene spans, and GC fractions.

An unusual FANCM–serpin-associated protein annotation is also evaluated using comparative orthology, conserved domains, and genomic gene-structure evidence.

## Analytical datasets

The study distinguishes three related but nonidentical datasets:

| Dataset | Records | Description |
|---|---:|---|
| Original comparative inventory | 230 | Annotation-screened immune-related protein candidates across four species |
| Consolidated comparative inventory | 231 | Original candidates plus one supplementary evidence-supported protein record |
| *M. rotundata* genomic organization dataset | 105 | Independently selected immune-related gene annotations among 10,500 protein-coding genes |

The consolidated comparative inventory includes 36 refined protein families and 83 immune-associated orthogroups.

These are computational candidate inventories, not exhaustive collections of experimentally validated immune genes.

## Research objectives

1. Compare immune-related protein-family representation across four bee species.
2. Examine orthogroup membership and distinguish candidate-selection gaps from gene absence.
3. Characterize the genomic distribution and local proximity of immune-related annotations in *M. rotundata*.
4. Compare genomic gene spans and GC fractions between immune-related and background genes.
5. Evaluate unusual predicted protein architectures using complementary genomic evidence.

## Reproducibility and archive scope

This version 1.0.0 archive preserves the original repository and adds the six consolidated supplementary workbooks. The notebooks contain original local paths and require adaptation to a new computing environment. The archive includes derived data and execution logs, not the complete raw genome, representative proteome, OrthoFinder or InterProScan outputs. No end-to-end execution is asserted.

## Genome resources

NCBI RefSeq assemblies (author-reported download date: 2026-11-04):

| Species | Assembly | RefSeq | GenBank |
|---|---|---|---|
| Megachile rotundata | iyMegRotu1 | GCF_050947335.1 | GCA_050947335.1 |
| Apis mellifera | Amel_HAv3.1 | GCF_003254395.2 | GCA_003254395.2 |
| Bombus terrestris | iyBomTerr1.2 | GCF_910591885.1 | GCA_910591885.2 |
| Bombus impatiens | BIMP_2.2 | GCF_000188095.3 | GCA_000188095.4 |

Exact annotation releases and analytical input filenames remain incompletely documented; full reproducibility is not claimed.

## Supplementary tables

Use `supplementary/consolidated_tables/` for the six manuscript workbooks. The original twelve CSV tables and historical manifests remain unchanged for provenance. Original S1–S2 map to consolidated S1; S3–S4 to S2; S5 to S3; S6–S7 to S4; S8–S9 to S5; S10–S12 to S6.

## Citation and licensing

GitHub: https://github.com/abdelmajidk/bee-immune-comparative-genomics

Version-specific DOI: https://doi.org/10.5281/zenodo.24540935.

All-versions DOI: https://doi.org/10.5281/zenodo.24540934.

Cite: Kassem, M. A. (2026). *Supporting Data and Computational Workflows for Comparative Genomics of Immune-Related Genes in Four Bee Species* (Version 1.0.0) [Dataset]. Zenodo. https://doi.org/10.5281/zenodo.24540935.

License selected for original research data and documentation: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), subject to the depositor confirming rights before publication. Third-party materials retain their original terms. No separate software license is asserted.

## Archival version 1.0.0

See `docs/archive_preparation/DEPOSIT_GUIDE.md` for deposit metadata and remaining release checks, `DATA_DICTIONARY.md` for core datasets, and `SHA256SUMS.txt` for archive integrity. Historical manifests describe earlier workflow outputs and are not the checksum manifest for this release.
