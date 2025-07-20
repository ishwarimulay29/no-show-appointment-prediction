# No-Show Appointment Prediction

This project analyzes medical appointment records to predict whether a patient will show up for their scheduled appointment. The motivation is to help healthcare systems improve scheduling efficiency and minimize wasted resources due to patient no-shows.

## 📊 Project Overview

Using a dataset of patient medical appointments, this project:
- Explores patterns in patient demographics and behaviors
- Builds machine learning models to predict no-shows
- Identifies key influencing factors such as age, wait time, and SMS reminders

## 🧠 Key Features

- *Target Variable:* No-show — whether a patient showed up for their appointment
- *Important Predictors:* Days between scheduling and appointment, Age, Hypertension, SMS reminders
- *Visualizations:* Age distributions, correlation heatmaps, feature importance bar plots, zip code-based trends

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Decision Tree Classifier
- PowerPoint for summary presentation

## 📁 Repository Contents

| File | Description |
|------|-------------|
| Final_Project.ipynb | Exploratory data analysis, feature engineering, and modeling |
| final_project.py | Python script version for CLI or batch runs |
| Presentationbda.pptx | Summary of findings and visualizations |
| requirements.txt | List of required Python packages |

## 📌 Key Insights

- Longer wait times between scheduling and appointment are associated with higher no-show rates
- Younger patients are more likely to miss appointments
- Surprisingly, receiving an SMS reminder *does not* always increase the likelihood of attendance

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/no-show-appointment-prediction.git
   cd no-show-appointment-prediction
