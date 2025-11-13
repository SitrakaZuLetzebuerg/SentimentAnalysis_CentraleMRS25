# Financial Sentiment Analysis

## Project Overview
This project focuses on performing sentiment analysis on financial news articles and market reports using advanced Natural Language Processing (NLP) techniques. By building and fine-tuning a custom model, we aim to classify financial texts as positive, negative, or neutral to provide actionable market insights.

## Objectives
- Analyze financial texts for sentiment classification.
- Build and fine-tune a model to detect market sentiment with high accuracy.
- Deliver meaningful insights to interpret market trends and investor behavior.

## Setup and Installation
To start working on this project, follow the steps below:

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/financial-sentiment-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd financial-sentiment-analysis
    ```
3. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Data Preprocessing and Preparation
The data is preprocessed to ensure it is clean and ready for model training:
- Text cleaning and normalization steps are performed to remove noise.
- Data is split into training, validation, and test sets to ensure robust model evaluation.

## Model Architecture and Training
The model is built using an advanced Transformer-based architecture, optimized and fine-tuned for financial sentiment classification tasks.

## Evaluation Metrics
Performance is measured using:
- Accuracy
- Precision
- Recall
- F1-Score

# Project Update

This project has shown significant improvements in text classification accuracy. Recent iterations achieved an accuracy exceeding 70%, with particularly strong performance in predicting **neutral** class instances. However, there is still room for enhancement in **positive** and **negative** class predictions. Various balancing techniques, regularization methods, and architectural optimizations have been applied throughout the process. The model continues to evolve, aiming for even better performance.

The current state of the project is promising, and further improvements will be explored in the future. Contributions and suggestions are always welcome.

## Future Improvements
- Additional data sources can be integrated to improve model generalizability.
- Different model architectures and optimization techniques can be explored for higher accuracy.

---
## Future Work & Improvements
- Expand the dataset with additional financial texts to enhance model generalizability.
- Experiment with different Transformer-based models for potential performance improvements.
- Explore multi-class sentiment classification and more granular sentiment categories.

# Conclusion
- To Conclude we can say that more infos are available on : https://huggingface.co/ProsusAI/finbert
- Bonus would be to show you guys this : https://bbycroft.net/llm
- And for those loving algebra : https://paulinamoskwa.github.io/blog/2025-11-06/attn

