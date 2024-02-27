# Improving polymer property prediction using transfer learning

This repository consist of implementations of base molecule and polymer models using Circular, PolyBERT and MiniLM fingerprints. Using the base molecule model, we implement transfer learning techniques, zero-shot and few-shot learning, fine-tuning and frozen featurization.

:green_book: See the [Documentation](https://drive.google.com/file/d/1TG5VxRb4mNdCcCM1AKmJr1xIwkTk1-OF/view?usp=sharing)

:computer: Try the predictor: [Here](https://band-gap-predictor.streamlit.app/)

## Instructions to use this repoository.

The given CSV files only consist of SMILES and PSMILES strings and their properties. So we need to convert these strings to fingerprints. To do so please follow below instructions:

For this repository to work, please follow the following steps:

1. Install the requirements.txt file
2. Please run below files to set up data before training any models.

- data_molecules.ipynb
- data_polymers.ipynb

** Note ** Please note this repository only has state_dictionaries for base molecule models that can be reused to train any transfer learning models. The models can be trained by directly running the Jupyter notebooks.
