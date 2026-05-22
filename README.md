# Protein-Family-Classification
Protein Family Classification using Random Forest and 1D CNN on UniProt protein sequences
# Protein Family Classifier – AI in Bioinformatics

## Project Overview
Protein classification using Machine Learning and Deep Learning techniques.

Classes:
- Kinase
- Protease
- Receptor
- Transporter

## Student B Tasks
- Random Forest with k-mer (k=3, k=4)
- CNN model
- Performance comparison
- Confusion Matrix

## Results

Random Forest (k=3): 0.375

Random Forest (k=4): 0.350

CNN Accuracy: 0.34

Best Result:
Random Forest with k=3


 Student C Tasks

### Data Preparation and Dataset Setup

This part focuses on preparing protein sequence data for training and testing.

### Steps Performed

- Download protein sequences from UniProt
- Extract sequences from FASTA files
- Filter protein sequence lengths
- Create labeled dataset:
  - Kinases
  - Proteases
  - Transporters
  - Receptors
- Split dataset into:
  - Training set (80%)
  - Testing set (20%)
- Generate:
  - train.fasta
  - test.fasta

## Dataset Summary

Total sequences collected from protein families and prepared for machine learning and deep learning experiments.

## Technologies Used

- Python
- Pandas
- BioPython
- Scikit-learn

## Student
Mohamed Karim 221010054

Yousef abdallah khamis 221002152
