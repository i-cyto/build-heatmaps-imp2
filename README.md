# Build heatmaps of frequencies and median intensities for correct interpretations

## Overview

This repository accompanies the article entitled "Build heatmaps of frequencies and median intensities for correct interpretations" from [E. Lohmann](https://orcid.org/0000-0002-3230-8363), [L. Gorvel](https://orcid.org/0000-0001-7526-261X) and [S. Granjeaud](https://orcid.org/0000-0001-9245-1535), and submitted to "Immunophenotyping: Methods and Protocols, Second Edition" edited by Angélique Biancotto and Pradeep K. Dagur in the book series "Methods in Molecular Biology". The preprint is available at [bioRXiv]().

The aim is to understand the steps for building heatmaps of frequencies. Data files to start to follow the protocols are [here](output). Data originates from the study of [Michlmayr et al.](https://www.embopress.org/doi/full/10.15252/msb.20177862). They performed a 37-plex mass cytometry acquisition of peripheral blood mononuclear cells (PBMCs) of acute- and convalescent-phase samples obtained from 43 children naturally infected with chikungunya virus. Their analysis classified cells into 57 sub-communities of canonical leukocyte phenotypes and revealed a monocyte-driven response to acute infection, with the greatest expansions in "intermediate" CD14++CD16+ monocytes and an activated subpopulation of CD14+ monocytes. The FCS files and the attachments files are available on FlowRepository under id [FR-FCM-Z238](https://flowrepository.org/id/FR-FCM-Z238). We focused on the smallest subset of cell populations called "Assignment".


## Data files

* [output](https://github.com/i-cyto/build-heatmaps-imp2/tree/main/output) data files to __start the protocols__
* [input](https://github.com/i-cyto/build-heatmaps-imp2/tree/main/input) files for __01_extract_from_fcs_to_db__
* [extract](https://github.com/i-cyto/build-heatmaps-imp2/tree/main/extract) results from __01_extract_from_fcs_to_db__


## R scripts and reports

Extensive R scripts are available below as well as the preparation script.

1. [01_extract_from_fcs_to_db](01_extract_from_fcs_to_db.html) [Rmd](01_extract_from_fcs_to_db.Rmd)
2. [02_prepare_from_extraction.html](02_prepare_from_extraction.html) [Rmd](02_prepare_from_extraction.Rmd)
3. [03_mfis_to_heatmap.html](03_mfis_to_heatmap.html) [Rmd](03_mfis_to_heatmap.Rmd)
4. [04_counts_to_heatmap.html](04_counts_to_heatmap.html) [Rmd](04_counts_to_heatmap.Rmd)


## Contact

Contact us by mail or open an issue on the [repository](https://github.com/i-cyto/build-heatmaps-imp2/).
