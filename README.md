# Udacity_ds_blogpost
## Hello, This is the 1st Project in Udacity's Data Science Program of AnTTQ

### Table of content
1. [Libraries Used](#libs)
2. [Project Motivation](#motivation)
3. [Project CRISP-DM process outlier](#outlier)
3. [Project Structure](#files)
4. [Project Summary](#summary)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Libraries Used <a name="libs"></a>
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>
For this project, I was interestested in using Stack Overflow data from 2017 to better understand:

1. Does career or job satisfaction have correlation with developer's salary?
2. Do developers have higher education get higher salary?
3. If the above question is true, which factors contribute to the satisfaction?
4. Could taking skill course in bootcamps help developer increase their salaries?

## Project CRISP-DM process outlier <a name="outlier"></a>
This project follow to the CRISP-DM process, which require:
1. Business Understanding
    a. Brief description: An analysis base on data of StackOverflow's survey 2017 about ưhat make impact on developer salary, how to increase that.
    b. Question 1: Does career or job satisfaction have correlation with developer's salary?
    c. Question 2: Do developers have higher education get higher salary?
    d. Question 3:If the above question is true, which factors contribute to the satisfaction?
    e. Question 4: Could taking skill course in bootcamps help developer increase their salaries?
2. Data Understanding
    Access and Explore: Load dataset into pandas dataframe and visualize its statistic
3. Prepare Data
    a. Wrangle and Clean: Remove records with nan Salary
4. Question 1
    a. Analyse
    b. Visualise
    c. Explain the visualisation
5. Question 2
    a. Analyse
    b. Visualise
    c. Explain the visualisation
6. Question 3
    a. Analyse
    b. Visualise
    c. Explain the visualisation
7. Question 3
    a. Analyse
    b. Visualise
    c. Explain the visualisation
8. Evaluation
    Findings: Job/Career Satisfaction, Education Degree contribute to Salary. StackOverflow Satisfaction, HoursPerWeek, HomeRemote have impact on Job/Career Satisfaction. And Bootcamp skills courses make no salary improvement. 

## Project Structure <a name="files"></a>

There is a notebook here to showcase work related to the above questions. The notebook is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There is an additional `.py` file that runs the necessary code to obtain the final model used to predict salary.

## Project Summary<a name="summary"></a>

The main findings of the code can be found at the post available [here](https://anttq.blogspot.com/2022/09/do-high-paid-employees-truly-satisfy.html).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).


