1) Title: Binary Classification Performance Evaluation with Data Correction

2) Abstract

    The article shows that Random Forests have a significantly higher predictive accuracy than logistic regression models. While the authors focus on comparing the performance       of statistical methods, namely Random Forests and three logistic regression versions in predicting civil war onset in out-of-sample data, we will focus on improving the         predictive performance of civil war onset. In this extension, we will explore methods to overcome the unbalance in the data classes. First, we will apply data correction         methods such as boosting and sampling on the same dataset used in the article, expecting to improve the logistic regression model’s accuracy. Then we will explore other           classifiers aiming to get the best possible predictive results on the corrected data. Cross validation is applied here as it produces unbiased and accurate error rates. In       assessing the predictive performance, we use the metrics, Confusion matrix, F1 score, Receiver Operating Characteristic Curve and AUC score.

3) Research Questions

    a) How correcting imbalanced datasets through boosting, sampling, and cost-sensitive methods can help improve the predictive performance of a classifier?
    
    b) How different classifiers (e.g SVM, KNN) perform on corrected imbalanced datasets?

4) Proposed dataset
    
    The main dataset we will use is the provided Civil War Data (CWD) dataset (`SambnisImp.csv`). It measures from 1945 to 2000 whether a civil war occured in a given country,       in  a given year. We will then use sampling methods on the dataset to try to overcome the dataset unbalance.

5) Methods

  a) Imbalanced data correction 
  
        i) Boosting techniques (AdaBoost/Gradient Boosting)
       ii) Sampling methods (Oversampling/Undersampling)
  
  b) Classifiers to test
  
        i) Logistic Regression
       ii) Random Forest
      iii) KNN
       iv) SVM
       
  c) Cross validation
  
  d) Assessment Metrics
  
        i) F1 score
       ii) Receiver operating characteristic curve
      iii) AUC score

6) Proposed timeline

    a) 1 week for data preprocessing, coming up with the algorithm and coding it. 
  
    b) 1 week for performance evaluation and running tests.
  
    c) 1 week for plotting results, preparing data story and pitching video.

7) Organization within the team

    a) Constantin: Problem formulation, coming up with the algorithm, crawling the data, writing up the data story/report.
  
    b) Graziano: Coding up the algorithm, preliminary data analysis, plotting graphs during data analysis, running tests.
  
    c) Yasser: plotting the graphs, Testing with different classifiers, tabulating final results, preparing the pitching video.

8) Questions for TAs (optional)

    a) Which of the 3 models should we implement our extension and evaluate on? 1) Fearon and Laitin (2003), 2: Collier and Hoeffler (2004), 3: Hegre and Sambanis (2006) or on         all   the 3 models?
  
    b) Do you have suggestions for data sampling methods? From your expertise do you know if we should better focus on some methods not all, because they generally work better?
