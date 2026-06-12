# Marine Algae Bioactive Compounds as Potential Therapeutic Candidates for Parkinson's Disease — Molecular Docking Study.

## MSc Bioinformatics & Data Science | Portfolio Project.

---

## Project Overview

This study investigates three novel marine algae-derived bioactive compounds as potential inhibitors of alpha-synuclein aggregation in Parkinson's disease (PD) using in silico molecular docking.

**Target protein:** Alpha-synuclein (PDB: 1XQ8) — primary protein implicated in PD pathology

**Novel compounds tested:**
| Compound | Source | PubChem CID |
|---|---|---|
| Ulvan | Green algae (*Ulva* spp.) | 44134405 |
| Porphyran | Red algae (*Porphyra* spp.) | 11966269 |
| Dieckol | Brown algae (*Ecklonia cava*) | 5281791 |

---

## Biological Rationale

- PD gut microbiome shows 7.5-fold depletion of *Roseburia intestinalis* and 5-fold depletion of *Blautia wexlerae* (Wallen et al. 2022)
- Marine algae polysaccharides selectively restore these depleted SCFA-producing taxa
- Alpha-synuclein N-terminal region (residues 39-48) drives early aggregation
- Hypothesis: marine algae compounds can inhibit alpha-synuclein aggregation via gut-brain axis

---

## Methods

### Tools Used
- **AutoDock Vina 1.1.2** — molecular docking
- **OpenBabel 3.1.0** — file format conversion
- **RDKit** — 3D structure generation
- **PyMOL 3.1.0** — visualisation

### Pipeline
---

## Results

### Binding Affinity Comparison

| Compound | Best Affinity (kcal/mol) | Binding Site | Key Residues |
|---|---|---|---|
| Porphyran | -4.3 | N-terminal | weak binding |
| Ulvan | -5.0 | N-terminal | TYR39, VAL40, LYS43 |
| **Dieckol** | **-6.0** | **N-terminal** | **LYS43, LYS45, VAL48, TYR39** |

### Ulvan Binding
![Ulvan binding to alpha-synuclein](results/images/ulvan_binding.png)

### Porphyran Binding
![Porphyran binding to alpha-synuclein](results/images/porphyran_binding.png)

### Dieckol Binding
![Dieckol binding to alpha-synuclein](results/images/dieckol_binding.png)

---

## Key Finding

Dieckol (*Ecklonia cava* phlorotannin) showed strongest binding affinity (-6.0 kcal/mol) to the N-terminal domain of alpha-synuclein at residues TYR39, LYS43, LYS45, VAL48 — the region responsible for early aggregation initiation in Parkinson's disease.

---

## Repository Structure
---

## Reference

Wallen, Z.D. et al. (2022). Metagenomics of Parkinson's Disease Implicates the Gut Microbiome in Multiple Disease Mechanisms. *Nature Communications*, 13, 6958. https://doi.org/10.1038/s41467-022-34667-x


Author

Ganapathirajan
MSc Bioinformatics & Data Science

#### Future Perspectives & Expanded Literature
Based on recent literature reviews, this project aims to expand its *in silico* testing to investigate the **NAC domain** of alpha-synuclein (specifically the hydrophobic groove spanning residues 70-82 on high-resolution Cryo-EM fibril structures like 7Y7A). Recent evidence suggests that compounds like Dieckol act as powerful **multi-target inhibitors**, demonstrating high binding affinities (e.g., -11.4 kcal/mol) at the NAC domain in addition to the N-terminal trigger zone.

Furthermore, integrating **Green Extraction Techniques** (such as Ultrasound-Assisted Extraction and Supercritical Fluid Extraction) for these marine bioactives represents a critical next step toward sustainable neuropharmacological drug development.

#### Expanded References
* **Tewatia, R. et al. (2026).** Docking-Based Screening of Natural Compounds as Inhibitors of α-Synuclein Aggregation in Parkinson’s Disease: A Comprehensive Review. *Int. J. of Pharm. Sci.* 4(5), 3826-3853.
* **Sasidharan, S. & Chellappan, R. D. (2026).** Greener Extraction Techniques and Neuroprotective Compounds from Marine Algae: A New Wave in Neuropharmacology. *Asian Journal of Green Chemistry*, 10, 144-162.
* **De Luca, L. et al. (2022).** Ligand-Based Discovery of a Small Molecule as Inhibitor of α-Synuclein Amyloid Formation. *Int. J. Mol. Sci.*, 23(23), 14844. 
* **Wang, W. et al. (2015).** Neuroprotective effects of porphyran derivatives against 6-hydroxydopamine-induced cytotoxicity is independent on mitochondria restoration. *Annals of Translational Medicine*, 3(3).
* **Liu, Y. et al. (2018).** Oligo-Porphyran Ameliorates Neurobehavioral Deficits in Parkinsonian Mice by Regulating the PI3K/Akt/Bcl-2 Pathway. *Marine Drugs*, 16(3), 82.
* **Bisai, B. & Vavilala, S. L. (2021).** Neuroprotective Potential of Bioactive Sulfated Polysaccharides from Algae. *Acta Scientific Medical Sciences*, 5(8), 169-182.
