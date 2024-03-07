# Early Disease Detection using Multinomial Naive Bayes Algorithm

## Overview
This project focuses on early disease detection using the Multinomial Naive Bayes algorithm. The model is trained to classify diseases based on symptoms extracted from a provided dataset, encompassing more than 150 symptoms. The trained model is then saved for future use.

## Steps

### 1. Data Loading
- The dataset containing disease information and corresponding symptoms is loaded using Pandas from the file `data.csv`.

### 2. Data Preparation
- Diseases and symptoms are extracted from the dataset.
- The `Diseases` column is considered as the target variable, and the remaining columns are considered as features.

### 3. Model Training
- A Multinomial Naive Bayes model is instantiated.
- The model is trained using the symptoms as features and diseases as the target variable.

### 4. Model Saving
- The trained model is saved to a file named `disease_model.pkl` using the `pickle.dump()` function.

### 5. Model Loading
- The saved model is loaded back into memory using the `pickle.load()` function.

## Features
- Utilizes the Multinomial Naive Bayes algorithm for disease classification.
- Incorporates likelihoods or probabilities of various symptoms for accurate prediction.
- Trains a single model encompassing all diseases and their corresponding symptoms.
- Recommends specific diagnostic tests post-disease classification for comprehensive patient evaluation.

## Diseases
1. Infarct
2. Ischemia
3. Aortic Dissection
4. PE (Pulmonary Embolism)
5. CHF (Congestive Heart Failure)
6. Pericarditis
7. AS/AI (Aortic Stenosis/Aortic Insufficiency)
8. Pulmonary
9. Eso rupture (Esophageal Rupture)
10. MS (Mitral Stenosis)
11. GI (Gastrointestinal)

## Recommended Tests
1. HsTnT 0H
2. No further test
3. D-Dimer
4. NT pro BNP
5. ESR (Erythrocyte Sedimentation Rate)
6. CRP (C-Reactive Protein)
7. WBC (White Blood Cell Count)
8. Hb (Hemoglobin)
9. EKG (Electrocardiogram)
10. CXR (Chest X-Ray)
11. CT (Computed Tomography)
12. ECHO (Echocardiogram)

**Note:** The dataset used in this research work is private and not available for public access.
