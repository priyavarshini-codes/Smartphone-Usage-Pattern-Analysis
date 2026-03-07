# Smartphone-Usage-Pattern-Analysis📱

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a dataset of mobile users to understand patterns in user behavior.  
The analysis investigates screen time, app usage, data consumption, operating system usage, and user behavior classes.  
The goal of this project is to gain insights into user habits, identify trends, and understand how different factors like installed apps, gender, and OS influence usage.

---

## Dataset

The dataset contains information about mobile users, including:

* User_ID
* Gender
* Age
* Operating System (Android / iOS)
* Number of Apps Installed
* App Usage Time (minutes/day)
* Screen On Time (hours/day)
* Data Usage (MB/day)
* User Behavior Class (Heavy / Moderate / Light)

Total records: **700** 

---

## Dataset Source

The dataset is a synthetic or collected dataset for **user behavior analysis**.  
*(If you have a specific source, include the link here.)*

---

## Tools and Technologies

The following tools and libraries were used:

* Python 
* Pandas
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

---

## Analysis Performed

The following steps were conducted:

* Data Cleaning and Handling Missing Values
* Removing Duplicates
* Descriptive Statistics
* Screen Time Distribution Analysis
* Relationship between Apps Installed and App Usage
* Data Usage by Gender
* User Behavior Class Distribution
* Operating System Usage Analysis
* Feature Correlation Heatmap

---

## Key Insights

* Users with **more installed apps tend to spend more time** on their phones.  
* **Screen time varies** across different user behavior classes.  
* **Data usage patterns differ** between male and female users.  
* **Android and iOS users show different usage distributions**.

---

## Visualizations

### Screen Time Distribution
![Screen Time Distribution](img/screen_time_distribution.png)

### Apps Installed vs App Usage
![Apps vs Usage](img/apps_vs_usage.png)

### Data Usage by Gender
![Data Usage by Gender](img/data_usage_by_gender.png)

### User Behavior Class Distribution
![User Behavior Distribution](img/user_behavior_distribution.png)

### Operating System Distribution
![OS Distribution](img/os_distribution.png)

### Feature Correlation Heatmap
![Correlation Heatmap](img/correlation_heatmap.png)

---

## Conclusion

This analysis provides insights into **mobile user behavior** and usage patterns.  
It shows how factors like the number of apps, gender, and operating system influence screen time and data consumption.  
The visualizations and statistics help identify **trends that can guide app development, marketing strategies, or user engagement improvements**.

---

## Project Files

* `user_behavior_analysis.ipynb` – Notebook containing the analysis and visualizations  
* `user_behavior_dataset.csv` – Dataset used for analysis  
* `img/` – Folder containing generated visualizations  
* `README.md` – This file  

---

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/priyavarshini-codes/Smartphone-Usage-Pattern-Analysis.git

2. Navigate to the project folder:

cd <repo>

3. Install required libraries:

pip install pandas matplotlib seaborn

4. Open the notebook in Google Colab or Jupyter Notebook and run all cells to reproduce the analysis and visualizations.

Project Structure

user_behavior_analysis
│
├── data
│   └── user_behavior_dataset.csv
│
├── img
│   ├── screen_time_distribution.png
│   ├── apps_vs_usage.png
│   ├── data_usage_by_gender.png
│   ├── user_behavior_distribution.png
│   ├── os_distribution.png
│   └── correlation_heatmap.png
│
├── user_behavior_analysis.ipynb
├── README.md
└── requirements.txt (optional)
