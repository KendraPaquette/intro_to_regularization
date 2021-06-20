Intro to Regularization with Kendra Wyant
=========================================

<iframe width="560" height="315" src="https://www.youtube.com/embed/MmxW1tcOgMc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>

What is Regularization?
=======================

Regularization is a type of regression that imposes a penalty to
coefficients in complex models. This penalty reduces overfitting by
introducing some bias into the model. As we see with the bias-variance
tradeoff, introducing some bias can reduce variance in model predictions
on new data making the model more generalizable.

**Types of regularization**  
\* Ridge regression: variables with minor contribution have their
coefficients close to zero. However, all the variables are incorporated
in the model. This is useful when all variables need to be incorporated
in the model according to domain knowledge. \* Lasso regression: the
coefficients of some less contributive variables are forced to be
exactly zero. Only the most significant variables are kept in the final
model. \* Elasticnet regression: the combination of ridge and lasso
regression. It shrinks some coefficients toward zero (like ridge
regression) and set some coefficients to exactly zero (like lasso
regression)

List of Related Topics/Ideas
============================

*We won’t be able to cover all of these topics due to time, but I will
provide resources and code for anyone who is interested in exploring
these further or using them in their own research. I am also happy to
chat more outside the workshop!*

-   Prediction vs Explanation in Psychology  
-   Overfitting  
-   Bias/variance tradeoff  
-   Test and training sets  
-   Cross-validation and resampling

Preparation
===========

Watch
-----

StatQuest Youtube Series  
1. Machine learning fundamentals – bias and variance (6:35)
<a href="https://www.youtube.com/watch?v=EuBBz3bI-aA" class="uri">https://www.youtube.com/watch?v=EuBBz3bI-aA</a>  
2. Ridge regression clearly explained (20:26) -
<a href="https://www.youtube.com/watch?v=Q81RR3yKn30" class="uri">https://www.youtube.com/watch?v=Q81RR3yKn30</a>  
3. Lasso regression clearly explained (8:18) -
<a href="https://www.youtube.com/watch?v=NGf0voTMlcs&amp;t" class="uri">https://www.youtube.com/watch?v=NGf0voTMlcs&amp;t</a>  
4. Elasticnet regression clearly explaines (5:18) -
<a href="https://www.youtube.com/watch?v=1dKRdX9bfIo" class="uri">https://www.youtube.com/watch?v=1dKRdX9bfIo</a>

Optional: Machine Learning Fundamentals: Cross Validation (6:04)
<a href="https://www.youtube.com/watch?v=fSytzGwwBVw" class="uri">https://www.youtube.com/watch?v=fSytzGwwBVw</a>

Read
----

1.  Skim the first 10 pages of Yarkoni and Westfall (2017)
    <a href="https://www.youtube.com/watch?v=1dKRdX9bfIo" class="uri">https://www.youtube.com/watch?v=1dKRdX9bfIo</a>  
2.  Read this blog post on overfitting
    <a href="https://www.ibm.com/cloud/learn/overfitting" class="uri">https://www.ibm.com/cloud/learn/overfitting</a>

Software
--------

-   We will be using R and RStudio
-   Install the following packages in RStudio:  
    install.packages(“tidyverse”)  
    install.packages(“tidymodels”)  
    install.packages(“kableExtra”)  
    install.packages(“skimr”)  
    install.packages(“naniar”)  
    install.packages(“doParallel”)  
    install.packages(“mlbench”)  
    install.packages(“vip”)  
    install.packages(“Matrix”)  
    install.packages(“glmnet”)

Additional Resources
====================

Coding
------

-   R for Data Science -
    <a href="https://r4ds.had.co.nz/" class="uri">https://r4ds.had.co.nz/</a>  
-   Tidyverse style guide -
    <a href="https://style.tidyverse.org/" class="uri">https://style.tidyverse.org/</a>  
-   Julia Silge blog -
    <a href="https://juliasilge.com/blog/" class="uri">https://juliasilge.com/blog/</a>  
-   Tidy modeling with R -
    <a href="https://www.tmwr.org/" class="uri">https://www.tmwr.org/</a>

Machine learning resources
--------------------------

-   Introduction to statistical learning -
    <a href="https://static1.squarespace.com/static/5ff2adbe3fe4fe33db902812/t/6009dd9fa7bc363aa822d2c7/1611259312432/ISLR+Seventh+Printing.pdf" class="uri">https://static1.squarespace.com/static/5ff2adbe3fe4fe33db902812/t/6009dd9fa7bc363aa822d2c7/1611259312432/ISLR+Seventh+Printing.pdf</a>  
-   Applied predictive modeling -
    <a href="https://vuquangnguyen2016.files.wordpress.com/2018/03/applied-predictive-modeling-max-kuhn-kjell-johnson_1518.pdf" class="uri">https://vuquangnguyen2016.files.wordpress.com/2018/03/applied-predictive-modeling-max-kuhn-kjell-johnson_1518.pdf</a>

**I am looking forward to meeting all of you on Wednesday. Please don’t
hesitate to reach out about anything
(<a href="mailto:kpaquette2@wisc.edu" class="email">kpaquette2@wisc.edu</a>).
I am happy to talk about data science, PREP, Madison, grad school, and
more!**
