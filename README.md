# Minervina et al. (eLife 2021) mild COVID-19 longitudinal TCRseq dataset
This repostitory contains procesed TCRalpha and TCRbeta repertoire datasets (and some results as well) for the paper by Minervina et al. on mild COVID-19,  [arxiv](https://arxiv.org/abs/2005.08290), [biorxiv](https://www.biorxiv.org/content/10.1101/2020.05.18.100545v3). 
The paper in now published in [eLife](https://elifesciences.org/articles/63502).

_Table_S1.tsv_ - list of libraries, with approx number of cells, number of UMIs and unique clonotypes. 

_Table_S2.tsv_ - HLA-typing results.

## Putatively COVID-19 reactive TCRbeta and TCRalpha sequences

_Table_S3.tsv_ - TCRbeta clonotypes _contracting_ from day 15 to day 85 post infection, for both donors, with frequencies in each timepoint.

_Table_S4.tsv_ - TCRalpha clonotypes _contracting_ from day 15 to day 85 post infection, for both donors, with frequencies in each timepoint.

_Table_S5.tsv_ - TCRbeta clonotypes _expanding_ from day 15 to day 37 post infection, for both donors, with frequencies in each timepoint.

_Table_S6.tsv_ -  TCRalpha clonotypes _expanding_ from day 15 to day 37 post infection, for both donors, with frequencies in each timepoint.

## Complete dataset
The complete processed repertoire data is available from zenodo in mixcr format:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3835955.svg)](https://doi.org/10.5281/zenodo.3835955)

## Raw data
The raw sequencing data is available at Short Read Archive acc. PRJNA633317.

## Raw data preprocessing instructions
(coming soon!)

## Old version (May 2020)

All SI tables for the initial version(v1) of preprint [biorxiv](https://www.biorxiv.org/content/10.1101/2020.05.18.100545v1) could be found in _old_version_ folder, see description below (note that contracting clones are defined as contracting from day 15 to day 45 in this version). 

### Putatively COVID-19 reactive TCRbeta and TCRalpha sequences
Two groups of TCR clones with active dynamics post-infection were identified for both donors: 

_contracting_ clones are clones contracting in the repertoire from day 15 to day 45 post-infection. 

_expanding_ clones go up from day 15 to day 37 post-infection. 

Both groups were identified with edgeR (FDR-adjusted p<0.01, log2FC threshold=2). Clone counts are given as in first replicate of PBMC on day 15 (for _contracting_) and day 37 (for _expanding_ group).
