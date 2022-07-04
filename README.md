
# Indonesian Text Message Classification with LSTM

## Introduction

Short message service (SMS) is a communication service in text format that has become an embedded feature on every cellphone, be it a featured phone or smartphone. Since this service has advantages such as low cost and easy to use, this is also used by certain parties to send unwanted text message, namely spam message.

Spam is a type of message that is sent arbitrarily with various purpose such as promotions/advertising, announcements of sweepstakes and such so that they are disturbing to mobile phone users. Spam message itself has been found in many countries including Indonesia.

## Data

The text dataset used in this project was obtained in two ways which is by exporting messages from many phones and the second was obtained from here. Total data obtained are about one thousand sentence of data text. The dataset is grouped into three classes, namely normal/ham, scam/fraudulent, and promotion/advertisement text message.

## Goal

The goal of this project is to create LSTM model that can classify Indonesian text message into three categories that are mentioned above and implement it in an android texting app.

## Conclusion / Result

In this project, the model was able to be fitted with overall acurracy score of 0.92, F1-Score of 0.92, and ROC-AUC score of 0.94. The result of each class are presented below:
|Class|Recall|Precision|F1-Score|ROC-AUC|
|:---:|:---:|:---:|:---:|:---:|
|Normal|0.92|0.99|0.95|0.97|
|Scam|0.94|0.85|0.89|0.91|
|Promotion|0.88|0.92|0.90 |0.94|
|**Average**|**0.92**|**0.92**|**0.92**|**0.94**|

---
### You can check model [here](https://nbviewer.org/github/Layrin14/Indonesian-Text-Message-Classification-LSTM/blob/master/Indonesian_SMS_Classification_with_LSTM.ipynb)

