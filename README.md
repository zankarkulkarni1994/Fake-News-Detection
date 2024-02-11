Fake News Detector is an an application of Natural Language Processing for classifying News as Fake or real.
In this model I have used pretrained uncased BERT model from Hugging Face. BERT stands for Bidirectional Encoded representations from Transformer. It uses attention mechanism to read only relevant parts of the text. 
The relevance of words is determined using attention mechanism.
The BERT model converts the text into word embeddings which can be later fed to a down stream classifier for text classification.
For this project, I have used FCNN for downstream classifier.


Model Performance is as below:

Training Accuracy: 99.87%
Testing Accuracy: 98.97%
Classification Report:
               precision    recall  f1-score   support

           0       0.98      1.00      0.99      7006
           1       1.00      0.98      0.99      7302

    accuracy                           0.99     14308
   macro avg       0.99      0.99      0.99     14308
weighted avg       0.99      0.99      0.99     14308

AUC score: 0.989853260338812
Total time required for testing: 479.39638233184814
