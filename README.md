# Automating-Loan-Qualification-Process

The aim of this project was to analyse and develop machine learning processes in order to automate the loan qualification process in real-time using information provided by customers in online application forms.

### Case Background
As the leading financial institution, ProsperityBank is dedicated to fostering prosperity and financial well-being for all its customers. With a focus on innovation and customer-centric solutions, ProsperityBank continues to evolve to meet the diverse needs of its clientele. The company aims to automate the loan qualification process in real-time using information provided by customers in online application forms. Developing machine learning models is expected to enhance the prediction of loan approval. You have been tasked with developing machine learning algorithms based on the company's dataset. 

### Requirements
1. CRISP-DM Methodology<br>
Employ the CRISP-DM methodology for your analytics process.

3. Exploratory Data Analysis and Data Preprocessing <br>
Perform exploratory data analysis (EDA) to understand the dataset's structure and characteristics. <br>
Handle missing values, outliers, and irrelevant features appropriately. <br>
Visualise distributions, relationships, and patterns in the data to gain insights. <br>

4. Predictive Modeling <br>
Implement various machine learning algorithms including KNN, Decision Tree, and Random Forest.<br>
Train models using the dataset.<br>
Evaluate model performance and compare different models using metrics such as accuracy, precision, recall, and F1-score. 

### Data Analysis and Modelling
For this project, I first prepared the data by filling missing values in categorical variables with the most frequent value and the numerical varaibales with the mean value. I then mapped the categorical variables to binary values using label encoder.

Then, was the modelling phase. I ran three models on the dataset: KNN, Random Forest Classifier and Decision Tree Classifier. I then compared the results using the confusion matrix and metrics like Accuracy, Precision, Recall and F1 Score. Moreover, I also used the Area under the ROC curve to compare the performance of the three models.

### Conclusion
In conclusion, the evaluation of various machine learning models for ProsperityBank's loan approval process revealed differences in performance. While the k-NN classifier demonstrated moderate performance, the decision tree classifier showed improvement in accuracy, precision, recall, and F1-score. However, the random forest classifier outperformed both models, exhibiting the highest accuracy, precision, recall, and F1-score. Considering these findings, it is recommended that ProsperityBank deploys the random forest classifier in its loan approval process.

Furthermore, the findings from the bias assessment and fairness metrics analysis underscore the importance of addressing biases and promoting fairness in the loan approval process. The initial logistic regression model exhibited bias towards certain demographic groups, highlighting the need for proactive measures to mitigate bias and promote fairness. This includes implementing fairness-aware algorithms and preprocessing techniques, prioritizing transparency and interpretability in decision-making, establishing regular monitoring mechanisms, and engaging with diverse stakeholders.

By deploying the random forest classifier and implementing strategies to mitigate bias and promote fairness, ProsperityBank can enhance its loan approval process, ensure equitable outcomes for all applicants, and reinforce its commitment to fostering prosperity and financial well-being for all stakeholders. Additionally, continuous monitoring and refinement of the deployed model are essential to maintain fairness and effectiveness over time.
