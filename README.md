# Simple Hashtag Recommendation System Using TF-IDF

## Overview

This project implements a Simple Hashtag Recommendation System using Natural Language Processing (NLP) and TF-IDF vectorization. The system filters out verbs from the input text and recommends relevant hashtags based on the top terms extracted. The application is built using Python and is designed to run in Google Colab for easy access and usability.

## Features

- Filters out verbs from the input text.
- Recommends hashtags based on the top terms extracted using TF-IDF.
- Interactive frontend built with `ipywidgets` for seamless user interaction.

## Requirements

To run this project, you will need the following Python packages:

- `datasets`
- `scikit-learn`
- `spacy`
- `ipywidgets`

## Installation

1. Clone the repository or download the files.
2. Install the required packages by running:

   pip install -r requirements.txt
3.Download the SpaCy language model:

python -m spacy download en_core_web_sm
