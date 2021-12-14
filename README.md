# COVID Misinformation Text Classification Modelling

With Joy Zhang (Columbia University)

The outbreak of COVID-19 was accompanied by fake news and misleading posts on social media platforms around the world. That misinformation hinders epidemic prevention and control, foments xenophobia, and exacerbates the damage caused by the virus itself. To address this issue, we first conduct some exploratory analysis on the difference between fake news and real news. We then train eight machine learning models using various algorithms including Logistic Regression, Naive Bayes, Random Forest, SVM, AdaBoost, and a simple deep learning approach. We obtained the highest 94.1% accuracy score and 93.9% F1 score using the Logistic Regression model with count vectorization as the feature extraction method. 

**The second part of the repo contains code used for the winning entry to the 2021 AI Modelshare Competition where I used a [Tensorflow-BERT model](https://github.com/ltk2118/covid_misinformation/blob/main/AI_Modelshare_Competition_Code.ipynb) to predict fake COVID tweets with 97.3% accuracy and 97.3% F1 score.**

| **accuracy** | **f1 score** | **precision** | **recall** | **framework** | optimizer | loss rate |
| ------------ | ------------ | ------------- | ---------- | ------------- | --------- | --------- |
| 97.4%        | 97.4%        | 97.4%         | 97.4%      | keras-BERT    | Adam      | 1e-5      |

