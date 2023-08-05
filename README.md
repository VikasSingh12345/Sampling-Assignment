
## Sampling_Assignment
In this python code, we have used sampling techniques on a credit card fraud detection dataset and then applied various ML models on the dataset to find out which Model,sampling technique combination gives us the best accuracy.

Following 5 sampling Techniques were used:

1.Random Under Sampler (Sampling1)

2.Random Over Sampler (Sampling2)

3.TOMEK links (Sampling4)

4.SMOTE (Sampling3)

5.Near Miss (Sampling5)

The Sample size was calculates using the following formula: n = Z^2(p(1 – p)/m^2) where: n = sample size Z = z-value (for 98% confidence interval, Z = 4) p = proportion of the minority class (taken as 0.5 for a balanced dataset) m = margin of error (taken as 0.1 for a sample size of 1000)

Following 5 models were applied on the sampled dataset:

Decision Tree Classifier (M1)

Random Forest Classifier (M2)

KMeans (M3)

Support Vector Classifier (SVC) (M4)

Extra Tree Classifier (M5)

On execution of the code, following results were obtained: The cells of the table represent accuracy of the applied model using the respective sampling technique.


As we can see from the table the Maximum Accuracy obtained is of 99.57% on the following combinations:

## Output Table 

Results:

        Sampling1  Sampling2   Sampling3   Sampling4   Sampling5

    M1    37.50       48.71       48.71       48.71       33.62   
    M2    79.31       97.84       98.28       97.84       10.34   
    M3    68.97       99.57       99.57       99.57       56.90   
    M4    58.62       99.57       99.57       99.57       40.95   
    M5    65.95       99.57       99.57       99.57       34.48   
## Result

Decision Tree with Random Over Sampler, Smote and Tomek

Random Forest Classifier with Random Over Sampler, Smote and Tomek

KMeans Classifier with Random Over Sampler, Smote and Tomek

Support Vector Classifier with Random Over Sampler, Smote and Tomek

Extra Tree Classifier with Random Over Sampler, Smote and Tomek

Sampling models Random Over Sampler, Smote and Tomek are better
