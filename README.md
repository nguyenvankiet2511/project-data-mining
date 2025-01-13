# Project Data Mining

Using the C# programming language to develop applications that help explore algorithms related to data mining, such as clustering, association rules, classification, and more.

# Main Algorithms

### 1. Clustering Algorithms
- **K-Means and K-Means++**: Classic clustering algorithms that partition data into groups based on similarity.
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**: Groups points based on density, effective for data with noise and arbitrary cluster shapes.
- **Mean-Shift**: A non-parametric algorithm that finds dense regions in data.

### 2. Association Rule Mining Algorithms
- **Apriori**: Identifies frequent itemsets and generates association rules based on support and confidence thresholds.
- **Eclat**: Uses a vertical database format to mine frequent itemsets.

### 3. Classification Algorithms
- **Decision Tree**: A tree-structured model for decision-making and classification.
- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem.
- **K-Nearest Neighbors (KNN)**: Classifies a data point based on the majority label of its nearest neighbors.
- **N-Layer (KNN)**: Analyze the dataset with labels in the same data set using the KNN algorithm.
# Prepare the data.
### 1. Clustering Algorithms
Consider a data point with two attributes: x-coordinate and y-coordinate.
Example:
3.4, 6.1
12.3, 8.9
……
1.8, 1.5
For instance, 3.4, 6.1 → The first data element has coordinates x = 3.4, y = 6.1."
### 2. Association Rule Mining Algorithms
The data file for this application is also a text file with the basic content as follows:
Example:
0,0,1,1,1  
1,1,0,1,0  
1,0,0,1,0  
1,1,1,1,0  
……..  
0,1,0,1,1  
Note that, for simplicity, we will fix the number of items in this application to always be 5, represented by A, B, C, D, and E. Similar to Application 1, we also set a limit of a maximum of 20 invoices.
For example:
The first line 0,0,1,1,1: Invoice 1 contains items C, D, and E.
### 3. Classification Algorithms
The data file used for this application will be structured as follows:
**Attributes:**
Gender (1: Male, 0: Female)
Age (1: 18-25, 2: 26-35, 3: 36-50, 4: 51 and above)
Income: an integer representing monthly income in million VND (e.g., 5, 16)
Loan Amount: an integer in million VND, representing the amount the customer has borrowed.
Rating: the classification result, with two possible values: T (good) and X (bad)
Here are a few lines of data in the PhanLop.txt file:
1, 2, 5, 20, T  
1, 3, 12, 100, X  
0, 2, 21, 30, T  
…………  
0, 1, 10, 25, T  
For example:
Line 1: The borrower is male (1), in the age range 26-35, with a monthly income of 5 million VND, has borrowed 20 million VND, and then repaid the principal and interest on time (T).

  








