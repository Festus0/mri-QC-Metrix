# MRI QC Notebooks

A reproducible MRI image-quality control (QC) workflow implemented in Jupyter notebooks using Python and NIfTI imaging data.

This repository demonstrates practical MRI quality assessment techniques suitable for research pipelines, scanner benchmarking, reconstruction validation, and quantitative imaging workflows.

---

## Overview

This project provides:

- Automated image quality diagnostics on NIfTI volumes  
- Quantitative QC metric extraction  
- Visual diagnostic outputs  
- Reproducible notebook execution  
- Clean repository structure for sharing and audit  

Designed for:

- Scanner performance comparison  
- Reconstruction pipeline validation  
- Sequence benchmarking  
- Pre-analysis QC screening  
- Research data integrity checks  

---

## Repository Structure
# MRI QC Notebooks

A reproducible MRI image-quality control (QC) workflow implemented in Jupyter notebooks using Python and NIfTI imaging data.

This repository demonstrates practical MRI quality assessment techniques suitable for research pipelines, scanner benchmarking, reconstruction validation, and quantitative imaging workflows.

---

## Overview

This project provides:

- Automated image quality diagnostics on NIfTI volumes  
- Quantitative QC metric extraction  
- Visual diagnostic outputs  
- Reproducible notebook execution  
- Clean repository structure for sharing and audit  

Designed for:

- Scanner performance comparison  
- Reconstruction pipeline validation  
- Sequence benchmarking  
- Pre-analysis QC screening  
- Research data integrity checks  

---

## Repository Structure

---

## Implemented QC Metrics

The notebooks demonstrate quantitative MRI QC metrics including:

### Intensity-Based Metrics
- Global mean intensity  
- Standard deviation  
- Intensity histograms  
- Distribution skewness and kurtosis  

### Signal Quality Proxies
- SNR-style estimates (global or ROI-based)  
- Background noise estimation  

### Sharpness & Focus Metrics
- Gradient magnitude energy  
- Laplacian variance (focus proxy)  
- Edge density analysis  

### Structural Diagnostics
- Slice-wise intensity consistency  
- Outlier slice detection  
- Volume statistics across axes  

### Visual Outputs
- Histogram plots  
- Slice visualization panels  
- Diagnostic overlays  
- Summary metric reporting  

---

## Technologies Used

- Python  
- NumPy  
- SciPy  
- Pandas  
- Matplotlib  
- NiBabel (NIfTI handling)  
- scikit-image  
- Jupyter Notebook  
- Git LFS (for large NIfTI files)  

---

## How to Run

### Option 1 – Jupyter Lab

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
