#Cyber Intrusions Identification with K-Means Clustering

An intrusion is an unauthorized action to access an IT&C resource by bypassing cyber security mechanisms.

The dataset includes a wide variety of information about simulated intrusions in a military network environment.

Only numerical characteristics were extracted from the dataset, such as: connection duration (in seconds), number of bytes transmitted from source to destination, number of urgent TCP packets, number of root accesses, etc. In total, the dataset has 38 features (columns) and 4,898,431 data (rows)

Intrusions fall into four broad categories:
1. DOS: denial-of-service
2. R2L: unauthorized access from a remote machine
3. U2R: unauthorized access to local superuser (root) privileges
4. probing: surveillance and other probing

The application aims to identify intrusions based on similarities between them.

Algorithms that calculate distances, such as K-means, are affected by the range of feature values.

Standardization is a data preparation method that involves adjusting the input (characteristics) by centering them (subtracting the mean from each data point) and then dividing by the standard deviation, resulting in the data having a mean of 0 and a standard deviation of 1 .

StandardScaler adjusts the data to have a standardized distribution, making it suitable for modeling and ensuring that no features disproportionately influence the algorithm due to differences in values.

Dataset: https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html
