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
- Performance comparison
- Confusion Matrix

## Results

Random Forest (k=3): 0.375

Random Forest (k=4): 0.350



Best Result:
Random Forest with k=3


## Student C Tasks

### Data Collection and Dataset Preparation

Tasks completed:

- Downloaded protein sequence data from UniProt
- Collected four protein families:
  - Kinases
  - Proteases
  - Transporters
  - Receptors

- Parsed FASTA files using BioPython
- Filtered protein sequence lengths (50–1000 amino acids)
- Created labeled dataset
- Converted records into a Pandas DataFrame
- Applied stratified train-test split:
  - Training set: 80%
  - Testing set: 20%

- Generated:
  - train.fasta
  - test.fasta

## Results

Dataset statistics:

Training samples: 531 sequences  
Testing samples: 133 sequences  

Class distribution:

- Proteases: 149
- Transporters: 131
- Receptors: 129
- Kinases: 122

Generated FASTA files successfully:

train.fasta → 531 sequences  
test.fasta → 133 sequences
### BLAST Baseline Evaluation

Tasks completed:

- Implemented BLAST as a baseline method
- Compared protein sequences using similarity search
- Generated prediction labels
- Evaluated baseline performance using Confusion Matrix
- Visualized classification performance

## BLAST Results

Confusion Matrix observations:

- Kinases correctly classified: 25
- Proteases correctly classified: 35
- Transporters correctly classified: 14
- Receptors correctly classified: 25

Minor misclassifications observed between related protein families.

BLAST baseline achieved strong performance and was used as a reference for comparison with Machine Learning and CNN models.

## Student
Mohamed Karim 221010054

Yousef abdallah khamis 221002152
