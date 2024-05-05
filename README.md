
# Twitter tweets emotion classification

Emotion classification of tweets using Machine Learning and Deep Learning techniques


## Dataset Description
"Emotions" dataset – a collection of English Twitter messages meticulously annotated with six fundamental emotions: anger, fear, joy, love, sadness, and surprise. This dataset serves as a valuable resource for understanding and analyzing the diverse spectrum of emotions expressed in short-form text on social media.

Each entry in this dataset consists of a text segment representing a Twitter message and a corresponding label indicating the predominant emotion conveyed. The emotions are classified into six categories: sadness (0), joy (1), love (2), anger (3), fear (4), and surprise (5).

[Dataset Link](https://www.kaggle.com/datasets/nelgiriyewithana/emotions/data)
## Model Summary

Using 10k rows
| Model | Accuracy |
|-------|----------|
|Random Forest Classifier| 54%|
|CNN|84%|
|RNN|84%|

Using 30k rows
| Model | Accuracy |
|-------|----------|
|cardiffnlp/twitter-roberta-base-sentiment-latest| 94%|

Using entire data
| Model | Accuracy |
|-------|----------|
|RNN|92%|
