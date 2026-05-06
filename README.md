<h1>Fraud Detection - Machine Learining</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
The goal of this project is to investigate and detect counterfeit banknotes using machine learning and data visualization.This project uses the bill_authentication.csv dataset, which extracts four numerical features including variance, skewness, entropy, and kurtosis from the digital image of banknotes. And the target variable with class determines whether the banknote is fake or genuine. By analyzing this data, we can create models that can identify fake banknotes with high accuracy and reduce the risks of fraud.

<br />


<h2>Languages and Libraries Used</h2>

- <b>Phyton</b> 
- <b>Matplotlib</b>
- <b>Seaborn</b>


<h2>Program walk-through:</h2>



- <b>Data cleaning and preprocessing</b> 
- <b> Exploratory Data Analysis (EDA))</b>
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

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
