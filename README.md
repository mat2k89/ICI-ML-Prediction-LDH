# ICI-ML-Prediction-LDH
Machine learning classifier to predict immunotherapy in hepatocellular carcinoma using electronic health record data - published in Lancet Digital Health:

The use of advanced machine learning to predict outcomes after atezolizumab plus bevacizumab for advanced hepatocellular carcinoma: a retrospective cohort study. Lancet Digit Health. 2026 Feb 12:100952. doi: 10.1016/j.landig.2025.100952. Epub ahead of print. PMID: 41688234.

Vithayathil M, Manfredi GF, D'Alessio A, Fulgenzi CAM, Celsa C, Lombardi P, Torkpour A, Stefanini B, Galle PR, Nishida N, Scheiner B, Crowley F, Wu L, Ang C, Marron TU, Hsu WF, Lin CY, Lin RP, Ulahannan SV, Andanamala H, Soror N, Kaseb A, Lapelusa M, Mohamed YI, Schönlein M, von Felden J, Schulze K, Wege H, Wietharn B, Vivaldi C, Salani F, Masi G, Pressiani T, Dalbeni A, Natola L, Marseglia M, Piscaglia F, Huang YH, Lee PC, Pirisi M, Parisi A, Rohlen N, Thimme R, Silletta M, Di Giacomo E, Vincenzi B, Galbato L, Vogel A, Cabibbo G, Camma C, Jae Chon H, Pinter M, Cortellini A, Kudo M, Zanuso V, Rimassa L, Pinato DJ, Aboagye EO, Sharma R. 

## Features<br/>
- <ins>Data preprocessing</ins><br/>
  - Feature harmonisation<br/>
  - Feature engineering (z-normalisationand one-hot encoding)<br/>
  - Imputation<br/><br/>
- <ins>Model training</ins><br/>
  - Feature selection<br/>
  - Supervised machine learning prediction<br/>
  - Ensemble learning<br/><br/>
- <ins>Model evaluation</ins><br/>
  - AUC against clinical benchmarks<br/>
  - Survival analysis with Kaplan-Meier, Cox Regression and C-index<br/>
  - Calibration curve<br/>
  - Decision curve analysis<br/>
  - Feature importance<br/>

## Directory structure
```
project_root/
├── src/                # Core implementation
│   ├── data/         # Data preprocessing codes
│   ├── model_builder/       # Model builder and feature selection codes
│   └── model_evaluation/          # Model evaluation 
├── notebooks/            # Notebooks for ML model construction and evaluation
    ├── 2025_Mar_31_Immuno_ML_impute_PFS_LDH.ipynb        # Notebook predicting 6-month progression
│   └── 2025_Mar_31_Immuno_ML_impute_OS_LDH.ipynb         # Notebook predicting 1-year mortality
└── requirements.txt
```

## Installation
Uses Python 3.8.8 
```bash
pip install -r requirements.txt
```
## Usage

### <ins>Machine Learning Radiomics Workflow</ins>

Workflow for Radiomics Machine Learning Model shown in notebooks for overall survival and progression-free survival prediction
