
# Artificial Intelligence to validate Drug Repurposing Hypotheses

This repository accompanies the Final Master's Thesis:  
**“Exploring the Use of Large Language Models in Drug Repurposing Validation”**  
By *Iratxe Zunzunegui Sanz*

---

## Overview

This project explores how Large Language Models (LLMs) can be used to validate drug repurposing hypotheses generated through pathway-based analysis. We evaluate four LLMs — GPT-4o, Claude-3, Gemini-2, and DeepSeek — using various prompt engineering strategies across both novel and benchmark drug-disease associations.

The repository includes:

- 40-case datasets derived from pathway-based predictions (DREBIOP)
- A set of 20 benchmark drug repurposing cases for comparison
- 10 prompt engineering techniques used across multiple LLMs
- Evaluation scripts and metrics (accuracy, precision, recall, F1-score)
- Results from both the prompt evaluation and the comparison with benchmark cases


---

## Repository Structure

```bash
├── data/
│   ├── pathway_cases.csv
│   ├── benchmark_cases.csv
│   └── prompt_templates.md
├── docs/
│   ├── references.md
│   └── dataset_description.md
├── results/
│   ├── approach1_benchmarking_results.csv
│   ├── approach1_phase1_results.csv
│   ├── approach1_phase2_results.csv
│   ├── approach2_benchmarking_results.csv
│   └── approach2_pathway_results.csv
├── scripts/
│   ├── approach_1_evaluation.ipynb
│   └── approach_2_evaluation.ipynb
├── figures/
│   └── graphical_abstract.png
│   └── heatmap_f1.png
│   └── barplots_phase2.png
└── README.md
```
---

## Related Publication

Zunzunegui Sanz, I., Otero-Carrasco, B., & Rodríguez-González, A.  
**“Accelerating Drug Repurposing with AI: The Role of Large Language Models in Hypothesis Validation”**  
*Presented at the 38th IEEE International Symposium on Computer-Based Medical Systems (IEEE CBMS2025)* – Madrid, Spain 2025  
DOI: https://doi.org/10.1101/2025.06.13.659527

---

## Contact

For questions, feel free to reach out:  
**iratxe.zunzunegui.sanz@alumnos.upm.es** ORCID: 0009-0002-0608-4615

**belen.otero@upm.es**
ORCID: 0000-0001-7315-2257

**alejandro.rg@upm.es**
ORCID: 0000-0001-8801-4762
