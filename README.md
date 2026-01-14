# Explainable AI for Model Interpretability

## Cross-Domain Evaluation on Natural and Medical Images

This repository presents a research-level exploration of explainable AI (XAI) methods applied across natural and medical imaging domains.
The study systematically investigates how architectural design, localization, and explanation strategies influence interpretability, attribution reliability, and diagnostic insight.

## Project Scope:

The notebooks encapsulate:

- Comparative evaluation of Grad-CAM, Integrated Gradients, and Attention Rollout.

- Experiments conducted on ResNet-18, DenseNet-121, and Vision Transformer (ViT) models.

- Quantitative faithfulness assessment using Insertion, Deletion, Entropy, and Sparsity metrics.

- Cross-domain validation on CIFAR-10 and RSNA Pneumonia Detection datasets.

Each notebook is self-contained, with output cells preserved to reflect finalized results and structured markdown reasoning

## Core Objectives:

- Examine architectural biases in interpretability mechanisms (CNN vs. ViT).

- Study the effect of dataset complexity on attribution fidelity.

- Bridge qualitative visualization with quantitative evaluation for model reasoning consistency.

- Identify cross-domain trends in explanation coherence.

## Reproducibility:

The repository prioritizes analysis reproducibility over computational retraining.
Due to model weight dependencies and dataset constraints, some notebooks are not designed for direct re-execution.
However, all outputs, metrics, and visual explanations are retained to ensure full transparency of results.

## Repository Structure:

```
XAI_Interpretability_Project
├── notebooks/           # Annotated and result-preserved notebooks
├── reports/             # Detailed and condensed project reports
└── README.md            # Current file
```
## Notebook Rendering Note
GitHub’s native notebook viewer may fail to render certain notebooks in this repository, particularly those containing complex visual outputs or widget metadata.
All notebooks are fully intact, and outputs have been preserved for analysis, but GitHub may display an “Invalid Notebook” or "Unable to render code block" message in some cases.

For best results, please download the notebooks locally or open them in JupyterLab or VS Code.

## Reports:

- Detailed Report: Comprehensive analysis, methodology, and extended discussion.

- Condensed Report: Summarized insights and comparative findings.

Both reports are available in the `reports/` directory.

## Research Reflection: 

This work serves as a qualitative and quantitative benchmark for evaluating explanation dynamics in deep neural networks.
It aims to encourage interpretability research focused on reasoning behavior, model introspection, and trustworthy diagnostics rather than conventional accuracy metrics.