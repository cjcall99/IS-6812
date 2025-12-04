# Business Problem

Many people struggle to get loans due to insufficient or non-existent credit histories leading to untrustworthy lenders taking advantage of this population. Home Credit doesn’t know how to select which individuals would be good potential clients with 100% accuracy. Giving loans to people who are incapable of repayment or not giving loans to capable individuals reduces revenue for Home Credit and limits opportunities for potential clients. 

# Solution to Business Problem

If Home Credit can accurately predict which individuals would be able to repay their loans, they could generate more revenue and help more individuals who struggle to get loans. Home Credit would also be able to ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.

We will look to create a model that will be able to help predict which clients Home Credit to loan to and what type of loans should be offered. We tested four different models and decided that our gradient boosted model will produce the most beneficial results.

# My Contribution

I collaborated with the the team and helped decide how we would like to shape the data before creating models. I created the random forest model and the gradient boosted model. The gradient boosted model gave us the highest AUC score on the training data so I proceeded to submit those predictions to the kaggle competition. During the presentation I spoke about these models, gave a individual example of what our model would predict, and calculated/described the business impact that our predictive model could bring to Home Credit.

The Private score we got was an AUC of .70126 and the public score was an AUC of .70297 when we submitted to the kaggle competition.

# The Business Value of our Solution

Our model gives a default probabilty score for every applicant regardless of missing credit history data. The Home Credit Team can then decide how risk averse they want to be with each individual.

To better understand how this model can benefit the business lets look at some numbers. 

Median Credit Amount - $450,000  
Default Rate - 8%  
Every person Expected default costs - $36,000 (450,000 * .08)  
Assume 100,000 applicants a year and we expect default losses totaling $3.6 Billion.

Using our model will help to reduce giving loans to bad clients and reduce millions (if not billions) of dollars of default money. Our model will also help to get loan money to trustworthy clients who don't have the typical credit history needed to get loans.

# Difficulties Encountered

There were a couple of difficulties that we encountered along the way. 

Collaborating with a team. It took time to figure out how to break up the work load while still making sure that everyone understood what was happening with our project. We also had to decide how to clean the data, which models to test, and how to best present our findings. Group calls and multiple text chains helped to overcome this.

Fixing model errors when the runtime of the models were lengthy. The Gradient boosted model took me many hours to create and get the code to run correctly. The work paid off as it generated the best performing model.

# What I Learned

Through this Capstone project I learned the importance of communicating early and often when you are part of a team. Many struggles and frustrations can be limited if you talk through you problems well before deadlines. 

I also learned that when dealing with big datasets you need to find ways to trim unuseful data to simplify what you are looking at and increase the speed of a model. There is no guarantee that one type of model will always perform better than others and many times some business decisions have to be made to decide what is really valueable in solving the business problem.

Lastly, taking time to really understand the data and what is being asked of you for a final product is very important. It is easy to waste many hours spinning your wheels on meaningless tasks if you don't properly understand what is being asked of you especially if your code takes a large amount of time to run.
