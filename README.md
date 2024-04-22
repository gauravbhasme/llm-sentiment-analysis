# Sentiment analysis using Large Language Model (LLM)

## Overview

This project implements a system using a pre-trained large language model called Mistral. The evaluation is conducted on the IMDB movie review dataset, where sentiment analysis is performed on individual movie reviews.

## Running the Application on Google Colab

1. Open the provided Jupyter Notebook file (`llm_evaluation.ipynb`) in Google Colab.

2. Ensure that you have a Google account and are logged in to Google Colab.

3. Execute each cell in the notebook sequentially by clicking the play button or pressing `Shift + Enter`.

4. Follow the instructions provided in the notebook for any necessary configurations or inputs.

5. Once all cells have been executed, you will see the output and results of the evaluation process.

## Dataset and Model

- **Dataset:** The IMDB movie review dataset is used for evaluation. It contains movie reviews labeled with sentiment (positive or negative). The dataset can be obtained from [here](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data).

- **Model:** The Mistral model, a pretrained Language Model (LLM), is utilized for sentiment analysis. It is loaded using the Transformers library from Hugging Face.

## Evaluation Metrics

The model's performance is evaluated using standard classification metrics such as accuracy, precision, recall, and F1-score. These metrics provide insights into the model's effectiveness in sentiment analysis tasks.

## Conclusion

This project demonstrates the process of automatically evaluating a Language Model's performance using a pretrained model and a labeled dataset. By running the provided notebook on Google Colab, users can easily replicate the evaluation process and analyze the model's performance.
