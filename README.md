# ouroboros_eeg-fmri_nf

## Ouroboros EEG-fMRI NF: Predicting EEG activity, fMRI activity and NF scores

Version: 28th October 2022

Project developed by Maël Donoso, Ph.D. in Cognitive and Computational Neuroscience. Affiliations: Ouroboros Neurotechnologies (https://ouroboros-neurotechnologies.com/), Institut Lémanique du Cerveau (https://institut-cerveau.ch/), Policlinique Ostéopathique de Lausanne (https://policlinique-osteopathique-lausanne.ch/). 

### Abstract

This project uses data science (NumPy, Pandas, Matplotlib), machine learning (Scikit-Learn) and deep learning (TensorFlow) tools on bandpowers obtained with Electroencephalography (EEG), brain images obtained with functional Magnetic Resonance Imaging (fMRI), and Neurofeedback (NF) scores computed using both techniques. Our objective is to explore several ways to apply machine learning models to EEG-fMRI NF data, using a dataset from the open data repository OpenNeuro. Specifically, we use machine learning models to classify brain images, to predict the value of the fMRI BOLD signal and fMRI NF scores, and to predict the value of the EEG bandpowers and EEG NF scores. Our results show that some of these tasks are possible, suggesting that machine learning can be used to extract subtle patterns from EEG and fMRI data in the context of NF training. 

### Structure and dependencies

This project is organized through a series of six JupyterLab Notebooks, to be run in order:

- 01. Data Analysis
- 02. Classification
- 03. Neural Networks
- 04. Regression on fMRI data
- 05. Regression on EEG data
- 06. Results

Dependencies:

- python=3.6
- numpy=1.15
- scipy=1.2
- pandas=0.24
- matplotlib=3.0
- seaborn=0.9
- jupyterlab=2.1
- notebook=6
- scikit-learn=0.20
- tensorflow=1.12
- tensorflow-hub=0.4.0
- requests=2.20
- pillow=5.3
- graphviz=2.38
- python-graphviz=0.8.4
- pip=18.1
- tqdm
