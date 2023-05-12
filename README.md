# Drug-Induced-Liver-Injury-DILI-prediction-using-machine-learning
## Overview
The main aim of this project is to predict the Drug-induced liver injury (DILI) which is a major factor in the development of drugs and the safety of drugs. If the DILI cannot be effectively predicted during the development of the drug, it will cause the drug to be withdrawn from markets. Physicochemical nature of compounds like lipophilicity has been identified as an important risk factor for DILI when considering together with daily dose. So various physicochemical properties of the molecules generated using padelpy descriptors. Drug-induced liver injury (DILI) is a major factor in the development of drugs and the safety of drugs. If the DILI cannot be effectively predicted during the development of the drug, it will cause the drug to be withdrawn from markets. Therefore, DILI is crucial at the early stages of drug research. This work presents a 2-class ensemble classifier model for predicting DILI, with 2D molecular descriptors and fingerprints on a dataset of 450 compounds. The purpose of our study is to investigate which are the key molecular fingerprints that may cause DILI risk, and then to obtain a reliable ensemble model to predict DILI risk with these key factors. Experimental results suggested that 8 molecular fingerprints are very critical for predicting DILI, and also obtained the best ratio of molecular fingerprints to molecular descriptors. The result of the 5-fold cross-validation of the ensemble vote classifier method obtain an accuracy of 77.25%, and the accuracy of the test set was 81.67%. This model could be used for drug-induced liver injury prediction..
## Requirements
Python 3.6 or higher
scikit-learn
pandas
numpy
matplotlib (for visualizing results)
padelpy (for generating molecular descriptors and fingerprints)
RDkit

## Results
The result of the 5-fold cross-validation of the ensemble vote classifier method obtain an accuracy of 77.25%, and the accuracy of the test set was 81.67%. This suggests that our model is a reliable tool for predicting DILI risk.
## Note
It is important to note that the model is trained on a limited dataset, and the results should be considered only as a rough estimate of the DILI risk for a given drug. The results should not be used for clinical decision making.
## References
Minjun Chen, Huixiao Hong, Hong Fang, Reagan Kelly, Guangxu Zhou, Jürgen Borlak, Weida Tong, Quantitative Structure-Activity Relationship Models for Predicting Drug-Induced Liver Injury Based on FDA-Approved Drug Labeling Annotation and Using a Large Collection of Drugs, Toxicological Sciences, Volume 136, Issue 1, November 2013, Pages 242–249, https://doi.org/10.1093/toxsci/kft189

