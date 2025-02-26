# HR Analytics Project  

## 📌 Overview  
This project analyzes employee data to identify patterns related to satisfaction, evaluation, work hours, and attrition. Using statistical analysis and machine learning, it helps HR teams improve employee retention and productivity.  

## 📂 Dataset  
The dataset includes:  
- `satisfaction_level` – Employee job satisfaction score  
- `last_evaluation` – Most recent performance evaluation score  
- `average_montly_hours` – Average working hours per month  
- `time_spend_company` – Number of years in the company  
- `work_accident` – Whether an employee had a workplace accident (0 = No, 1 = Yes)  
- `left` – Whether the employee left the company (0 = No, 1 = Yes)  

## 🛠️ Setup & Installation  
### **1. Install Required Packages**  
Run the following command in R to install necessary libraries:  
```r
install.packages(c("GGally", "corrplot", "tidyverse"))
```
### **2. Load The Dataset**
```r
df <- read.csv("hr_data.csv")
```
## Key Insights
- `Job Satisfaction & Attrition` – Employees with lower satisfaction are more likely to leave.
- `Working Hours & Turnover` – Overworked employees show a higher turnover rate.
- `Performance Evaluation` – High and low performers tend to leave more than average performers.
