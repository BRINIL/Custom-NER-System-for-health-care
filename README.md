**Healthcare Named Entity Recognition**
This repository contains code and models for a custom named entity recognition (NER) system focused on healthcare entities.

**Overview**
Healthcare data contains many important entities such as medications, procedures, diagnoses, etc. This NER system can accurately extract those entities from clinical text data like doctor's notes, medical literature, patient health records, and more.

**Entities Recognized**
The system recognizes the following entity types related to healthcare:
Medications
Procedures
The specific entities recognized under each type are customized based on target use cases in healthcare.

**Data**
The system was trained and evaluated using a proprietary dataset of deidentified clinical notes annotated for the entity types above. This customized dataset focuses on common entities seen in real-world health data.

Due to sensitive medical information, the original training data is not publicly shared. An anonymized sample dataset is included to demonstrate the data schema.

**Model Architecture**
The named entity recognition model uses a bidirectional LSTM architecture with a conditional random field (CRF) decoding layer. This allows it to effectively capture context and label sequence patterns to detect healthcare entities.

The model performance is robust, with a validation F1 score of 0.87. Detailed metrics on the test set are withheld for proprietary reasons.
