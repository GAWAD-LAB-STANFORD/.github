<div align="center">

<img src="https://raw.githubusercontent.com/GAWAD-LAB-STANFORD/.github/main/profile/assets/logo.png" alt="Gawad Lab" height="88">

# Gawad Lab

**Stanford Medicine · Department of Pediatrics**

### Creating biotechnologies that improve human health

We invent single-cell and cell-free genomics methods, then use them to understand how childhood cancers arise, evolve, and resist treatment — and to build faster, more accurate diagnostics.

[![Website](https://img.shields.io/badge/Website-gawadlab.org-8C1515?style=for-the-badge)](https://gawadlab.org)
[![Stanford Profile](https://img.shields.io/badge/Stanford-Charles_Gawad-2F5D70?style=for-the-badge)](https://profiles.stanford.edu/charles-gawad)
[![Contact](https://img.shields.io/badge/Contact-cgawad%40stanford.edu-F6A30C?style=for-the-badge)](mailto:cgawad@stanford.edu)

</div>

---

## What we build

Methods that read genomes, transcriptomes, and cell-free DNA at single-cell or single-molecule resolution, and the analysis code that makes sense of the result. Each row links to the papers that introduced or applied the tool.

| Tool type | What it does | Papers |
| :-- | :-- | :-- |
| **Single-cell whole-genome amplification (PTA)** | Primary template-directed amplification copies a single cell's genome uniformly enough to call point mutations, indels, and copy number in one cell; available commercially as ResolveDNA | [PNAS 2021](https://doi.org/10.1073/pnas.2024176118) · [Methods Mol Biol 2019](https://doi.org/10.1007/978-1-4939-9240-9_14) · [PLoS One 2014](https://doi.org/10.1371/journal.pone.0105585) · [Nat Rev Genet 2016](https://doi.org/10.1038/nrg.2015.16) |
| **Same-cell genome + transcriptome** | Paired DNA and full-length RNA readouts from the same cell, so a mutation can be tied to the cell state it produces; methylation and surface-protein layers are in development | [bioRxiv 2025](https://www.biorxiv.org/content/10.1101/2025.03.19.644196v2) |
| **Single-cell variant calling & clonal reconstruction** | Computational methods that separate true somatic variants from amplification artifacts and rebuild clonal trees, applied to leukemia through diagnosis, therapy, and relapse | [PNAS 2014](https://doi.org/10.1073/pnas.1420822111) · [BMC Genomics 2017](https://doi.org/10.1186/s12864-017-4286-1) · [Nat Genet 2024](https://doi.org/10.1038/s41588-024-01920-6) · [Sci Adv 2025](https://doi.org/10.1126/sciadv.adt3873) |
| **Cell-free DNA sequencing** | Plasma DNA assays that predict bloodstream infection before symptoms appear and track leukemia and microbes in the same sample | [JAMA Oncol 2020](https://doi.org/10.1001/jamaoncol.2019.4120) · [Sci Adv 2022](https://doi.org/10.1126/sciadv.abj1360) · [Lancet Microbe 2026](https://doi.org/10.1016/j.lanmic.2025.101312) |
| **Single-microbe genomics** | PTA adapted to single bacterial cells: near-complete genomes without culture | [ISME Commun 2024](https://doi.org/10.1093/ismeco/ycae085) |
| **Somatic-mosaicism detection** | Single-cell and deep-sequencing approaches that find mutations present in only a fraction of cells, from human neurons to inherited cardiac disease | [Nat Genet 2022](https://doi.org/10.1038/s41588-022-01180-2) · [PNAS 2016](https://doi.org/10.1073/pnas.1607187113) |
| **Single-cell atlases & exploration tools** | Transcriptional atlases of developing and malignant tissue, and interactive viewers for single-cell data ([CellSeek](https://gawadlab.github.io/CellSeek/)) | [Curr Biol 2018](https://doi.org/10.1016/j.cub.2018.07.062) · [Nature 2019](https://doi.org/10.1038/s41586-019-1434-6) · [Genome Med 2023](https://doi.org/10.1186/s13073-023-01241-z) |

Full list: [gawadlab.org/publications](https://gawadlab.org/publications.html) · [Google Scholar](https://scholar.google.com/citations?hl=en&user=Nbk0c_oAAAAJ)

## Code & pipelines

- [**basejumper-sherlock**](https://github.com/GAWAD-LAB-STANFORD/basejumper-sherlock) — run BioSkryb's open-source BaseJumper single-cell QC/variant pipelines on Stanford's Sherlock cluster (SLURM + Apptainer), with a container mirror on GHCR
- [**gawadlab.org**](https://github.com/GAWAD-LAB-STANFORD/gawadlab.org) — the lab website: plain HTML/CSS/JS, publications rebuilt from PubMed
- Analysis code and source data for each study are released with the paper; the lab's HPC pipelines (WGS/WES, RNA-seq, metagenomics, bacterial genomes) are being consolidated here from the cluster

---

<div align="center">
<sub>Biomedical Innovations Building · Stanford University School of Medicine · <a href="https://gawadlab.org">gawadlab.org</a></sub>
</div>
