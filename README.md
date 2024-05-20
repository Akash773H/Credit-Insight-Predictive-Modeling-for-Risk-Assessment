# Credit-Insight-Predictive-Modeling-for-Risk-Assessment
This project involves assessing credit worthiness using a toy dataset. The dataset includes the following features: Age (range 19-75), Gender (Male or Female), Job (USK- Unskilled, SK- Skilled, HSK- Highly Skilled), Housing (Own or Rent), Savings Account (Little, Moderate, and Rich), Credit Amount (in $), Duration (in months), and Risk (Good or Bad).

I converted all the categorical data into binary values (0's and 1's) and developed a logistic regression model using the Excel Data Analysis Toolpak. To calculate the probability, I used the formula Exp()/(1+Exp()). For decision-making, I set a threshold of 0.65 using the IF function—if the calculated probability exceeded 0.65, credit would be granted; otherwise, it would be rejected.

After the model was ready, I used the multilinear regression formula to calculate the regression value for the next customer based on the intercept and coefficient values obtained from the regression model. I then used a confusion matrix to check the accuracy of my model, which is 69.30%. This project demonstrates the application of logistic regression for credit risk assessment.
