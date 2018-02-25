# Hack Night 2018.02.25 Intro to R

Welcome RDS!  Today we will use R to train a decision tree for the Titanic Data Set.  

## Requirements

Before anything else, make sure you have Python and Jupyter set up on your
computer.  If you don't then download the [Anaconda Python
Distribution](https://www.anaconda.com/download/) (it will install nearly
everything we need and will make your life easier).



### 1. Getting Started with R

You can either open Jupyter notebooks and download the provided notebooks or simply open them in github and 
follow along in RStudio.

If you're not yet comfortable with Jupyter, check out [this guide (**Estimated
Time: 5-10min**)](https://compsci697l.github.io/notes/jupyter-tutorial/) for a
brief introduction, or grab someone from RDS and ask for some pointers!

If you aren't comfortable with RStudio,
this free first chapter of the datacamp course covers all of the basics.
https://www.datacamp.com/courses/working-with-the-rstudio-ide-part-1

Once you feel like you've gotten a decent grip on one of those tools, check out the
notebook here, [`intro-to-r.ipynb` (**Estimated Time:
10min**)](./intro-to-r.ipynb).  

### 2. Get Started manipulating data in R
http://r4ds.had.co.nz/transform.html
Hadley Wickham's online book Intro to Data Science in R is a fantastic resource.
To learn how to Tidy data go to Chapter 12:Tidy Data
To learn how to transform and manipulate Data go to Chapter 5: Data Transformation

Once you are comfortable with those tools, download the titanic data set 
and start playing around with it. 

If you are stuck or wan't to learn a little more about analyzing data, this [kaggle kernel](https://www.kaggle.com/etiennedumoulin/titanic-simple-intro-with-r) shows how one person 
began breaking down this data for the [Titanic: Machine Learning for Disaster Competition](https://www.kaggle.com/c/titanic),
an intro Kaggle Competition that taks data scienctists wth predicting who survived the titanic.

### 3. Machine Learning!!

Learn how random forests work with these tutorials:
[Implementation](https://www.tutorialspoint.com/r/r_random_forest.htm) 
[Intuition](https://www.kdnuggets.com/2017/10/random-forests-explained.html)

Then try it yourself on the titanic dataset.
I have provided a reference solution in the following notebook: 
[`random-forest.ipynb`](./random-forest.ipynb)

## 4.Take it one step further
How can we optimize random forests? Which features are useful?
Learn to fine tune your model with Caret.
[Picking the best model with caret](https://www.kaggle.com/rtatman/picking-the-best-model-with-caret)
