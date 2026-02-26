# Game-Based Learning & Assessment for Digital Skills  
## Replication Package

This repository contains all data and analysis materials required to ensure the **transparency, reproducibility, and repeatability** of the study:

> *Improving Digital Skills for Older Adults: A Game-Based Approach*

The materials provided here allow independent researchers to replicate the statistical analyses, verify reported results, and understand the mapping between game design and competence framework alignment.

---

## Repository Contents

### Pre/Post Performance Data

**File:** `Pre_Post_Performance.xlsx`

This file contains:

- Participant demographic data  
- Baseline (pre-test) proficiency levels  
- Post-game proficiency levels  
- Distributions across DigComp competence areas  
- Aggregated mean values used in comparative analysis  

The dataset enables replication of:

- Absolute and relative improvements  
- Distribution analyses  
- Non-parametric comparisons (Wilcoxon tests)  
- Effect size calculations  

---

### GPQ Questionnaire Dataset (SDT-based)

**File:** `Cronbach_alpha_computation_template.xlsx`

This file contains the raw item-level responses (N = 45 participants) for the Self-Determination Theory–based Gameplay Questionnaire (GPQ), structured into three sheets:

- **Autonomy answers** (3 items)  
- **Competence answers** (4 items)  
- **Relatedness answers** (3 items)  

The dataset enables replication of:

- Cronbach’s alpha calculations  
- Item variances  
- Corrected item–total correlations  
- Shapiro–Wilk tests  
- Friedman tests  
- Cliff’s delta effect sizes  
- Likert-scale distribution plots  

---

### Statistical Analysis Code

**File:** `GBL+GBA.ipynb`

This Jupyter Notebook contains the complete Python code used for:

- Data preprocessing  
- Reliability analysis  
- Non-parametric statistical testing  
- Effect size computation  
- Distribution plotting  
- Figure export (high-resolution PNG)  

The notebook is fully executable and reproduces all reported statistical outputs.

---

### DigComp Mapping Documentation

**Files:** Corresponding PDF documents for each game in this repository

These files contain:

- Mapping of each game question to DigComp competence areas  
- Alignment with proficiency levels  
- Explanation of task–competence relationships  
- Design rationale for INFINITY and DiGiUP  

These materials allow full traceability between:

- Game mechanics  
- Assessment logic  
- Competence framework alignment  

---

### SDT-Coded Trainer Notes

**File:** `SDT-Coded_Trainers_Notes.pdf`

This document contains the qualitative trainer observations systematically coded according to **Self-Determination Theory (SDT)**. The coding framework is structured around the three basic psychological needs:

- **Autonomy (A)**  
  - A1: Initiative and choice  
  - A2: Reduced fear of errors  
  - A3: Perceived relevance  

- **Competence (C)**  
  - C1: Initial low self-efficacy  
  - C2: Skill acquisition  
  - C3: Confidence gains  

- **Relatedness (R)**  
  - R1: Peer support  
  - R2: Shared emotional experience  
  - R3: Collaborative problem solving  

The document provides a structured thematic analysis of participant behaviors and interactions observed during both INFINITY and DiGiUP gameplay sessions.

#### Purpose

The SDT-coded notes serve to:

- Provide transparency in the qualitative analysis process  
- Demonstrate how observational evidence aligns with SDT constructs  
- Support the interpretation of quantitative motivational findings  
- Ensure methodological traceability between raw observations and reported conclusions

---

## Reproducibility Statement

All datasets are anonymised. No personally identifiable information is included.

The repository provides:

- Raw response data  
- Processed performance data  
- Statistical analysis scripts  
- Design documentation  

Together, these materials ensure full reproducibility of:

- Reliability analyses  
- Pre/post comparisons  
- Effect size calculations  
- Motivational construct analysis  
- Competence progression findings  

---

## Software Requirements

- Python 3.9+
- Jupyter Notebook
- pandas
- numpy
- scipy
- matplotlib

All dependencies are specified within the Jupyter notebook.

---

## Citation

If you use this dataset or analysis pipeline, please cite:

> [Full journal citation once published]

---

## Contact

For methodological clarifications or replication inquiries, please contact the corresponding author.
