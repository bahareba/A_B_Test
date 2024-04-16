# <span style='color:darkorchid'> A/B test for Facebook ads </span>

## Project Overview

We run 2 different ads on Facebook.Based on the collected data, we draw a conclusion about which version of Facebook advertising brings more revenue and conversion to purchase.


<br> This project has 4 parts:
* Business Problem
* Data Undrestanding
* Modeling and Evaluation
* Conclusion



 
## Part 1: Business Problem
<img src="images/problem_10266358.png" width="100" height="100" align=left  >

* The Business launched an A/B test in order to increase income. The data contains raw data on the results of the experiment (user_id), sample type (variant_name) and income brought by the user (revenue).

* The task is to analyze the results of the experiment.

<span style='color:indigo'> We will consider 2 hypothesis:
<br> 1. Did the ad lead to more views?
<br>  2. Did the treatment group generate more income? </span>



## Part 2: Data Understanding


<img src="images/survey_10266430.png" width="100" height="100" align=left  >



### Number of users are less than number of records. It shows some users have seen both versions of ads.
### Based on the box plot there are lot of outliers in data. By considering the threshold of 50, we'll remove outliers.




<br>


## Part 3: Modeling and Evaluation
<img src="images/creative-writing_10266412.png" width="100" height="100" align=left  >


Hypothesis 1: Number of views
Chi-Square Test: Since we're comparing categorical data (watched ad or not watched) between two groups (control and treatment), a Chi-Square test (chi2_contingency) is suitable to assess.

Hypothesis 2: number of purchases





<br>

## Part 4: Conclusion
<img src="images/value_10266329.png" width="100" height="100" align=left  >
The A/B test results indicate that neither of the ads (A and B) showed a statistically significant impact on the number of visitors or average revenue compared to the other. Both ads performed similarly in terms of attracting visitors and generating revenue.

## Recomendations:
* Refinement of Ads: Analyze the content, design, and targeting parameters of both ads to identify elements that could be optimized for better results. This could include testing different ad creatives, headlines, call-to-action buttons, or audience segments.
* Explore Other Channels: Consider diversifying advertising efforts by exploring other digital marketing channels or platforms where the target audience may be more receptive. Experiment with platforms such as Google Ads, Instagram, or LinkedIn to reach a broader audience and compare performance across different channels.
