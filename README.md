# python_EDA_human_body_temp

### Background
The mean normal body temperature was held to be 37∘C or 98.6∘F for more than 120 years since it was first conceptualized and reported by Carl Wunderlich in a famous 1868 book. But, is this value statistically correct?

### Exercises
In this exercise, you will analyze a dataset of human body temperatures and employ the concepts of hypothesis testing, confidence intervals, and statistical significance.

Answer the following questions in this notebook below and submit to your Github account.

1. Is the distribution of body temperatures normal?
- Although this is not a requirement for the Central Limit Theorem to hold (read the introduction on Wikipedia's page about the [CLT](https://en.wikipedia.org/wiki/Central_limit_theorem) carefully: it gives us some peace of mind that the population may also be normally distributed if we assume that this sample is representative of the population.
- Think about the way you're going to check for the normality of the distribution. Graphical methods are usually used first, but there are also other ways: https://en.wikipedia.org/wiki/Normality_test
2. Is the sample size large? Are the observations independent?
- Remember that this is a condition for the Central Limit Theorem, and hence the statistical tests we are using, to apply.
3. Is the true population mean really 98.6 degrees F?
- First, try a bootstrap hypothesis test.
- Now, let's try frequentist statistical testing. Would you use a one-sample or two-sample test? Why?
- In this situation, is it appropriate to use the t or z statistic?
- Now try using the other test. How is the result be different? Why?
4. Draw a small sample of size 10 from the data and repeat both frequentist tests.
- Which one is the correct one to use?
- What do you notice? What does this tell you about the difference in application ofmthe t and z statistic?
5. At what temperature should we consider someone's temperature to be "abnormal"?
- As in the previous example, try calculating everything using the boostrap approach, as well as the frequentist approach.
Start by computing the margin of error and confidence interval. When calculating the confidence interval, keep in mind that you should use the appropriate formula for one draw, and not N draws.
6. Is there a significant difference between males and females in normal temperature?
- What testing approach did you use and why?
-Write a story with your conclusion in the context of the original problem.


You can include written notes in notebook cells using Markdown:

In the control panel at the top, choose Cell > Cell Type > Markdown
Markdown syntax: http://nestacms.com/docs/creating-content/markdown-cheat-sheet
Resources
Information and data sources: http://www.amstat.org/publications/jse/datasets/normtemp.txt, http://www.amstat.org/publications/jse/jse_data_archive.htm
Markdown syntax: http://nestacms.com/docs/creating-content/markdown-cheat-sheet
