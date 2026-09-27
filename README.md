# calotropis-network-pharmacology-molecular-docking
Network pharmacology and molecular docking analysis of Calotropis using computational drug discovery tools
# Network Pharmacology and Molecular Docking Study of *Calotropis procera* Against Depression

## Project Overview

This project investigates the potential therapeutic role of *Calotropis procera* in depression using an integrated **network pharmacology and molecular docking approach**.

The study combines bioactive compound identification, ADME screening, target prediction, disease-associated target identification, target intersection analysis, protein-protein interaction analysis, network construction, and molecular docking to investigate potential compound-target interactions and molecular mechanisms associated with depression.

---

## Aim

To investigate the potential therapeutic mechanisms of *Calotropis procera* against depression using network pharmacology and molecular docking approaches.

---

## Objectives

1. To identify compounds reported from *Calotropis procera*.
2. To collect and analyze the chemical information of the identified compounds.
3. To perform ADME screening and identify potentially bioactive compounds.
4. To predict potential molecular targets of the selected compounds.
5. To identify targets associated with depression.
6. To determine the overlapping targets between *Calotropis procera* compounds and depression-associated targets.
7. To identify and prioritize relevant molecular targets/receptors.
8. To construct and analyze compound-target networks using Cytoscape.
9. To perform molecular docking of selected bioactive compounds against prioritized protein targets.
10. To visualize and analyze ligand-protein interactions using BIOVIA Discovery Studio.

---

# Methodology

## 1. Identification of Phytoconstituents

Compounds reported from *Calotropis procera* leaves were collected from relevant literature and/or chemical databases.

The identified compounds were organized along with their corresponding chemical identifiers and structural information.

Chemical structures were represented using **SMILES (Simplified Molecular Input Line Entry System)** notation and relevant compound IDs.

---

## 2. ADME Screening

The identified compounds were subjected to **ADME (Absorption, Distribution, Metabolism and Excretion)** screening.

The screening was performed to identify compounds with suitable pharmacokinetic and drug-likeness characteristics.

Compounds satisfying the selected screening criteria were retained as potential bioactive compounds for subsequent analysis.

---

## 3. Target Prediction

Potential molecular targets associated with the selected compounds were identified using **SwissTargetPrediction**.

The predicted targets were collected and organized for further analysis.

This step helped establish potential relationships between the bioactive compounds of *Calotropis procera* and their molecular targets.

---

## 4. Disease-Associated Target Identification

Targets associated with **depression** were collected from relevant databases, including **GeneCards** and other appropriate sources.

The disease-associated target list was compiled and processed to obtain a comprehensive set of potential depression-related molecular targets.

---

## 5. Target Intersection Analysis

The targets associated with the *Calotropis procera* compounds were compared with the depression-associated targets.

**Venny** was used to identify the overlapping targets.

The overlapping targets represent potential molecular targets through which the compounds of *Calotropis procera* may exert effects related to depression.

The intersection analysis was represented using a Venn diagram.

---

## 6. Target and Receptor Identification

The overlapping targets were further investigated to identify relevant molecular targets and receptors associated with the proposed therapeutic mechanism.

**GeneCards** was used as an additional source for target/receptor information and biological relevance.

Prioritized targets were subsequently considered for network analysis and molecular docking.

---

## 7. Protein-Protein Interaction Analysis

The identified common targets were analyzed using the **STRING database** to investigate protein-protein interactions.

The resulting interaction information was used to understand the functional relationships between the identified targets and to identify important molecular interactions within the target network.

---

## 8. Network Construction and Analysis

The obtained compound-target and protein interaction data were imported into **Cytoscape** for network construction and visualization.

The network was used to represent relationships between:

* Bioactive compounds
* Molecular targets
* Disease-associated targets
* Protein-protein interactions

Network analysis was performed to identify important targets and potential hub nodes that may have a significant role in the proposed mechanism.

---

## 9. Molecular Docking

Molecular docking was performed to investigate the binding interactions between selected bioactive compounds and prioritized protein targets identified through the network pharmacology analysis.

**AutoDock Vina** was used as the molecular docking software.

The docking workflow included:

1. Selection of target proteins.
2. Retrieval of protein structures.
3. Preparation of protein structures.
4. Preparation of ligand structures.
5. Definition of the docking region/grid.
6. Molecular docking using AutoDock Vina.
7. Generation and evaluation of docking poses.
8. Comparison of binding affinities.
9. Selection of relevant ligand-protein complexes for interaction analysis.

Docking scores and binding poses were analyzed to investigate the potential binding of the selected compounds to the prioritized targets.

---

## 10. Molecular Interaction Visualization

The docked ligand-protein complexes were further analyzed using **BIOVIA Discovery Studio**.

The software was used to visualize and analyze the interactions between the ligands and target proteins, including relevant non-covalent interactions such as:

* Hydrogen bonds
* Hydrophobic interactions
* van der Waals interactions
* Other relevant ligand-protein interactions

Two-dimensional and/or three-dimensional interaction diagrams were generated for interpretation of the docking results.

---

# Overall Workflow

```text
*Calotropis procera* Leaves
            ↓
Identification of Phytoconstituents
            ↓
Chemical Structure / SMILES Collection
            ↓
ADME Screening
            ↓
Selection of Bioactive Compounds
            ↓
SwissTargetPrediction
            ↓
Compound-Associated Targets
            ↓
Depression-Associated Targets
            ↓
GeneCards / Disease Target Collection
            ↓
Target Intersection
            ↓
Venny Analysis
            ↓
Common Targets
            ↓
STRING Protein-Protein Interaction Analysis
            ↓
Cytoscape Network Construction
            ↓
Identification of Important Targets
            ↓
Selection of Target Proteins
            ↓
Molecular Docking
            ↓
AutoDock Vina
            ↓
Docking Scores and Binding Poses
            ↓
BIOVIA Discovery Studio
            ↓
Ligand-Protein Interaction Analysis
            ↓
Final Interpretation
```

---

# Software and Databases Used

## Databases / Online Resources

* GeneCards
* STRING
* SwissTargetPrediction
* PubChem
* Protein Data Bank (PDB)
* Relevant literature databases

## Analysis and Visualization Tools

* Venny
* Cytoscape
* AutoDock Vina
* BIOVIA Discovery Studio

---

# Data Organization

The repository contains the data and analysis associated with the different stages of the study.

```text
01_Data/
02_Network_Pharmacology/
03_Molecular_Docking/
04_Results/
05_Scripts/
```

The raw and processed datasets will be maintained separately wherever applicable to improve reproducibility and traceability of the analysis.

---

# Molecular Docking Information

Detailed docking information will be provided for each selected ligand-target pair, including:

* Compound name
* Compound ID
* Target protein
* PDB ID
* Docking software
* Docking parameters
* Binding affinity
* Docking pose
* Ligand-protein interactions

---

# Results

The repository will contain:

* Bioactive compound datasets
* Target prediction results
* Disease-associated target datasets
* Common/overlapping targets
* Venn diagrams
* STRING interaction data
* Cytoscape networks
* Hub-target analysis
* Molecular docking results
* Docking scores
* Ligand-protein interaction diagrams

Detailed results and interpretations will be added as the project progresses.

---

# Project Status

**Status: Completed / Ongoing**

The network pharmacology analysis and molecular docking workflow has been performed. Final organization of datasets, figures, docking results, and interpretation is in progress.

---

# Reproducibility

This repository is intended to document the computational workflow used in the study.

Data files, analysis outputs, methodology, and relevant computational parameters will be organized within the repository to facilitate reproducibility and future reference.

---

This computational study is intended to provide hypotheses regarding potential compound-target interactions and molecular mechanisms. Network pharmacology and molecular docking results require appropriate experimental validation before conclusions regarding therapeutic efficacy can be established.
