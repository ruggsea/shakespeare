# Shakespeare Text Classifier

A BERT-based binary classifier for authenticating Shakespearean text.

This project was created as a collaborative learning exercise between [@ruggsea](https://github.com/ruggsea) and [@lanretto](https://github.com/lanretto) to teach the fundamentals of fine-tuning BERT models.

## Dataset

The model was trained on [lanretto/shakespeare-vs-modern-dialogue](https://huggingface.co/datasets/lanretto/shakespeare-vs-modern-dialogue), a binary classification dataset containing:

- **Label 0**: Modern movie dialogue
- **Label 1**: Authentic Shakespeare text
- **Test Set**: 40,626 samples (~30k modern, ~11k Shakespeare)

## Model Performance

- **Accuracy**: 98.2%
- **F1 Score**: 96.6%
- **Model**: [lanretto/shakespeare-authenticator](https://huggingface.co/lanretto/shakespeare-authenticator)

## Usage

Install dependencies:
```bash
pip install -r requirements.txt
```

Run the Jupyter notebook `Classification_Shakespear_text.ipynb` to see the complete training and evaluation pipeline.

