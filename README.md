# Internship_viva_Questions

## 1. Introduce yourself

### Answer:
My name is Manish Kumawat, and I am pursuing a B.Sc. degree. I have a strong interest in Data Science and Machine Learning. During my internship at Airsme Technology Private Limited, I worked on a Smartphone Addiction Detection System using Machine Learning, where I gained hands-on experience in data preprocessing, EDA, model building, API development, and deployment using FastAPI and Streamlit.

## 2. Explain your internship in detail

### Answer:
I completed a one-month Data Science internship where I learned practical concepts of Machine Learning and worked on a real-world project called Smartphone Addiction Detection System. The internship involved data preprocessing, visualization, feature engineering, model training, evaluation, and deployment. I also learned how to create APIs using FastAPI and build an interactive UI using Streamlit.

## 3. Explain your project in detail

### Answer:
The Smartphone Addiction Detection System is a Machine Learning-based application that predicts addiction levels based on user behavior and smartphone usage patterns. The model classifies users into three categories:

Mild
Moderate
Severe

The project workflow included:

Data Collection
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Model Training
Model Evaluation
Deployment using Streamlit and FastAPI

## 4. Why did you choose this project?

### Answer:
Smartphone addiction is increasing rapidly, especially among students and young professionals. I chose this project because it solves a real-world problem and demonstrates how Machine Learning can be used to analyze human behavior patterns.

## 5. What dataset did you use?

### Answer:
I used a smartphone usage dataset containing behavioral information such as screen time, app usage, and digital activity patterns. These features helped the model classify addiction levels.


6. What preprocessing steps did you perform?

Answer:
The preprocessing steps included:

Handling missing values
Removing duplicate records
Feature selection
Encoding categorical values
Data transformation and cleaning

This improved the quality of the dataset before training.

7. What is EDA? Why is it important?

Answer:
EDA (Exploratory Data Analysis) is the process of understanding data using statistical summaries and visualizations.

It helps:

Find patterns
Detect outliers
Understand relationships between variables
Select useful features

I used countplots, heatmaps, histograms, and boxplots for analysis.

8. Explain the graphs you used

Answer:
I used:

Countplot

To visualize the distribution of addiction levels (Mild, Moderate, Severe).

Heatmap

To identify relationships between features.

Boxplot

To compare screen time against addiction level.

Histogram

To understand data distribution.

9. Which algorithms did you use?

Answer:
I experimented with:

Logistic Regression
Random Forest

Random Forest performed better, so it was selected for prediction.

10. Why Random Forest?

Answer:
Random Forest was chosen because:

It handles complex relationships
Reduces overfitting
Works well with mixed features
Produces stable results

It combines multiple decision trees to improve prediction quality.


1. What is overfitting?

Answer:
Overfitting happens when a model memorizes training data instead of learning patterns. As a result, it performs well on training data but poorly on unseen data.

Random Forest helps reduce overfitting.

12. What is underfitting?

Answer:
Underfitting occurs when a model is too simple and cannot learn patterns from data properly.

13. Explain train-test split

Answer:
The dataset was divided into:

Training data → used for learning
Testing data → used for evaluation

Usually, I used an 80:20 ratio.

14. What is accuracy?

Answer:
Accuracy measures how many predictions are correct.

Formula:

Accuracy=
Total Predictions
Correct Predictions
	​


My model achieved approximately 68.7% accuracy.

15. What is F1-score?

Answer:
F1-score combines precision and recall into one metric and is useful for classification problems.

My project achieved approximately 70% F1-score.

16. Why accuracy alone is not enough?

Answer:
Accuracy can be misleading in imbalanced datasets. F1-score provides a better measure because it considers both false positives and false negatives.

17. What is a confusion matrix?

Answer:
A confusion matrix shows:

Correct predictions
Incorrect predictions

It helps understand model performance in classification.

18. Why did you use Streamlit?

Answer:
Streamlit was used to build an interactive UI where users can input data and get predictions in real time.

19. Explain Streamlit workflow

Answer:

User enters input
Input is sent to model
Model predicts addiction level
Result is displayed
20. Why FastAPI?

Answer:
FastAPI was used to expose the ML model as an API and test predictions using /docs.

21. What is API?

Answer:
API (Application Programming Interface) allows communication between systems.

In my project, FastAPI connected the frontend and ML model.

22. What is /docs in FastAPI?

Answer:
/docs provides interactive API documentation where requests can be tested directly.

23. What is model deployment?

Answer:
Deployment means making the trained model available for real-world usage through applications or APIs.

24. Explain project architecture

Answer:
The project followed a modular structure:

Notebook → EDA & experiments
src/ → preprocessing & pipelines
model/ → trained model
app.py → application logic
YAML → configuration
25. What is YAML?

Answer:
YAML is a configuration file format used to store settings and parameters separately from code.

26. What is a pipeline?

Answer:
A pipeline automates multiple ML steps like preprocessing and prediction in sequence.

27. What challenges did you face?

Answer:

Data preprocessing issues
Feature selection
Improving model performance
API integration
28. What improvements can be made?

Answer:

Larger dataset
Deep learning models
Cloud deployment
Better feature engineering
29. What was your role?

Answer:
I worked on preprocessing, EDA, model training, evaluation, Streamlit UI, FastAPI integration, and testing.

30. Why should we hire you?

Answer:
I have hands-on experience in Data Science projects, strong Python skills, and practical exposure to ML deployment using FastAPI and Streamlit. I am also eager to learn and adapt quickly.

These are the kinds of questions that often decide the viva.
