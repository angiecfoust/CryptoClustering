# CryptoClustering

For this module assignment I used Python and unsupervised learning to predict if crtyptocurrencies are affected by 24-hour or 7-day price changes.

Method
After loading the csv file, StandardScaler (scikit-learn) was used to scale the data.
The elbow method was used to find the best k-value for the data.
The data was graphed using k-means clusters.
To view an alternative, a PCA was performed ont the original data to reduce the features to three principal components.
The eblow method was again used to find the best k-value for the PCA data.
The data was graphed using these clusters.
Lastly, a comparison between the two clusters was made.

Resources
Composite plot documentation: https://holoviz.org/tutorial/Composing_Plots.html
