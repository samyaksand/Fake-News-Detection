# Fake-News-Detection

## Aim
This project aims to build a fake news classifier that can accurately distinguish fake news from genuine news. We also developed a simple UI, to enable the users to efficiently verify news articles

### Technologies Used:
- Frontend -  HTML, CSS, Javascript for building the webapp
- Backend - Flask, for running the localhost
- Framework - Jupyter Notebook for Machine learning & deep learning models
- Open Source Environment - Spyder 

#### Dataset: 20,800 samples with 10387 real news,10413 fake news. Dataset is publically available [here](https://www.kaggle.com/c/fake-news/data)

### Machine Learning / Deep Learning Algorithms used
    1. Naive Bayes 
    2. Decison Tree
    3. SVM (Support Vector Machine)
    4. TF-IDF Tokenizer with Passive Aggressive Classifier
    5. BERT
  
<div align="center">
<img src= "https://imgur.com/Qou6VYy.png" ><p>Figure 1: Pipeline of the approach used</p>
</div>

### Pipeline & Output:
### a) Main Model 1: BERT Tokeniser with Bert model
<div align="center">
<img src= "https://imgur.com/OnbSNca.png" ><p>Figure 2: Pipeline for BERT Tokeniser with Bert model</p>
</div>

### b) Main Model 2: TF-IDF Tokenizer with Passive Aggressive Classifier
<div align="center"> 
<img src= "https://imgur.com/f6cgGfC.png" ><p>Figure 3: Pipeline for TF-IDF Tokenizer + Passive Aggressive Classifier</p>
</div>

## WebApp:

### [https://samyaksand-fakenewsnlp.pythonanywhere.com/](https://samyaksand-fakenewsnlp.pythonanywhere.com/)
- An end-to-end deployed tool which allows user to verify news articles in a click. 
- This project is the first step toward creating a data protection mechanism to protect against the spreading of fake news on social networks. The outcome of this research is proposed to be essential to designing innovative online social networks.

#### Features 
1. Users can enter input directly.
2. Users can load random news articles
3. Users can see the text processing pipeline live.

#### [Presentation Slides](https://docs.google.com/presentation/d/12JnonlKkk62ftw1ivorXuGvs-MuHm64a/edit?usp=sharing&ouid=115677275615206191517&rtpof=true&sd=true)

