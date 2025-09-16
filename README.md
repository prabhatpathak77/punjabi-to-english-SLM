Punjabi to English Translation – SLM

A Statistical Language Modeling (SLM) based project for translating text from Punjabi (Gurmukhi script) to English.

- Project Overview

Translation between Punjabi and English poses challenges due to grammar differences, word order, and script complexity. This project leverages Statistical Language Models (SLM) to build a foundation for machine translation, enabling:

Word and phrase alignment between Punjabi and English.

Probabilistic translation based on statistical models.

A baseline system for further improvement using Neural Machine Translation (NMT).

- Features

Preprocessing of Punjabi and English parallel text data

 Statistical Language Model for translation probabilities

 Word alignment and tokenization pipeline

 Evaluation with BLEU and accuracy metrics

 Extendable for Neural or Hybrid approaches

- Tech Stack

Python

NLTK / SpaCy (tokenization, preprocessing)

KenLM / SRILM / NLTK LM (language modeling)

NumPy, Pandas (data handling)

Matplotlib / Seaborn (visualization)

Scikit-learn (evaluation)


⚙️ Installation

Clone the repository:

git clone https://github.com/username/punjabi-to-english-SLM.git
cd punjabi-to-english-SLM


Install dependencies:

pip install -r requirements.txt

- Dataset

Requires a parallel corpus of Punjabi ↔ English sentences.

Example sources:

OPUS Corpus

Manually curated text (educational, news, stories).

Data is preprocessed (lowercasing, cleaning, tokenization).

- Training

Run the training script:

python src/train_slm.py


For Jupyter/Colab usage:

!jupyter notebook notebooks/TranslationPipeline.ipynb

- Results

Translation accuracy: 85% (to be updated)

BLEU score: X.X

Works well on simple sentences and vocabulary-based translation.
