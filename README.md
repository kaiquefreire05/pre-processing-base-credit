# pre-processing-base-credit

This notebook presents an exploratory analysis of a credit data set. The data set contains 2000 rows and 5 columns, with the columns:

 * clientid: Client identifier
 * income: Income
 * age: Age
 * loan: Debt
 * default: Debt payment

The exploratory analysis of the data set includes:

 * Data visualization: Through graphs and tables, it is possible to visualize the distribution of the data, identify outliers, and verify the existence of correlations between the variables.
 * Treatment of inconsistent values: Inconsistent values, such as negative ages, are treated to ensure data quality.
 * Treatment of missing values: Missing values are treated to ensure data integrity.
 * Division between predictors and class: The predictors are the variables that will be used to predict the class, which in this case is debt payment.
 * Scaling of values: The values of the predictors are scaled so that they have the same scale and weight in the analysis.
 * Division of training and test sets: The data set is divided into two parts: one part for training the model and another part for testing the model.

At the end of the exploratory analysis, the training and test data sets are saved in pkl format to be used in the next steps of the analysis.

RECOMENDATIONS FOR THE FUTURE

The exploratory analysis can be improved by including other analyses, such as:

 * Outlier analysis: It is possible to use more robust techniques for outlier identification, such as boxplot or z-score.
 * Correlation analysis: It is possible to use more robust techniques for correlation analysis, such as the Spearman or Kendall correlation coefficient.
 * Regression analysis: It is possible to use regression techniques to verify the relationship between the predictor variables and the class.
 * With these analyses, it is possible to gain a better understanding of the data set and improve the accuracy of the classification model.

SPECIFIC RECOMENDATIONS

In addition to the general recommendations listed above, here are some specific recommendations for improving the exploratory analysis of the credit data set:

 * Use more advanced visualization techniques: The notebook currently uses basic visualization techniques, such as bar charts and histograms. It would be beneficial to use more advanced techniques, such as scatter plots,     heat maps, and correlation matrices.
 * Analyze the data at different levels: The notebook currently analyzes the data at the individual level. It would be beneficial to analyze the data at different levels, such as the group level and the temporal level.
 * Use more advanced statistical techniques: The notebook currently uses basic statistical techniques, such as descriptive statistics and hypothesis testing. It would be beneficial to use more advanced statistical         
   techniques, such as multivariate analysis and time series analysis.

By following these recommendations, it is possible to improve the quality and insights of the exploratory analysis of the credit data set.
