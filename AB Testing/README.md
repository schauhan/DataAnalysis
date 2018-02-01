# A/B Testing #

In this project I have attempted to perform a regular A/B test to decide if the new_web_page is better in coverting the user than the old_web_page. For this project I was given one dataset which had datapoints for both the new and the old web pages. I have performed the analysis using two different approaches:
1. **A/B Testing** - Here I form the null and alternate hypothesis. In this case I create sampling distributions for the treatment and control pages (new and old web pages respectively). I compare the distribution mean with the null hypothesis mean to decide if the alternative hypothesis is definitely better than the null.
2. **Logistic Regression** - Here I perform simple logistic regression and see how much more the user is likely to convert if he/she is shown the new page.

I have included a small discussion about the comparison of the above two models. In the end I do a final regression analysis to check if the geographical region if the user has any correlation with the conversion rate for the new page.


### HTML file:
- [Analyze_ab_test_results_notebook.html]()

### Jupyter Notebook file:
- [Analyze_ab_test_results_notebook.ipynb](https://nbviewer.jupyter.org/github/schauhan/DataAnalysis/blob/master/AB%20Testing/Analyze_ab_test_results_notebook.ipynb)
