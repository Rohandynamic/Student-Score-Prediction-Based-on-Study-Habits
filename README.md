# Student-Score-Prediction-Based-on-Study-Habits
A regression-based project to predict students’ exam scores using study hours and attendance data.


This project focuses on predicting student performance based on their study habits using a regression model. The primary goal is to estimate a student’s final exam score by analyzing two key factors: **hours studied** and **attendance percentage**. The project begins with data collection and preprocessing using **Pandas**, ensuring that the dataset is clean and consistent. Exploratory data analysis and visualization are carried out with **Matplotlib** and **Seaborn** to understand relationships between variables. A **Linear Regression model** is then trained using **Scikit-learn**, where the data is split into training and testing sets to evaluate performance. The model’s accuracy is assessed using metrics like the **R² score** and **Mean Absolute Error (MAE)**. Finally, the model can predict scores for new inputs, such as estimating performance for a student with specific study hours and attendance. This project demonstrates the application of data science in education and predictive analytics.



# Steps to Complete the Project

**Step 1: Setup Environment**
   * Install Python on your system.
   * Install required libraries: Pandas, Matplotlib, Seaborn, Scikit-learn.

**Step 2: Collect or Prepare Dataset**
  * Create a dataset with at least 20–50 rows.
  * Columns should include:
    
    * Hours_Studied
    * Attendance (%)
    * Final_Score

**Step 3: Import and Load Data**
  * Load the dataset into your Python environment.
  *  Check for missing or incorrect values.

**Step 4: Data Visualization and Analysis**
  * Plot graphs to show relationships:

      * Hours Studied vs Final Score
      * Attendance vs Final Score
        
* Create a heatmap to check correlations.

**Step 5: Data Splitting**
* Split the dataset into two parts:

    * Training Set (80%) – to train the model.
    * Testing Set (20%) – to evaluate the model.
 
**Step 6: Model Training**
* Apply Linear Regression to the training dataset.
* Fit the model to learn the relationship between study habits and scores.

**Step 7: Predictions**
* Use the trained model to predict scores for the test dataset.
* Try with a new example input:
    * Hours Studied = 7, Attendance = 80%
 
**Step 8: Model Evaluation**
* Calculate accuracy using:
    * R² Score – how well the model explains data.
    * Mean Absolute Error (MAE) – average prediction error.
  
