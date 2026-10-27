# AI-Based Sentiment Analyzer

## Project Overview

The AI-Based Sentiment Analyzer uses a pretrained Natural Language Processing model to classify English product reviews and social media comments. It provides predicted sentiment labels and model confidence scores.

## Features

* Single-review sentiment analysis
* Batch analysis of CSV files
* Positive and negative sentiment predictions
* A simplified neutral category for low-confidence predictions
* Confidence score display
* Interactive sentiment distribution charts
* CSV report export
* Gradio web interfaces

## Technologies Used

* Python
* Hugging Face Transformers
* PyTorch
* Pandas
* Plotly
* Gradio
* Google Colab

## Model

The project uses the pretrained DistilBERT SST-2 sentiment classification model from Hugging Face.

## How to Run

1. Open `AI_Based_Sentiment_Analyzer.ipynb` in Google Colab.
2. Run the installation and import cells.
3. Load the pretrained model.
4. Run the sentiment analysis and visualization cells.
5. Launch the Gradio interfaces.
6. Test individual reviews or upload a CSV file.

## Limitations

The pretrained model is designed for binary positive/negative sentiment classification. The neutral category is assigned using a confidence threshold and should not be interpreted as a reliable neutral sentiment prediction. Results can be inaccurate for sarcasm, mixed opinions, slang, and text outside the model's intended domain.

## Privacy

Use public or synthetic reviews for demonstrations. Do not publish confidential customer data.
