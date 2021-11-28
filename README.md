# Plagiarism-Detection

Build a model for plagiarism detection in Amazon // AWS Sagemaker.
 
Problem: Compare answers given by students with the corresponding Wikipedia texts and detect if there is any cut & paste plagiarism.  

Steps: 
1. Feature Engineering
Computed 2 features: Containment and Longest Common Subsequence. Inspected and selected correlated features with the test data set. 

2. Building & Training a ML Model
Used pyTorch library to build a 2 layer simple Neural Network that performs binary classification. 

3. Testing in production
Accuracy and Precision is calculated. 
