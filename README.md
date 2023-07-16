# Machine Learning Using Python - Decision Tree vs XGBoost
To predict students' performance:



1. Do students perform better in Morning class (before 12:00pm) or afternoon class? 
I conducted research from a dataset that shows students’ performance in 10 core classes in college. I wanted to know whether students perform better in morning class or afternoon classes. This can be for a number of reasons. For example, students that constantly take afternoon classes might work full-time during the day or might be raising a family. This can cause a decrease in a student's GPA due to stress and/or time constraints.
First, I needed to convert the letter grades into the grade point system: A being 4 points, B being 3, C being 2, D being 1 and F being 0. After, I should identify if the grade is associated with a morning class or afternoon class. After, I could compare using t-test two-sample assuming unequal Variances. I used unequal variance because the sample sizes are two different sizes.
With my research performed, I found that students perform better in morning classes (before 12pm). The morning class has a higher mean GPA at 2.71and a lower variance at 0.70.

2. Which Major has a higher quantitative class GPA?
Below I have mentioned the following majors that are included in the datasets for our analysis to reveal the class of with the highest GPA:
Accounting
Information Systems
Marketing
Finance
Management
Using the provided dataset I was able to identify which major has the highest GPA. I identified that the Marketing major has the highest GPA of 4.54468 from the rest of the indicated majors.

3. How to combine two dataset and build a classification model to predict if a student can graduate in time (Note: I could not use the last 2 semester’s performance to predict the graduation, since it is too late to predict the graduation)
For this question you can see final confusion matrix of both model (Decision Tree and XGBoost models) in python file.

