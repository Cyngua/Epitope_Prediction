# Predicting Systemic Lupus Erythematosus (SLE)-Associated Epitopes using Deep Learning

### Nilay Bhatt, Xincheng Cai, Tom Shin, Luning Yang

## Abstract

Systemic Lupus Erythematosus (SLE) is a global health issue with diverse symptoms and serious
complications. Current research is mainly focused on identifying epitopes to uncover autoimmune
triggers, which contributes to the development of precision medicine for SLE. While the computational
methods for epitope prediction have progressed, the complexity of SLE makes specific predictions
challenging, which eventually hinders therapy development and drug discovery.
Although extensive experimental data are available on certain open-source biomedical datasets, predicting
SLE-associated epitopes has not been fully leveraged by traditional ML-based methods. Our project aims to leverage state-of-the-art Deep learning models like ProtBERT, ReLSO, BEETLE and MITNet to predict immunogenic potential of an epitope for SLE-related outcomes.

## Navigate

```bash
/Epitope_Prediction_DL-main
├── Data
│   ├── clean_data.csv
│   ├── data.csv
│   ├── Data_processing_EDA.ipynb
├── MITNet_training
│   ├── biomitnet_adam_model.pth
│   ├── biomitnet_adamW_model.pth
│   ├── clean_data.csv
│   ├── mitnet_adamw_model.pth
│   ├── performance_ctc_base.csv
│   ├── performance_mitnet_all.csv
│   ├── test_model_bioinfo.ipynb
│   └── test_model.ipynb
├── performance_all.csv
├── ProtBert
│   ├── ProtBERT_full.ipynb
└── RELSO
    └── ReLSO (full).ipynb
```
