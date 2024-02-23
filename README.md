# GPT-TOKENIZER
<img width="700" alt="image" src="https://github.com/iamharshvardhan/gpt-tokenization/assets/82762146/c063df5a-da24-448f-a50f-bedd6da7fa68">

This repository provides a basic demonstration of tokenizers used in NLP models like GPT-2, SentencePiece, etc. Tokenizers play a crucial role in natural language processing tasks by breaking down input text into smaller units, typically tokens, which are then used as input to NLP models.

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your_username/tokenizers-demo.git
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open either `Tokenization.ipynb` to view and run the demonstration notebooks.

## About Tokenizers

Tokenizers are essential components in natural language processing pipelines. They break down input text into smaller units, such as words or subwords, which are easier for models to process. Some common tokenization techniques include:

- **Word Tokenization**: Breaking text into individual words.
- **Subword Tokenization**: Breaking text into smaller subword units, which can be especially useful for handling out-of-vocabulary words and morphologically rich languages.
- **Byte Pair Encoding (BPE)**: A subword tokenization algorithm that iteratively merges frequent pairs of characters.

Both GPT-2 and SentencePiece tokenizers provide efficient methods for tokenizing text and preparing it for input into NLP models.

## License

This repository is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.
