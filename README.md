
<!-- README.md is generated from README.Rmd. Please edit that file -->

<div style="margin-top: 5px;">

<img src="man/figures/hex.jpg" align="right" width="150"/>

</div>

## <span style="font-size:60px;">`sceptre`</span>

`sceptre` is an R package for single-cell CRISPR screen data analysis,
emphasizing statistical rigor, massive scalability, and ease of use.

<!-- badges: start -->

[![R-CMD-check](https://github.com/Katsevich-Lab/sceptre/workflows/R-CMD-check/badge.svg)](https://github.com/Katsevich-Lab/sceptre/actions)

<!-- badges: end -->

## v0.10.0: `sceptre` at massive scale

`sceptre` v0.10.0 represents another a major upgrade to the `sceptre`
software. We have integrated `sceptre` with
[`ondisc`](https://timothy-barry.github.io/ondisc/), a companion R
package that facilitates large-scale computing on single-cell data.
`sceptre` now supports the analysis of single-cell CRISPR screen data
out-of-core on a laptop or distributed across hundreds of processors on
a computing cluster or cloud.

`sceptre` v0.10.0 includes the following updates:

- Support for disk-backed `sceptre` objects, enabling the analysis of
  data too large to fit in memory
- A `sceptre` [Nextflow
  pipeline](https://github.com/timothy-barry/sceptre-pipeline), enabling
  the deployment of `sceptre` across hundreds of processors on a cluster
  or cloud
- An updated [e-book](https://timothy-barry.github.io/sceptre-book/)
  containing new sections about at-scale `sceptre` and the statistical
  methodology underlying `sceptre`
- New functionality for plotting and inspecting gRNA-to-cell assignments
- A comprehensive suite of unit tests, helping to verify the correctness
  of the code
- More detailed man pages (including a runnable example for each) and
  minor bug fixes

## Featured publications

- [Barry et al.,
  2024+](https://www.biorxiv.org/content/10.1101/2023.05.15.540875v2).
  “Robust differential expression testing…”. *Genome Biology*.
- [Barry et al., 2024+](https://arxiv.org/abs/2201.01879). “Exponential
  family measurement error models…”. *Biostatistics.*
- [Morris et al.,
  2023](https://www.science.org/doi/10.1126/science.adh7699). “Discovery
  of target genes and pathways…”. *Science*.
- [Barry et al.,
  2021](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02545-2).
  “SCEPTRE improves calibration and sensitivity…”. *Genome Biology*.

`sceptre` also recently was featured in a [10x
Genomics](https://www.10xgenomics.com/analysis-guides/single-cell-crispr-screen-analysis-with-sceptre)
analysis guide.

## Bug reports, feature requests, and software questions

For bug reports, please open a [GitHub
issue](https://github.com/Katsevich-Lab/sceptre/issues). For feature
requests, please start a discussion under [feature
requests](https://github.com/Katsevich-Lab/sceptre/discussions/categories/feature-requests).
For questions about `sceptre` functionality, documentation, or how to
apply it to your data, please start a discussion under
[Q&A](https://github.com/Katsevich-Lab/sceptre/discussions/categories/q-a).
