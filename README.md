# Credit-Card-Fraud-Detection
The rapid growth of credit card transactions has brought convenience to consumers and businesses alike, but it has also led to a significant rise in fraudulent activities. Our project, Credit Card Fraud Detection, leverages advanced Machine Learning techniques to identify and prevent fraudulent transactions, thus safeguarding financial systems and personal information.

**Problem Statement:** Credit cards are ubiquitous in modern society, serving as a convenient tool for making purchases and accessing financial services. Each card carries unique information such as the cardholder's name, picture, signature, and most importantly, the credit card number. The security of these transactions relies heavily on both the physical security of the card and the confidentiality of the credit card number. With the surge in credit card usage, there has been a corresponding increase in fraudulent activities, leading to substantial financial losses. Therefore, detecting fraud through efficient and secure methods is crucial to mitigate these risks and protect consumers.

**Tasks To Be Performed:**
1. Loading the Dataset: We used the Pandas module to load the dataset containing transaction details.
2. Missing Value Analysis: We analyzed the dataset to identify and handle any missing values.
3. Transaction Analysis: We calculated the number of genuine and fraudulent transactions, and determined the percentage of fraud transactions.
4. Data Visualization: Using Matplotlib, we visualized genuine and fraudulent transactions with a bar graph to understand their distribution.
5. Data Normalization: We normalized the transaction amount using the Standard Scaler module and stored these values in a new column, NormalizedAmount.
6. Data Splitting: We split the dataset into training and testing sets with a 70:30 ratio to ensure robust model evaluation.
7. Model Training: We trained two models, a Decision Tree and a Random Forest, on the training set.

**Results-** The performance of our models was evaluated based on several key metrics: Accuracy: 0.99533, Precision: 0.13333, Recall: 0.11765, F1-score: 0.12500
These results indicate a high level of accuracy in our fraud detection model, although precision and recall suggest there is room for improvement in correctly identifying all fraudulent transactions.
