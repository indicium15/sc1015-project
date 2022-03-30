# sc1015-project
## About
This is a mini-project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on evaluating the effectiveness of Machine Learning Models for classifying Fake News Headlines.
## Contributors
- @hyunsunryu2020: Hyunsun Ryu - Data Cleaning and EDA 
- @pravindkk: Pavind Kumar - Model Building
- @indicium15: Chaitanya Jadhav - Model Evaluation
## Problem Definition
- Are we able to apply Natural Language Processing to classify the headline of a news article as being fake or real?
- Based on the model we have, how can we improve its accuracy and effectiveness?
## Model Used
- LTSM Model
## Conclusions
- The LSTM model is a good base for classifying headlines
- Our model is good at classifying fake news but bad at classifying true news due to the nature of our data and the linguistic nature of the headlines
- There are improvements that can be made to our current model to improve accuracy
## Skills Learned
- Collaboration using GitHub and Google Collab
- How to clean text data
- How to draw insights from text data
- New evaluation metrics for Binary Classification Models
- Understanding the working behind LSTM model
- Understanding why our model is good at classifying fake news and why it is bad at classifying real news
- Understanding the shortcomings in our train data and how to improve model accuracy
## References
### Datasets:
1. [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
2. [Onion or Not?](https://www.kaggle.com/datasets/chrisfilo/onion-or-not)
3. [Buzzfeed Political News Data](https://github.com/BenjaminDHorne/fakenewsdata1)
4. [ABC News Headlines](https://www.kaggle.com/datasets/therohk/million-headlines)

### Evaluation Metrics:
1. [ROC Curve](https://machinelearningmastery.com/roc-curves-and-precision-recall-curves-for-imbalanced-classification/)
2. [Advanced Evaluation Metrics for Binary Classification](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-019-6413-7#Sec8)
3. [Matthews Correlation Coefficient](https://biodatamining.biomedcentral.com/articles/10.1186/s13040-021-00244-z#Sec16)
4. [Introduction to Transfer Learning](https://machinelearningmastery.com/transfer-learning-for-deep-learning/)