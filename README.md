**Development of Baseline Classification Model for OOS LID**

This repository presents a baseline model for classifying languages in an open-set scenario using Support Vector Machines (SVMs).
The project focuses on developing a robust and efficient system capable of handling known and unknown languages.


Project Description:

This project implements a baseline classification model for open-set Language Identification (LID) using SVMs.
The model leverages the following key components:

VoxLingua Dataset: Audio samples are extracted from the VoxLingua dataset, encompassing 20 different languages.

ECAPA-TDNN Feature Embedding: The ECAPA-TDNN extracts feature embeddings from the audio data, providing a robust representation for classification.

SVM Classifier: A Support Vector Machine (SVM) is trained on the extracted features to classify languages.The SVM is equipped for outlier detection, trying to make it able to identify whether the language is Inset or Outset. 

Individual Language Threshold Probabilities: The model outputs threshold probabilities for each language, allowing for a more nuanced classification approach by understanding the behaviour of languages and performing experiments on them.
