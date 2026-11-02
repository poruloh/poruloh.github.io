---
title: "Loh Lab - Research"
layout: textlay
excerpt: "Research"
sitemap: false
permalink: /research
---

## Research

We use computational techniques to study inherited and acquired genetic variation, primarily in human population cohorts such as [UK Biobank](https://www.ukbiobank.ac.uk) and [<i>All of Us</i>](https://www.nih.gov/allofus). Our work often involves developing statistical or algorithmic methods to detect subtle signals of latent genetic variants (e.g., tandem repeats, structural variants, and somatic variants) and their effects on human health. Many of our projects have arisen from collaborations with [Steve McCarroll](https://mccarrolllab.org)'s lab at Harvard Medical School, and we have also had fruitful collaborations with [Peter Park](https://compbio.hms.harvard.edu/)'s and [Chikashi Terao](https://c-teraolab.com)'s labs.

### Mosaic chromosomal alterations

<img src="images/research_pic_mosaic.jpg" style="width: 20%; float: right; margin: 0px 20px">

Cells throughout the human body accrue DNA mutations over the life course, such that every person is a “mosaic” of cells with slightly different DNA. Occasionally, mutations affect megabase-scale genomic regions or entire chromosomes, generating mosaic chromosomal alterations (mCAs). We have developed statistical methods to detect and study mCAs in biobank genomic data sets. These analyses have revealed ways in which inherited genetic variants influence mCA acquisition and clonal expansion. Our work has also implicated early developmental mCAs as a likely contributor to sporadic cases of autism spectrum disorder and refined the relationship between age-acquired hematopoietic mCAs and blood cancer risk.

* [Tang et al. <i>bioRxiv</i>][tang2027]
* [Si\*, Kamitaki\* et al. <i>medRxiv</i>][si2026]
* [Tang et al. 2026 <i>Nat Genet</i>][tang2026]
* [Sherman et al. 2021 <i>Nat Neurosci</i>][sherman2021]
* [Loh, Genovese, McCarroll 2020 <i>Nature</i>][loh2020]
* [Terao et al. 2020 <i>Nature</i>][terao2020]
* [Loh\*, Genovese\* et al. 2018 <i>Nature</i>][loh2018b]

### Tandem repeats

<img src="images/research_pic_repeats.png" style="width: 30%; float: right; margin: 0px 10px">

Human genomes contain millions of repeat elements at which a DNA motif appears multiple times in a row. Tandem repeats are prone to expansion and contraction and are among the most mutable of genomic elements. This leads to length variation between alleles inherited by different people as well as somatic expansion of unstable alleles within a person. We have developed computational techniques to assess inherited and acquired repeat length variation in biobank cohorts. This work has identified many repeats that confer disease risk or alter gene expression, and it has also found many genomic loci at which inherited variants influence somatic repeat instability.

* [Hujoel et al. 2026 <i>Nature</i>][hujoel2026]
* [Mukamel\*, Handsaker\* et al. 2023 <i>Cell</i>][mukamel2023]
* [Mukamel\*, Handsaker\* et al. 2021 <i>Science</i>][mukamel2021]

### Structural variants and rare coding variants

<img src="images/research_pic_SVs.png" style="width: 30%; float: right; margin: 0px 10px">

Genomic structural variants, including large insertions, deletions, and duplications of DNA, are the largest inherited variants in the human genome, yet are the hardest to “see” in population cohorts with short-read sequencing or SNP-array genotyping data. We have developed computational methods to genotype structural variants in such data sets using a variety of statistical techniques, particularly by leveraging haplotype-sharing within large cohorts. These approaches, which we have also applied to rare protein-coding variants, have identified common structural variants that underlie some of the strongest associations of genetic variation with human phenotypes and rare variants with large effects on health-related traits.

* [Kamitaki et al. 2024 <i>Nat Genet</i>][kamitaki2024]
* [Hujoel et al. 2024 <i>Nat Genet</i>][hujoel2024]
* [Hujoel et al. 2022 <i>Cell</i>][hujoel2022]
* [Barton et al. 2021 <i>Nat Genet</i>][barton2021]

### Other DNA phenotypes

<img src="images/research_pic_virome.png" style="width: 25%; float: right; margin: 0px 10px">

Whole-genome sequences of human biosamples commonly contain small amounts of non-human DNA. This is particularly true of saliva samples, for which ~10% of DNA is often derived from bacterial species present in the oral microbiome. Blood samples also contain trace amounts of DNA from common viruses resident in each person's blood system. We have studied inherited genetic influences on the oral microbiome and blood DNA virome in large human sequencing data sets, finding ways that human genetic variation interacts with microbial and viral variation. These genetic instruments have shed light on the extent to which epidemiological associations with disease phenotypes are causal.

* [Kamitaki et al. 2026b <i>Nature</i>][kamitaki2026b]
* [Kamitaki et al. 2026a <i>Nature</i>][kamitaki2026a]

### GWAS tools

<img src="images/research_pic_GWAS.jpg" style="width: 25%; float: right; margin: 0px 10px">

We have developed software tools that have been widely used in genome-wide association studies (GWAS). These include the [Eagle](https://alkesgroup.broadinstitute.org/Eagle) software for statistical haplotype phasing and the [BOLT-LMM](https://storage.googleapis.com/broad-alkesgroup-public/BOLT-LMM/BOLT-LMM_manual.html) software package for linear mixed model (LMM) association testing, heritability estimation (BOLT-REML), and phenotype prediction.

* [Loh et al. 2018 <i>Nat Genet</i>][loh2018a]
* [Loh et al. 2016b <i>Nat Genet</i>][loh2016b]
* [Loh et al. 2016a <i>Nat Genet</i>][loh2016a]
* [Loh et al. 2015b <i>Nat Genet</i>][loh2015b]
* [Loh et al. 2015a <i>Nat Genet</i>][loh2015a]



[tang27]: https://doi.org/10.64898/2026.10.27.760146
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
