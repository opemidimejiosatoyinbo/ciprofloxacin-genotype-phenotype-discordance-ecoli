# Reproducibility materials

This repository accompanies the study:

**Beyond resistance-gene calling: a provenance-aware case study of ciprofloxacin genotype–phenotype discordance in African Escherichia coli**

**Author:** Opemidimeji Osatoyinbo  
**Affiliation:** Department of Microbiology, Faculty of Life Sciences, University of Ilorin, Ilorin, Nigeria  
**ORCID:** https://orcid.org/0009-0005-4431-3249

## Scope

This repository contains the compact, publication-facing reproducibility materials for a bounded secondary genomic case study of ciprofloxacin genotype–phenotype discordance in *Escherichia coli*. It does not redistribute raw sequencing data that are already available through public sequence archives.

The biological analysis was frozen before repository preparation. Repository preparation did not reopen candidate discovery, alter thresholds, change denominators, rerun association testing, or introduce causal claims.

## Scientific endpoint

The focal ciprofloxacin-resistant isolate (ID005) remained mechanistically unresolved by sequence data alone. Four ID005-specific substitutions in the *ompF* regulatory region and one coherent raw-read *qnrB* locus remained as sequence-level candidates, but neither system met the evidentiary threshold for causal assignment.

External contextualisation was descriptive only:

- *ompF* exact focal-allele recurrence: **0/5 callable isolates**, with CIP06 technically unresolved.
- *qnrB* raw-read signal: **0/2 technically evaluable isolates**, with CIP02–CIP05 technically unavailable.

Technical missingness is retained explicitly and is not converted to a biological negative.

## Repository contents

- `accessions.tsv` — focal, comparator and external-panel public accession linkage.
- `software/` — frozen software/database metadata used for reporting.
- `tables/` — final manuscript-facing and machine-readable tables.
- `figures/` — final figure exports and editable/vector sources.
- `supplement/` — publication-facing supplementary PDF.
- `reproducibility/` — compact claim/evidence/reporting registries. The local evidence-pack SHA256 file is intentionally excluded because it contains machine-specific absolute paths; repository integrity is instead covered by the portable root `MANIFEST_SHA256.txt`.
- `reporting/` — frozen claim, denominator, limitations and endpoint records.
- `provenance/` — compact authoritative-source registry and summary.
- `workflow/rules/` — frozen implementation-rule files defining the final analytical gates.
- `MANIFEST_SHA256.txt` — portable SHA256 integrity manifest.

## Why historical scripts are not included

The local project contains historical analytical scripts, exploratory branches, terminal executions and project-management code. A dedicated authority/linkage audit found no original analytical script with direct final-output name linkage sufficient to justify presenting it as the authoritative executable workflow. Those historical scripts are therefore retained in the private/local provenance archive rather than published as if they generated the final endpoint.

The public reproducibility layer instead preserves the frozen analytical rules, software/database versions, accession linkage, final evidence registries, tables, figures and supplementary material.

## Data access

All analysed sequence data originated from public resources. Durable accession identifiers are listed in `accessions.tsv`. Raw FASTQ, assembly FASTA, BAM/SAM and other large sequence-derived files are intentionally not redistributed here.

## Citation

A machine-readable citation is provided in `CITATION.cff`.

**Archived release (v1.0.0):**  
Osatoyinbo, O. (2026). *Reproducibility materials accompanying "Beyond resistance-gene calling: a provenance-aware case study of ciprofloxacin genotype–phenotype discordance in African Escherichia coli" (Version 1.0.0)* [Dataset]. Zenodo. https://doi.org/10.5281/zenodo.22644406

**Version-specific DOI:** https://doi.org/10.5281/zenodo.22644406

**All-versions DOI:** https://doi.org/10.5281/zenodo.22644405

The archived Zenodo v1.0.0 dataset corresponds to Git tag `v1.0.0`.

## Licence

Except where otherwise noted, original repository text, tables, figures and metadata created for this study are licensed under the Creative Commons Attribution 4.0 International licence (CC BY 4.0). Third-party sequence data, database content and referenced resources remain subject to their original terms and are not relicensed by this repository.
