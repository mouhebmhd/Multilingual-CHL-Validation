# Multilingual-CHL-Validation

Reference implementation accompanying our research on multilingual communicative health literacy (CHL) analysis using readability dynamics and cross-dataset validation.

## Overview

This repository implements the complete methodology proposed in our paper for analyzing communicative health literacy across multilingual online health communities.

The framework introduces two readability-based measures:

- **Readability Variance Score (RVS)** for measuring intra-document readability variability.
- **Readability Transition Score (RTS)** for quantifying readability transitions between consecutive sentences.

These metrics are combined with pragmatic annotations and unsupervised meta-clustering to identify Communicative Health Literacy (CHL) profiles across multiple languages.

To assess the robustness of the proposed methodology, the framework also performs **cross-dataset validation** using independent health corpora collected from multiple online platforms in English, French, and Arabic.

---

## Repository Structure

```
.
├── data/
│   ├── primary/
│   └── secondary/
│
├── preprocessing/
│
├── readability/
│   ├── rvs/
│   └── rts/
│
├── annotation/
│
├── clustering/
│
├── validation/
│
├── visualization/
│
├── results/
│
├── notebooks/
│
└── README.md
```

---

## Methodology

The workflow consists of the following stages:

1. Data collection
2. Data preprocessing
3. Sentence segmentation
4. Readability computation
5. Readability Variance Score (RVS)
6. Readability Transition Score (RTS)
7. Pragmatic annotation
8. Meta-clustering
9. Cross-dataset validation
10. Statistical analysis and visualization

---

## Supported Languages

- English
- French
- Arabic

The framework is designed to be language-agnostic and can be extended to additional languages with appropriate readability models.

---

## Validation Strategy

The repository supports validation using independent datasets collected from different online health platforms to evaluate the consistency of communicative health literacy profiles across platforms.

Validation includes:

- Mann–Whitney U tests
- Jaccard similarity
- Pearson correlation
- Distribution comparison
- Cross-language consistency analysis

---

## Citation

If you use this repository in your research, please cite our accompanying paper.

```
Citation information will be added after publication.
```

---

## License

This project is released under the MIT License.

---

## Contact

For questions or collaborations, please open an issue or contact the repository maintainers.
