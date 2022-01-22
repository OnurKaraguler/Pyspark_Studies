## Adult income dataset

An individual’s annual income results from various factors. Intuitively, it is influenced by the individual’s education level, age, gender, occupation, and etc.

Fields<br>
The dataset contains 16 columns<br>
Target filed: Income<br>
-- The income is divide into two classes: <=50K and >50K<br>
Number of attributes: 14<br>
-- These are the demographics and other features to describe a person<br>

We can explore the possibility in predicting income level based on the individual’s personal information.<br>

The study consists of:<br>
  (1) Functions to be used<br>
      <ul>
        <li>1.1 Pyspark</li>
        <li>1.2 Visualizations</li>
        <li>1.3 Confusion matrix and metrics </li>
      </ul>
  (2) Importing Libraries<br>
  (3) Initialize Spark and Load Data<br>
  (4) Exploratory Data Analysis (EDA)<br>
      <ul>
        <li>4.1 Analyze each feature</li>
      </ul>
  (5) Machine Learning Algorithms and Results<br>
      <ul>
        <li>5.1 String Indexer</li>
        <li>5.2 Vector Assembler</li>
        <li>5.3 Feature engineering</li>
          <ul>
            <li>5.3.1 Check categorical Features</li>
            <li>5.3.2 Constant and quasi constant features removal</li>
            <li>5.3.3 Drop highly correlated features using Pearson Correlation</li>
          </ul>
        <li>5.4 Correlation of the features</li>
        <li>5.5 Over-sampling using SMOTE</li>
        <li>5.6 Normalization</li>
        <li>5.7 Building ML models</li>
          <ul>
            <li>5.7.1 Logistic Regression</li>
            <li>5.7.2 Decision Tree Classification</li>
            <li>5.7.3 Random Forest Classification</li>
            <li>5.7.4 Naive Bayes Classification</li>
            <li>5.7.5 Gradient-Boosted Tree Classification</li>
            <li>5.7.6 Linear Support Vector Machine</li>
          </ul>
        <li>5.8 Model selection - final</li>
        <li>5.9 Evaluation of the selected model</li>
          <ul>
            <li>5.9.1 ROC Curve</li>
            <li>5.9.2 TPR & TNR - Threshold Curves</li>
            <li>5.9.3 Precision(PPV)&NPV - Recall Curves</li>
            <li>5.9.4 Accuracy - Threshold Curves</li>
          </ul>
      </ul>

