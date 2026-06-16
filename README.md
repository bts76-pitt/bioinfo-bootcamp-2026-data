# Bioinformatics Bootcamp 2026 — Data

Pre-baked artifacts for the "Dissecting a Tumor's Ecosystem" Colab lesson.

- `signature_matrix.csv` — 349 marker genes × 7 cell-type lineages (from Xu et al. 2024 Primary Breast Tumor Atlas)
- `atlas_umap.csv.gz` — 20,424 single cells: UMAP coords + cell type + 14 panel genes
- `tcga_brca_bulk.csv` — TCGA-BRCA bulk expression (CP10K), lesson gene subset × 1,092 patients (via UCSC Xena)
- `tcga_brca_clinical.csv` — patient → subtype (882 IDC / 210 ILC)

All derived from public data (Xu atlas, TCGA). For teaching use.
