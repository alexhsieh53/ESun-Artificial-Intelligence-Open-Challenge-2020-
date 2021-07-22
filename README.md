# ESun-Artificial-Intelligence-Open-Challenge-2020
Solution of 4th Place in ESun-Artificial-Intelligence-Open-Challenge-2020

Flow of AML Detector
![image](https://user-images.githubusercontent.com/11289421/126606984-3dd585b2-213e-4ab7-921a-28b30b64b3fe.png)

•	Used Roberta as the backend to develop classification and name tagging model in PyTorch to extract criminal’s name from the news article
NewsClassifier.ipynb is the training file of classification model of News Article. Used Transformer's BertForSequenceClassification to train it.
bertTrain_v2.ipynb is the training file of name tagging model of News Article. Used Transformer's BertForTokenClassification to train it.

•	Deployed model with flask web framework on the Azure platform

amldetector.py is the inference flask service
