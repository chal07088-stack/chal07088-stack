# Minjae Kim · 김민재

**Computer Vision · Medical Imaging · Deep Learning**

[GitHub](https://github.com/chal07088-stack)

<br>

I study how information from paired images can improve visual recognition, with a focus on bilateral diabetic retinopathy grading. My current research examines when information from the fellow eye helps a prediction—and when it can make it worse.

## Research

### Bilateral Diabetic Retinopathy Grading
*Ongoing research*

Retinal images from the two eyes provide related information, but disease severity can differ between eyes. I investigate adaptive fusion methods that use this relationship while accounting for cases where bilateral correction may harm an otherwise correct prediction.

My work focuses on:

- **Boundary-wise correction:** modeling how fellow-eye information changes individual severity boundaries.
- **Adaptive fusion:** comparing simple fusion with learned utility, strength, and soft-gating mechanisms.
- **Benefit and harm analysis:** examining which predictions improve, which deteriorate, and how these changes differ across bilateral asymmetry groups.

### Reliable Evaluation for Multi-stage Models

I also examine how training and inference choices affect a multi-stage vision pipeline. This includes patient-level data separation, nested out-of-fold feature generation, checkpoint lineage, and the transfer of learned features between upstream models.

Evaluation combines classification and ordinal metrics with patient-paired uncertainty estimates and subgroup analysis.

## Research & Engineering

**Model development**  
Building and comparing multi-stage image classification and bilateral fusion pipelines.

**Experimental analysis**  
Controlled ablations, negative controls, failure-case analysis, and prediction-level diagnostics.

**Reproducibility**  
Tracking data splits, feature schemas, configurations, checkpoints, and file integrity.

## Tools

`Python` · `PyTorch` · `NumPy` · `pandas` · `scikit-learn`  
`Git` · `Linux` · `PowerShell`

<br>

<sub>Research descriptions refer to ongoing work; they do not imply peer-reviewed publication or clinical validation.</sub>
