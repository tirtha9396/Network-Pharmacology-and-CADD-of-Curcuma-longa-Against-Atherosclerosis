# Network-Pharmacology-and-CADD-of-Curcuma-longa-Against-Atherosclerosis
## Project Overview

This project explores the potential molecular interactions of selected phytochemicals from *Curcuma longa* (turmeric) against atherosclerosis-associated targets using an integrated approach involving **network pharmacology and computer-aided drug design (CADD)**.

Atherosclerosis is a chronic inflammatory disease characterised by lipid accumulation, inflammation and plaque formation in arterial walls. Since multiple genes and biological pathways contribute to its development, network pharmacology can help explore the relationships between phytochemicals and disease-associated molecular targets.

Molecular docking was subsequently used to investigate the predicted interactions between selected phytochemicals and the IL-6 protein.

## Objectives

- Identify selected phytochemicals from *Curcuma longa*.
- Perform preliminary molecular property and toxicity screening.
- Collect compound-associated and atherosclerosis-associated target genes.
- Identify common genes and construct a protein–protein interaction network.
- Identify hub genes and relevant biological pathways.
- Perform molecular docking of selected compounds against IL-6.

## Selected Phytochemicals

1. Bisdemethoxycurcumin
2. Tetrahydrocurcumin
3. Germacrone

## Workflow

1. Phytochemical identification and screening.
2. Compound-target gene collection.
3. Atherosclerosis-related gene collection.
4. Common target identification using Venny 2.0.
5. PPI network analysis using STRING and Cytoscape.
6. Hub-gene analysis using CytoHubba.
7. KEGG pathway enrichment using ShinyGO.
8. Molecular docking using PyRx and AutoDock Vina.

## Key Findings

- **21 overlapping genes** were identified between the compound-associated target set and the atherosclerosis-associated gene set.
- **IL6** was highlighted as the leading hub gene in the analysed network.
- Relevant enriched pathways included:
  - Lipid and atherosclerosis
  - Fluid shear stress and atherosclerosis
  - PPAR signalling pathway

## Molecular Docking Results

The three selected phytochemicals were docked against the IL-6 protein.

| Compound | Predicted binding affinity |
| Germacrone | -6.3 kcal/mol |
| Bisdemethoxycurcumin | -6.2 kcal/mol |
| Tetrahydrocurcumin | -6.1 kcal/mol |

Germacrone showed the most negative predicted docking score among the three compounds. The small differences in scores should be interpreted cautiously and do not establish biological or therapeutic superiority.

## Tools and Resources

- IMPPAT
- GeneCards
- Venny 2.0
- STRING
- Cytoscape
- CytoHubba
- ShinyGO
- KEGG
- SwissADME
- ProTox
- Molsoft
- PyRx
- AutoDock Vina
- BIOVIA

## Project Outcomes

This project demonstrates an integrated computational workflow combining network pharmacology, bioinformatics, pathway enrichment and molecular docking to explore potential compound-target relationships in a complex disease.

## Limitations

This is an exploratory in-silico study. Predicted target associations, pathway enrichment and docking scores do not confirm direct binding, target inhibition or therapeutic efficacy. Experimental validation is required to establish biological relevance.

## Research Disclaimer

The compounds investigated in this project are not established treatments for atherosclerosis based on this computational study. The findings should be considered preliminary predictions rather than clinical evidence.

## Author

Biotechnology Student | Interested in Bioinformatics, Computational Biology and AI in Drug Discovery
