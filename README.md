# Multi-Disease-FL-Dataset-Archive
Curated clinical and medical imaging-related datasets for a dual-stage federated learning framework.
# Privacy-Preserving and Scalable Federated Learning Framework for Multi-Disease Prediction

This repository contains the curated datasets and reference materials for the dual-stage federated learning framework designed for heart disease, chronic kidney disease (CKD), and diabetes prediction.

## 📂 Repository Structure

* **/datasets/clinical_screening/**: Contains the tabular clinical data used for Stage-1 Multi-label Federated Distillation (FedMD).
* **/datasets/confirmatory_images/**: Contains representative samples of physiological signals and medical imaging used for Stage-2 CNN validation.
    * `ecg/`: 1D-CNN training samples for heart disease.
    * `ultrasound/`: 2D-CNN training samples for kidney abnormality detection.

## Dataset Information

### Stage-1: Clinical Screening (Tabular Data)
The clinical datasets were sourced from the UCI Machine Learning Repository via Kaggle.
* **Heart Disease**: Cleveland Dataset.
* **Diabetes**: PIMA Indians Diabetes Database.
* **CKD**: Chronic Kidney Disease Dataset.
* **Public Reference Set**: A curated dataset utilized for Federated Model Distillation (FedMD) to synchronize local client knowledge without sharing private data.

### Stage-2: Confirmatory Diagnosis (Image/Signal Data)
Due to file size constraints on GitHub, this repository provides a **representative subset** of the full image datasets. 
* **ECG Signals**: Utilized for 1D-CNN heart disease validation (98.13% Accuracy).
* **Ultrasound Scans**: Utilized for 2D-CNN kidney validation (100% Accuracy).

*Note: The full high-resolution datasets (approx. 300MB) used for training and testing are available from the original Kaggle/UCI sources or can be provided by the authors upon reasonable request.*

## 📜 Academic Credit
Original data contributions belong to the UCI Machine Learning Repository and respective Kaggle contributors. This repository serves as a versioned archive to ensure the reproducibility of the results presented in the associated journal submission.
