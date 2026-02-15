# Yelp Sentiment Analysis Project

## Objective
The goal of this project is to perform sentiment analysis on Yelp restaurant reviews using a 5-class classification task and outperform a fine-tuned BERT baseline.

## Dataset
We used the Yelp Review Full dataset from Hugging Face.  
The training split was used for training and validation, while the test split was strictly reserved for evaluation.

## Preprocessing
- URLs were removed
- Extra whitespaces and line breaks were normalized
- Texts were truncated to a maximum length of 256 tokens based on text length distribution

## Model
We fine-tuned a DistilRoBERTa-base model for sequence classification with 5 output classes.  
DistilRoBERTa was chosen as a trade-off between performance and training speed.

## Training Setup
- GPU: NVIDIA V100
- Mixed precision training (fp16)
- Batch size: 16
- Learning rate: 2e-5
- Number of epochs: 1

## Results
- Training time: XX minutes
- Precision, Recall, F1-score (weighted)
- Confusion matrix analysis

## Discussion
Most errors occur between neighboring sentiment classes (e.g. 3 vs 4 stars).  
With more time, performance could be improved by training for more epochs or using a larger model.