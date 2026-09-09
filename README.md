# MLEvalBook
MLEvalBook: An Open-Source Reference for Statistical Validation and Reproducible Machine Learning


MLEvalBook – Internal Development Roadmap

Phase 0 — Repository Foundation

Infrastructure

- [ ] Create GitHub repository
- [ ] Apache-2.0 license
- [ ] README skeleton
- [ ] CONTRIBUTING.md
- [ ] CODE_OF_CONDUCT.md
- [ ] CITATION.cff
- [ ] GitHub Discussions
- [ ] GitHub Issues templates
- [ ] GitHub Project Board
- [ ] Pre-commit hooks
- [ ] GitHub Actions CI

Documentation

- [ ] Project vision statement
- [ ] Scope and non-scope definition
- [ ] Target audience definition
- [ ] Repository structure finalized
- [ ] Method inclusion criteria

---

Phase 1 — Literature Survey

Train/Test Splits

Original Literature

- [ ] Train/Test Split references
- [ ] Cross Validation references
- [ ] Nested Cross Validation references
- [ ] Group K-Fold references
- [ ] Patient-Level Split references

Code Sources

- [ ] scikit-learn implementation review
- [ ] Official documentation review
- [ ] Example notebooks

---

Leakage Detection

Literature

- [ ] Target leakage
- [ ] Data leakage
- [ ] Temporal leakage
- [ ] Patient leakage
- [ ] Hospital leakage
- [ ] Feature leakage

Code Sources

- [ ] scikit-learn examples
- [ ] Medical AI examples
- [ ] Pathology examples

---

Confidence Intervals

Literature

- [ ] Wald CI
- [ ] Wilson CI
- [ ] Clopper-Pearson CI
- [ ] Bootstrap CI

Original Papers

- [ ] Collect seminal references
- [ ] Collect modern references

Code Sources

- [ ] statsmodels
- [ ] scipy
- [ ] official examples

---

Calibration

Literature

- [ ] Reliability Diagrams
- [ ] Platt Scaling
- [ ] Isotonic Regression
- [ ] Expected Calibration Error (ECE)
- [ ] Brier Score

Code Sources

- [ ] scikit-learn
- [ ] netcal
- [ ] official repositories

---

Statistical Significance Testing

Literature

- [ ] McNemar Test
- [ ] DeLong Test
- [ ] Permutation Test
- [ ] Paired t-Test
- [ ] Wilcoxon Signed Rank
- [ ] Effect Size
- [ ] Cohen's d

Code Sources

- [ ] statsmodels
- [ ] scipy
- [ ] Yandex DeLong implementation
- [ ] original repositories

---

Bootstrap Evaluation

Literature

- [ ] Efron Bootstrap
- [ ] Bias Corrected Bootstrap
- [ ] Bootstrap AUC
- [ ] Bootstrap Accuracy
- [ ] Bootstrap F1

Code Sources

- [ ] Original implementations
- [ ] scipy examples

---

External Validation

Literature

- [ ] Internal Validation
- [ ] External Validation
- [ ] Temporal Validation
- [ ] Geographic Validation
- [ ] Hospital Validation
- [ ] Prospective Validation

Medical AI Examples

- [ ] Histopathology
- [ ] Radiology
- [ ] Clinical Prediction

---

Experiment Tracking

Tools

- [ ] MLflow
- [ ] Weights & Biases
- [ ] TensorBoard
- [ ] DVC

Examples

- [ ] Local setup
- [ ] Docker setup
- [ ] Cloud setup

---

Phase 2 — Implementation

For every method:

- [ ] Original paper identified
- [ ] Canonical citation added
- [ ] Official implementation located
- [ ] License checked
- [ ] Reproducible notebook created
- [ ] Synthetic example added
- [ ] Real dataset example added
- [ ] References section completed

---

Phase 3 — Quality Control

For every notebook:

- [ ] Deterministic seed
- [ ] Tested on Python 3.12
- [ ] Tested on Linux
- [ ] Tested on Windows
- [ ] Output verified
- [ ] Runtime benchmarked

---

Phase 4 — Publication

Software Citation

- [ ] Create CITATION.cff
- [ ] Add ORCID
- [ ] Add OpenReview profile
- [ ] Add preferred citation
- [ ] Generate citation badge

GitHub and Zenodo both support CITATION.cff files for software citation metadata.

---

Zenodo

- [ ] Connect GitHub to Zenodo
- [ ] Create v1.0 release
- [ ] Archive release
- [ ] Obtain DOI
- [ ] Add DOI badge

Zenodo can archive GitHub releases and use repository citation metadata to support software citation and DOI generation.

---

Paper

arXiv

- [ ] Motivation
- [ ] Repository design
- [ ] Coverage analysis
- [ ] Comparison with existing resources
- [ ] Case studies
- [ ] Release paper

Future Journal

- [ ] JOSS submission
- [ ] Journal extension

---

Phase 5 — Long-Term Vision

- [ ] 50 GitHub stars

- [ ] 100 GitHub stars

- [ ] 500 GitHub stars

- [ ] 1000 GitHub stars

- [ ] Community contributions

- [ ] External maintainers

- [ ] Documentation website

- [ ] Pathology evaluation cookbook

- [ ] Medical AI evaluation cookbook

- [ ] Computer vision evaluation cookbook

- [ ] NLP evaluation cookbook

---

Ideas Parking Lot

- [ ] Uncertainty Quantification
- [ ] Bayesian Evaluation
- [ ] Conformal Prediction
- [ ] Fairness Metrics
- [ ] Dataset Shift Detection
- [ ] OOD Detection
- [ ] Federated Learning Evaluation
- [ ] Foundation Model Evaluation
- [ ] Medical AI Reporting Standards
- [ ] Statistical Review Checklist