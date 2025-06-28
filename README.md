Predicting India’s Olympic Performance with Machine Learning
Hi there! I'm Deepthi Reddy Kallam, and this project was part of my undergraduate journey at GRIET. Along with my teammates, I explored how data science and machine learning could help us understand why countries like India perform the way they do in the Olympics.

What’s this project about?
We looked into the question: "Why doesn’t India, despite its huge population and talent, win more Olympic medals?"
To find answers, we analyzed various factors—like GDP, literacy rate, health and education spending, undernourishment levels, and more—to see how they affect a country's chances of doing well in the Olympics.

Using machine learning, we built models to predict Olympic performance based on these indicators, hoping to offer insights that can inspire better sports policies in India.

What did we do?
Collected data from global sources for 227 countries, including India.

Cleaned and preprocessed the data (used KNN to handle missing values and normalized everything with a sigmoid function).

Applied regression models to predict medal counts:

Decision Tree Regressor

K-Nearest Neighbors (KNN)

Linear Regression

Random Forest

Bayesian Ridge Regression

What did we find?
The KNN regressor gave the most reliable results overall.

There’s a strong positive correlation between literacy rate, population, and medal count.

GDP, undernourishment, and income inequality (Gini index) also played a role, though not as strongly.

Surprisingly, health expenditure didn’t show a direct link to Olympic success, but it was linked to undernourishment.

Key Takeaway
Countries that invest in education, reduce malnutrition, and improve living standards tend to perform better in global sports. For India to climb the Olympic rankings, we need to treat sports as more than just a hobby—it has to become a national priority.

Tools and Technologies Used
Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Approach: Supervised learning (regression)
