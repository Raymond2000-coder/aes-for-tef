# Automated Essay Scoring for TEF Writing Tasks

This project explores the use of Natural Language Processing and Transformer-based models to automatically predict the writing score of candidates taking the Test d’Évaluation de Français (TEF).

## Objective

The goal is to build a machine learning pipeline capable of estimating the overall writing score based on the candidate's written response and contextual information provided in the prompt.

## Project Structure

```text
aes-for-tef/
├── README.md
├── requirements.txt
├── AES_FOR_TEF.ipynb
```

## Technologies

- Python
- Transformers (HuggingFace)
- CamemBERT
- PyTorch
- Pandas / NumPy
- Scikit-learn

## Methodology

1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Baseline modeling
4. Transformer fine-tuning with CamemBERT
5. Subscore prediction model
6. Model evaluation

## Notes

- The repository shares the code and notebook structure.
- Sensitive or heavy datasets, model checkpoints, and confidential files should not be uploaded publicly.

## Results

The CamemBERT-based model was trained to predict the overall writing score from candidate responses.

The model demonstrates the potential of transformer architectures for automated essay scoring tasks and shows promising predictive performance when combining contextual exam information with candidate responses.

Future work may include:
- Larger training datasets
- Improved model architectures
- Explainability techniques for score interpretation

## Author

Raymond Maurice Faye
