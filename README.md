# Analyze-AB-Test-Results
Analyzing the results of an A/B test run by an e-commerce website to determine whether a new page increases user engagement (specifically successful user conversions) or not.  Initial datasets 'ab_data.csv' and 'countries.csv' are provided and analysis is performed in Python (version 3.7.3) and Jupyter notebooks while leveraging popular Python data analytics and data science packages: pandas, numpy, statsmodels, matplotlib and random. 
To arrive at our conclusions we employ different statistical methods including: 
1) calculating basic mean conversion rate for successful conversions versus total population of users who visited the new (aka 'treatment') versus the original (aka 'control') page.
2) hypothesis testing against a bootstrapped sample distrubtion to compare whether the p-value of our null hypothesis - that the original 'control' page is equally or more effective at generating user conversions than the new 'treatment' page - is less than our desired Type I (aka alpha) error rate of 5%. 
3) fitting a logistical regression model to see if there is a significant difference in conversion based on which page a customer receives.

# License
The contents of this repository are covered under the MIT License: https://github.com/jerrycyip/Analyze-AB-Test-Results/blob/master/MIT%20License.txt
