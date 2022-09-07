# R-Data-Analysis

Below are descriptions & html file links to some data analysis projects that I did for Uni (course: Data Analytics). I also attached the respective .rmd notebooks and datasets (as a backup, should the web-source not be available anymore) in the respective repository folders. The projects can thus be simply replicated in RStudio. 

Project 1.:
- Task was a descriptive Analysis of U.S. College Data from Iowa.
- After preprocessing, I programmed a linear regresison model (both a basic one and one with feature engineering/split per college typ)
- I then did a stepwise variable selection based on AIC.
- Lastly, I split into training & test data-set, normalized the data & applied a knn (K-nearest-neighbor) regression

🔗to the html file: https://tinyurl.com/college-data-exploration

Project 2:
- The aim of the project was to analyse the customer turnover or churn of a telecommunications company.
- After an exploratory analysis, I did a basic logistic regression with all variable and did a step-wise variable selection for an optimized model
- I then compared both model's churn probability, accuracy, recall, precision & F1 scores
- Lastly, as a bonus, I also tried to improve the model via a cutoff point selection

🔗to the html file: https://tinyurl.com/customerschurnprediction

Project 3:
- This was a continuation of project 2 with different types of models employed.
- Build a classification tree on the training sample (optimally pruned)
- From this tree chose variables for the split
- Compared the logistic regression, classification tree and random forest models on accuracy, recall and precision (on the test sample)

🔗to the html file: https://tinyurl.com/customerchurnprediction2

Project 4:
- The goal of the analysis was to perform customer segmentation using cluster analysis for an online retailer based on the RMF ("Recency, Frequency, Monetary Value") strategy.
- Visualized the data - pair plots for the 3 variables (for 3d graph plotly package used)
- Performed clustering using k-means, hierarchical clustering and dbscan.
- Interpreted the groups.

🔗to the html file: https://tinyurl.com/rmfanalysis
