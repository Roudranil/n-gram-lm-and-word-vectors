# Building a n-gram LM and word vectors

This is a small project that works with a smaller version of the english-wiki corpus and builds a n-gram language model and word vectors out of this corpus

## Cleaning and tokenization

[01-tokenization-and-verification-of-empirical-laws.ipynb](01-tokenization-and-verification-of-empirical-laws.ipynb) shows the cleaning and tokenization procedure of the corpus. Additionally it also shows the verification of the empirical laws, like Zipf's law on this corpus.

## Building the 4 gram language model

[02-m-gram-language-model-prediction-and-generation.ipynb](02-m-gram-language-model-prediction-and-generation.ipynb) shows the procedure of building the 4-gram language model on this corpus. Additionally it also does next word prediction and sentence generation, and also does so conditionally based on POS tags.

## Building the word vectors

[03-building-word-vectors-with-coals.ipynb](03-building-word-vectors-with-coals.ipynb) shows the building of word vectors using *Co-occurance Analogue to Lexical Semantics*, a method to generate word vectors using co-occurance statistics. It also generates the words with the closest meanings.