<h1>Fraud Detection - Machine Learining</h1>


<h2>Description</h2>
The goal of this project is to investigate and detect counterfeit banknotes using machine learning and data visualization.This project uses the bill_authentication.csv dataset, which extracts four numerical features including variance, skewness, entropy, and kurtosis from the digital image of banknotes. And the target variable with class determines whether the banknote is fake or genuine. By analyzing this data, we can create models that can identify fake banknotes with high accuracy and reduce the risks of fraud.

<br />


<h2>Languages and Libraries Used</h2>

- <b>Phyton</b> 
- <b>Matplotlib</b>
- <b>Seaborn</b>


<h2>Program walk-through:</h2>



- <b>Data cleaning and preprocessing</b> 
- <b> Exploratory Data Analysis (EDA)</b>
- <b>Data visualization using Matplotlib and Seaborn</b>

- <b>Dataset splitting (training and testing sets)</b> 
- <b> Implementation of classification and regression models</b>
- <b>Model evaluation and performance analysis</b>




<h2>Program Data Visualization:</h2>

<p align="center">

data visualization from EDA is implemented,  helps to better understand  relationships between variables. First, the class distribution 
is examined, which shows that the number of counterfeit and genuine banknotes is balanced. This balance is important for machine learning
models while severe class imbalance can lead to biased predictions.Then, by drawing histograms and density graphs, the difference in their production in the two categories was examined. The results show that some features such as variance and skewness have high potential in distinguishing counterfeit banknotes from genuine banknotes.:  <br/>
<img src="https://i.imgur.com/YLOscjv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
o examine the relationship between features using a correlation heatmap. There were no strong correlations between features, indicating that these data were not suitable for multiple collinearity.
: <br/>
<img src="https://i.imgur.com/iNnEcsa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Visualize key insights with histograms
A histogram shows the explanation of each feature. Check data for normality
Identify skewness
:  <br/>
<img src="https://i.imgur.com/NbmEWIP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Tableu :</h2>
<br />
To examine the distribution of features in each class, we used box plots. These plots show the dispersion, median, and outliers of each feature in the two groups of counterfeit and real banknotes. This result shows that some features, especially variance and entropy, have significant differences between the two classes, which play an important role in the classification process.  <br/>
  <br/>
<img src="https://i.imgur.com/Wo15Klz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

A scatter plot is also constructed to examine the relationship between features such as variance and entropy. By assigning different colors to each class, the visual distinction between counterfeit and genuine banknotes is very clear.Interactive dashboards have also been used in the dashboards so that users can dynamically examine specific features or a class of banknotes. This interactivity allows us to delve deeper into the analysis and focus on high-risk cases. In addition, the results from the logistic regression are presented alongside the actual values to implement a visual comparison between the actual classification and the predicted values. This comparison helped to find misclassifications and complete the visual assessment of the model performance.  <br/>
  <br/>
   <br/>
<img src="https://i.imgur.com/uSOBDpx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<br/>
<img src="https://i.imgur.com/0Sw8FeQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Project Output :</h2>
This project showed that visual features extracted from scanned images using wavelet transform are good features for detecting counterfeit banknotes. Exploratory analysis shows a significant difference between variance and entropy and regression model, we used these differences for class prediction. Confusion matrix and classification report show that the model has high accuracy and low false negative error rate, which is important to prevent losses due to incorrect banknote detection.

  <br/>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
