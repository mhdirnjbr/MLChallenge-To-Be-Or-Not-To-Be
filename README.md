# Mortality Prediction Challenge

## Background
In this challenge, we aim to predict the survival of patients given their medical record. More specifically, the goal is to predict whether or not the patients died during their stay at the hospital. Medical professionals collect a lot of information about patients through various methods, such as asking questions and using tools like stethoscopes and sensors. This data is incredibly valuable for monitoring health, diagnosing illnesses, and choosing treatments. However, it can also be used for statistical predictive analysis.

## Data
The training dataset contains information about 80,000 patients, represented by categorical, binary, and numerical features (also known as "variables"). These features include things like age, gender, ethnicity, marital status, as well as medical data such as blood pressure and glucose levels. There are a total of 342 variables.

The class (or label) to be predicted is a binary variable indicating whether the patient died or not during their stay in the hospital. Most patients do not die, leading to an imbalanced classification problem. In the data, a label of 0 means "DIDN'T DIE" and a label of 1 means "DIED".

## Task
The task is to create a model that can learn from the data and make predictions on unseen data. This is called supervised learning, as the algorithm learns from labeled data. Each data point (each patient) has a label indicating whether they died or not during their stay in the hospital. The goal is to learn a link between the data and labels and use it to make predictions on new, unseen data.

The problem is a binary classification problem, which means that the goal is to label every row in the test set with a 0 or a 1, corresponding to the two classes "DIED" or "DIDN'T DIE".

## Evaluation
Submissions are evaluated using the balanced accuracy metric, which is the average recall obtained on either class. This is used instead of accuracy score because the classes distribution (number of examples of each class) is imbalanced, and accuracy score would not be a fair evaluation metric in this case. A model that classifies every patient as "DIDN'T DIE" would have an accuracy score of 94%, while being clearly not useful as a predictive model.

## Getting Started
1. Clone the repository to your local machine
2. Download the dataset
3. Start building your model
4. Submit your solution to the leaderboard
   
## Note
As the data provided is sensitive and private, the dataset will not be shared publically, the results are only for the evaluation of the model, not for the real-life use.
