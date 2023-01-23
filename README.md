# Online News Popularity
Main goal of my work was to find correlation between popular articles.

Starting off, I implemented the whole data set. Almost 40k of articles and 59 features included in.
My task was to sort out the not influencing features and check on the ones which has big impact on article popularity. Shown few histograms as well as scatter plots to visualize the main differences. Dividing the target value(amount of shares) to popular and not popular shows it in the most efficient way.

Scaling the data also helped a lot since the data set is not that small.
In the next steps you can see stuff like t-SNE and PCA to reduce dimensionality and implement clustering. 
One of the goal was to check the regression models on this data set. The outcomes can be seen and are not that much satisfying. I tried to increase the accuracy using SMOTE regression but could not get over one particular error.

