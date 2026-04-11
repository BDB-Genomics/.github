BDB Genomics
Accelerating discovery at the intersection of Big Data and Multi-omics.

Welcome to BDB Genomics, an open-source initiative dedicated to engineering robust, production-grade Snakemake pipelines for state-of-the-art epigenomic and transcriptomic analysis.

Our mission is to standardize next-generation sequencing workflows to guarantee reproducibility, scalability, and relentless quality control across all major cloud and HPC environments.

🧬 Our Core Pipelines
We maintain a suite of highly modular, perfectly synchronized Snakemake pipelines. Each workflow is governed by strict, isolated conda environments and automated intrinsic QC fast-failing.

atacseq-pipeline - Production-ready pipeline for ATAC-seq. Features automated gating on TSS Enrichment and FRiP.
cutandrun-pipeline - Modular CUT&RUN analysis workflow including SEACR peak calling and E. coli spike-in normalization.
chipseq-pipeline - Best-practices ChIP-seq data processing with deep quality control and MACS2 implementations.
rnaseq-pipeline - (In Development) Scalable transcriptomics quantification.
🚀 Why Use BDB Genomics?
Uncompromising Quality Control: We don't just generate reports. Our qc_gate.smk module actively halts runs if intrinsic sample quality falls below accepted biological thresholds.
Cross-Assay Modularity: The same fundamental filtering, trimming, and mapping rules are perfectly preserved across ATAC, RNA, and ChIP workflows.
Pre-flight Error Prevention: Integrated configuration validation ensures zero mid-pipeline crashes due to missing inputs or bad keys.
💬 Contact & Support
If you encounter bugs, require assistance, or have requests for new assay supports, please open an issue in the respective pipeline repository. We actively maintain and refine our tools to match evolving ENCODE and nf-core quality standards.

Standardized and Open-Source by BDB Genomics
