# Text Preprocessing and Embedding Generation using Hugging Face Transformers

## Project Overview

This project demonstrates how to preprocess text descriptions and convert them into numerical embeddings using Hugging Face Transformers. These embeddings can be used as inputs for text-to-image generation models.

## Objective

To tokenize and encode text data into meaningful vector representations so that AI models can better understand textual information.

## Technologies Used

* Python
* Google Colab
* PyTorch
* Hugging Face Transformers
* DistilBERT

## Workflow

1. Input text descriptions
2. Clean and preprocess the text
3. Tokenize using DistilBERT tokenizer
4. Generate 768-dimensional embeddings
5. Save embeddings for future use in text-to-image models

## Sample Output

The model successfully converts text descriptions into numerical embeddings with the following shape:

```python
torch.Size([1, 768])
```

## Conclusion

The project successfully preprocesses text and generates embeddings using Hugging Face Transformers. These embeddings can be used as inputs for text-to-image generation systems to improve text understanding.
