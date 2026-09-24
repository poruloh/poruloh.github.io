---
title: "Loh Lab - Resources"
layout: textlay
excerpt: "Resources"
sitemap: false
permalink: /resources
---

## Resources

### Data sets

Summary statistics from genetic association analyses conducted by our group are available from the GWAS Catalog and/or [data.broadinstitute.org/lohlab](https://data.broadinstitute.org/lohlab), and individual-level derived data have been returned to data providers when possible. These data sets are summarized below; details are provided in each publication.
* [Tang et al. 2026 <i>Nat Genet</i>][tang2026]: Anonymized WGS-based mosaic chromosomal alteration calls in UK Biobank; summary statistics for GWAS, burden, and allelic shift association tests of CN-LOH mutations in <i>cis</i>; WGS read-depth PCs and REF-bias estimates.
* [Kamitaki et al. 2026b <i>Nature</i>][kamitaki2026b]: Viral DNA load GWAS summary statistics for UK Biobank and All of Us v8; individual-level viral load phenotypes for AoU participants.
* [Kamitaki et al. 2026a <i>Nature</i>][kamitaki2026a]: Oral microbial abundance and composition GWAS summary statistics for SPARK (WGS1-5); individual-level quantifications of microbial abundances in SPARK saliva samples.
* [Hujoel et al. 2026 <i>Nature</i>][hujoel2026]: Somatic repeat-expansion GWAS and PheWAS summary statistics for UK Biobank.
* [Hujoel et al. 2024 <i>Nat Genet</i>][hujoel2024]: Coding CNV-phenotype association statistics for WES-derived CNV calls with 57 quantitative phenotypes in UK Biobank.
* [Mukamel\*, Handsaker\* et al. 2023 <i>Cell</i>][mukamel2023]: VNTR-phenotype association statistics for WGS-imputed VNTRs with 668 phenotypes in UK Biobank.
* [Hujoel et al. 2022 <i>Cell</i>][hujoel2022]: CNV-phenotype association statistics for SNP-array-derived CNVs with 56 quantitative phenotypes in UK Biobank.
* [Mukamel\*, Handsaker\* et al. 2021 <i>Science</i>][mukamel2021]: Coding VNTR-phenotype association statistics for WES-imputed VNTRs with 787 phenotypes in UK Biobank.
* [Barton et al. 2021 <i>Nat Genet</i>][barton2021]: Rare coding variant associations for WES-imputed variants with 54 quantitative traits in UK Biobank.
* [Sherman et al. 2021 <i>Nat Neurosci</i>][sherman2021]: Mosaic chromosomal alterations detected from SNP-array data for SSC and SPARK.
* [Loh, Genovese, McCarroll 2020 <i>Nature</i>][loh2020]: Individual-level SNP-array-based mosaic chromosomal alteration calls in UK Biobank.
* [Terao et al. 2020 <i>Nature</i>][terao2020]: Individual-level SNP-array-based mosaic chromosomal alteration calls in BioBank Japan.
* [Loh et al. 2018 <i>Nat Genet</i>][loh2018a]: GWAS summary statistics for 46 phenotypes in UK Biobank.

### Software

* [mCAs_WGS](https://github.com/tangdavid/mCAs_WGS) pipeline for calling mosaic chromosomal alterations from WGS data ([Tang et al. 2026 <i>Nat Genet</i>][tang2026]).
* [extractLongSTRs](https://github.com/poruloh/extractLongSTRs) tool for efficiently extracting sequencing reads with high repeat content from WGS cram/bam files; other STR analysis pipelines used in [Hujoel et al. 2026 <i>Nature</i>][hujoel2026] at [https://github.com/mhujoel/STRs](https://github.com/mhujoel/STRs).
* [HI-CNV](https://data.broadinstitute.org/lohlab/HI-CNV/HI-CNV_manual.html) software for calling CNVs from SNP-array genotyping probe intensity data using a haplotype-informed approach in large cohorts ([Hujoel et al. 2022 <i>Cell</i>][hujoel2022]).
* [Eagle](https://alkesgroup.broadinstitute.org/Eagle/Eagle_manual.html) software for estimating haplotype phase either using a phased reference panel or within a genotyped cohort ([Loh et al. 2016b <i>Nat Genet</i>][loh2016b] + [Loh et al. 2016a <i>Nat Genet</i>][loh2016a]).
* [BOLT-LMM](https://alkesgroup.broadinstitute.org/BOLT-LMM/BOLT-LMM_manual.html) software for linear mixed model (LMM) association testing ([Loh et al. 2015a <i>Nat Genet</i>][loh2015a] + [Loh et al. 2018 <i>Nat Genet</i>][loh2018a]), heritability estimation (BOLT-REML; [Loh et al. 2015b <i>Nat Genet</i>][loh2015b]), and phenotype prediction.
* [ALDER](https://cb.csail.mit.edu/alder) software for computing weighted linkage disequilibrium (LD) curves, which can be used to infer admixture parameters including dates, mixture proportions, and phylogeny ([Loh*, Lipson* et al. 2013 <i>Genetics</i>][loh2013]).
* [MixMapper](http://groups.csail.mit.edu/cb/mixmapper/) software for analyzing allele frequency correlations among multiple populations simultaneously to build a tree (or “admixture graph”) of population relationships that incorporates the possibility of mixture ([Lipson*, Loh* et al. 2013 <i>Mol Biol Evol</i>][lipson2013]).

[si2026]: https://doi.org/10.64898/2026.09.08.26362505
[tang2026]: https://www.nature.com/articles/s41588-026-02592-0
[kamitaki2026b]: https://doi.org/10.1038/s41586-026-10288-y
[kamitaki2026a]: https://doi.org/10.1038/s41586-025-10037-7
[hujoel2026]: https://doi.org/10.1038/s41586-025-09886-z
[kamitaki2024]: https://doi.org/10.1038/s41588-024-01841-4
[hujoel2024]: https://doi.org/10.1038/s41588-024-01684-z
[mukamel2023]: https://doi.org/10.1016/j.cell.2023.07.002
[hujoel2022]: https://doi.org/10.1016/j.cell.2022.09.028
[mukamel2021]: https://www.science.org/doi/10.1126/science.abg8289
[barton2021]: https://www.nature.com/articles/s41588-021-00892-1
[sherman2021]: https://www.nature.com/articles/s41593-020-00766-5
[loh2020]: https://www.nature.com/articles/s41586-020-2430-6
[terao2020]: https://www.nature.com/articles/s41586-020-2426-2
[loh2018b]: https://doi.org/10.1038/s41586-018-0321-x
[loh2018a]: https://doi.org/10.1038/s41588-018-0144-6
[loh2016b]: http://dx.doi.org/10.1038/ng.3679
[loh2016a]: http://dx.doi.org/10.1038/ng.3571
[loh2015b]: http://dx.doi.org/10.1038/ng.3431
[loh2015a]: http://dx.doi.org/10.1038/ng.3190
[loh2013]: http://www.genetics.org/content/193/4/1233.full
[lipson2013]: http://mbe.oxfordjournals.org/content/30/8/1788.full
