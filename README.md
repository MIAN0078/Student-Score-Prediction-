#  Student Score Prediction

This project predicts students' scores based on the number of hours they studied using **Machine Learning** techniques. It demonstrates the use of **Supervised Learning (Linear Regression)** to analyze and predict outcomes from given data.

##  Project Overview

* The dataset contains information about students' study hours and their corresponding scores.
* The main objective is to build a **regression model** that can predict a student’s score if the number of study hours is given.
* This is a beginner-friendly ML project, useful for understanding regression, evaluation metrics, and visualization.

##  Features

* Data preprocessing and visualization
* Simple Linear Regression model
* Model training and testing
* Evaluation using metrics (e.g., Mean Absolute Error, R² Score)
* Prediction of scores based on input study hours

##  Dataset
**The dataset used is a simple CSV file with two columns:**
* `Hours` → Number of hours studied
* `Scores` → Percentage score obtained

## Example:

| Hours | Scores |
| ----- | ------ |
| 2.5   | 21     |
| 5.1   | 47     |
| 7.8   | 86     |

##  Technologies Used

* Python 🐍
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit-learn

##  How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/student-score-prediction.git
   cd student-score-prediction
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or Python script:

   ```bash
   jupyter notebook Student_Score_Prediction.ipynb
   ```
      OR

   ```bash
   python student_score_prediction.py
   ```
##  Results

* The model shows a strong correlation between study hours and student scores.
* Example prediction:

  * If a student studies **9.25 hours**, the predicted score is approximately **92%**.

##  Learning Outcomes

* Basics of data visualization
* Understanding linear regression
* Evaluating regression models
* Making predictions with ML models

---

##  Acknowledgements

* The dataset is inspired by student performance studies.
* Special thanks to open-source libraries and learning resources that made this project possible.


