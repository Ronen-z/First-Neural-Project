# Arabic Sentiment Analysis using Transformers

This project aims to build a transformer model from scratch that performs sentiment analysis on an Arabic data.

## Installation

There are 5 notebooks (Scraping, PreProcessingEnglish, Translation, PreProcessingArabic, Transformer_Model)
There are also multiple csv files which are created using the notebooks

## Usage

Scarping -> Scrapes english reviews from trustpilot platform and puts them in a csv file.

PreProcessingEnglish -> Contains preprocessing for the scraped english dataset.

Translation -> Uses the marefa-nlp pre-trained model to translate the reviews to arabic.

PreProcessingArabic -> Contains preprocessing for the translated arabic dataset.

Transformer_Model -> Builds the transformer model from scratch and trains it using the preprocessed arabic dataset.
