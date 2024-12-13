# BERT Finetuning for Sentiment Analysis
Finetuning BERT base model for clear sentiment analysis and retraining finetuned model for handling sarcastic data

## As indicated by BertBaseModel, we should be Training the model before using it for predictions and inference
##### Below is result of using without proper training
![image](https://github.com/user-attachments/assets/1d590079-db63-4ab9-857f-74f7652776c8)

## With training/finetuing the model with dataset with possible sentiments(IMDB reviews), below are results
##### Label - 0 => Negative sentiment
##### Label - 1 => Positive sentiment
![image](https://github.com/user-attachments/assets/8846e242-3de6-4fa1-af30-b2ac3be00393)
###### => Still the edge cases with sarcastic data is getting worngly labeled.

## With re-training the model on dataset with sarcastic datas properly tagged with right labels, below are results
![image](https://github.com/user-attachments/assets/907703f9-e990-42b6-92b8-ac7e385a08bf)

