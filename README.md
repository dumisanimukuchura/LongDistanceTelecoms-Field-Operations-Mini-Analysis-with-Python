# Telecom Field Operations — Mini EDA Project

This is a quick but insightful data analysis project conducted as part of a data analytics training by Jerita Chibanda.
Done by: Dumisani Maxwell Mukuchura
Email: dumisanimukuchura@gmail.com 

**Disclaimer:** This is a demonstration of analytical thought process on a very small dataset. Any derived insights would require a significantly larger and more representative dataset for validation in a real-world scenario.


## 📄 Overview
The dataset contains records for **6 fictional telecom technicians** at "LongDistanceTelecoms". While small in size, the dataset was used to:

- Practice **Exploratory Data Analysis (EDA)**
- Apply **descriptive and diagnostic analytics**
- Unearth patterns in **experience, performance, and satisfaction**
- Make **recommendations for workforce productivity improvement**


## Dataset

The dataset (`telecom_field_operations.csv`) includes the following fields for 6 technicians:
* Work_ID
* Technician_Name
* Age
* Gender
* Education_Level
* Years_Experience
* Region
* Work_Type
* Duration_Hrs
* Tasks_Completed
* Faults_Resolved
* Equipment_Used
* Site_Type
* Issue_Escalated
* Customer_Satisfaction

## 🧠 Key Concepts Explored
* **Data Loading and Inspection:** Using Pandas to load and get an overview of the data. 
* **Descriptive Statistics:** Calculating means, distributions, and counts (e.g., average satisfaction, education level distribution). 
* **Grouped Analysis:** Using `groupby()` to compare metrics across different segments (e.g., average work duration by gender, experience by region).
* **Data Visualization:** Generating histograms for age distribution (using Matplotlib/Seaborn). 
* **Correlation Analysis:** Examining the relationship between variables (e.g., experience vs. faults resolved). 
* **Conditional Filtering & Comparative Analysis:** Comparing sub-groups (e.g., older vs. younger technicians, diploma vs. degree satisfaction). 
* **Calculated Metrics:** Creating new metrics for analysis (e.g., efficiency as faults resolved per hour). 
* **Identifying Influencing Factors:** Basic analysis to see which demographic factors might influence outcomes like customer satisfaction. 


## 🔍 Sample Questions Answered
- What is the average customer satisfaction rating across all technicians?
- Is there a correlation between years of experience and number of faults resolved?
- Are there gender-based differences in issue escalation rates?
- What combination of demographics leads to the highest efficiency?

## 💡 Key Insight
> “Small data can still drive big decisions—if the right questions are asked.”

## ⚠️ Note  
Small sample size—insights are illustrative. Methodology scales to larger datasets.

## 👥 Acknowledgement
This project was completed during a training facilitated by **Jerita Chibanda**. Many thanks for the challenge and the inspiration.

---

📬 For collaborations or deeper workforce analytics projects, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/dumisani-maxwell-mukuchura-4859b7170/)
