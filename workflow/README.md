# Frozen workflow rules

This directory contains the final implementation-rule files copied from the frozen Paper 1 provenance set.

They define the analysis gates used for reporting, including mapping/depth quality control, comparator-aware copy-number screening, targeted minor-allele screening, local structural-context assessment, acquired quinolone discrimination, paired-read *qnrB* context evaluation, and external *qnrB*/*ompF* contextualisation.

These files are documentary records of the frozen analysis. They are not newly generated code and repository preparation did not rerun the biological analysis.

Historical analytical scripts are intentionally excluded because provenance audits did not establish direct final-output linkage sufficient to present any original script as the authoritative executable workflow.


## Portability note

The local file `Paper1_ID005_manuscript_evidence_pack_sha256_v1.txt` is not copied into the public repository because its checksum entries contain machine-specific absolute paths. Excluding that local manifest does not remove scientific evidence: the underlying claim/evidence/reporting files are retained, and the public repository generates a new portable root `MANIFEST_SHA256.txt` after staging.
