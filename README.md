# transformer-sentiment-analysis
Binary sentiment classification on the IMDB dataset using a transformer built from scratch in PyTorch.

## Results
- **Validation Accuracy:** 78.84%
- **Test Accuracy:** 76.11%

Trained for 3 epochs, exceeding the 75% project goal.

## Approach
- **Tokenizer:** BERT's subword tokenizer from Hugging Face
- **Model:** A custom transformer with mean pooling and a classification head
- **Training:** 3 epochs on the IMDB training set

## Requirements
```bash
pip install torch transformers pandas huggingface_hub numpy
