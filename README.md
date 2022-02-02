<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>

<h3 align="center"><a href = "https://www.udacity.com/course/predictive-analytics-for-business-nanodegree--nd008t"> Udacity Predictive Analytics for Business</a></h3>
<h4 align="center">Project IV: Predicting Default Risk</h4>


## Table of Contents
- [Project Overview](#project_overview)
- [Project Details](#details)
  - [The Business Problem](#the_BP)
  - [Steps to Success](#sts)
- [Project Submission](#submission)
- [Results](#results)
- [Licensing, Authors, and Acknowledgements](#licensing)

## Project Overview <a name="project_overview"></a>

You are a loan officer at a young and small bank (been in operations for two years) that needs to come up with an efficient solution to classify new customers on whether they can be approved for a loan or not. You'll use a series of classification models to figure out the best model and provide a list of creditworthy customers to your manager.
How Do I Complete this Project?

This project uses skills learned throughout the "Classification Models” course. To complete this project:

- Go through the course
- Apply the skills learned in the course to solve the business problem given in the project details section.
- Use our guidelines and rubric to help build your project.
- When you're ready, submit it to us for review using the submission template found in the supporting materials section.

<b>Skills Required</b>

In order to complete this project, you must be able to:

- Cleanup, format, and blend a wide range of data sources
- Build predictive classification models using Logistic Regression, Decision Tree, Random Forest, and Boosted Model


## Project Details <a name="details"></a>

### The Business Problem <a name="the_BP"></a>

You work for a small bank and are responsible for determining if customers are creditworthy to give a loan to. Your team typically gets 200 loan applications per week and approves them by hand. Due to a financial scandal that hit a competitive bank last week, you suddenly have an influx of new people applying for loans for your bank instead of the other bank in your city. All of a sudden you have nearly 500 loan applications to process this week! 

Your manager sees this new influx as a great opportunity and wants you to figure out how to process all of these loan applications within one week. Fortunately for you, you just completed a course in classification modeling and know how to systematically evaluate the creditworthiness of these new loan applicants. For this project, you will analyze the business problem using the Problem Solving Framework and provide a list of creditworthy customers to your manager in the next two days.

You have the following information to work with:

- Data on all past applications
- The list of customers that need to be processed in the next few days

### Steps to Success <a name="sts"></a>
<b>Step 1: Business and Data Understanding</b>

Your project should include a description of the key business decisions that need to be made.

</b>Step 2: Explore and Cleanup the Data</b>

To properly build the model, and select predictor variables, you need to explore and cleanup your data.

Here are some guidelines to help you clean up the data:

- Are any of your numerical data fields highly-correlated with each other? The correlation should be at least .70 to be considered “high”.
- Are there any missing data for each of the data fields? Fields with a lot of missing data should be removed
- Are there only a few values in a subset of your data field? Does the data field look very uniform (there is only one value for the entire field?). This is called “low variability” and you should remove fields that have low variability. Refer to the "Tips" section to find examples of data fields with low-variability.
- Your clean data set should have 13 columns where the Average of Age Years should be 36 (rounded up)

Note: If you decide to impute any data field, for the sake of consistency in the data cleanup process, impute the data using the median of the entire data field.

<b>Step 3. Train your Classification Models</b>

You should choose 70% to create the Estimation set and 30% to create the Validation set. Set the Random Seed to 1 if you're using Alteryx.

Train your dataset using these models:

- Logistic Regression
- Decision Tree
- Forest Model
- Boosted Tree

<b>Step 4. Writeup</b>

Compare all of the models’ performance against each other. Decide on the best model and score your new customers.

<b>Important:</b> Your manager only cares about how accurate you can identify people who qualify and do not qualify for loans for this problem.

Write a brief report on how you came up with your classification model and write down how many of the new customers would qualify for a loan.

## Project Submission:<a name="submission"></a>
To complete this project, you will be submitting a file in pdf format that contains the answers to the following questions.

## Results: <a name="results"></a>
All the results(including graphs) are in the <a href="https://github.com/Abhishek20182/Predicting-Default-Risk/blob/main/Report.pdf">Report.pdf</a> File.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Udacity to providing this data. You can find the Licensing for the data and other descriptive information at Udacity Page.
