# ⚽ Predicting-FIFA-Rating-Changes-from-Player-Injuries

## 📌 Overview
This project analyzes the impact of **player injuries** on **FIFA video game rating changes** using real-world football data.  
It combines **injury history**, **player performance**, and **FIFA ratings** to understand whether injuries influence how player ratings evolve over time.

The project focuses on identifying patterns between:
- Injury frequency and severity  
- Time missed due to injuries  
- Subsequent changes in FIFA player ratings  

## 🎯 Objectives
- Analyze historical FIFA rating changes for professional football players  
- Study injury-related factors affecting rating upgrades or downgrades  
- Build predictive models to estimate rating changes following injury events  
- Provide data-driven insights into how injuries influence player valuation in FIFA  

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn  
- **Data Collection:** Web scraping  
- **Environment:** Jupyter Notebook  
- **Version Control:** Git & GitHub  

## 📊 Dataset Description
The dataset was created by combining:
- **FIFA player rating data** across multiple editions  
- **Injury records** collected through web scraping  
- **Player metadata** such as position, age, and club  

### Key Features
- Player identifiers and names  
- FIFA overall ratings across seasons  
- Injury count and injury duration  
- Matches missed due to injury  
- Rating change (target variable)  

## 🔄 Data Pipeline
- Web scraping to collect injury data  
- Data cleaning and standardization  
- Merging injury data with FIFA rating datasets  
- Feature engineering to quantify injury impact  
- Exploratory data analysis (EDA)  
- Predictive modeling and evaluation  

## 🤖 Modeling Approach
Multiple machine learning models were used to predict FIFA rating changes, including:
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

Model performance was evaluated using:
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  


## 📈 Key Insights
Some of the key findings include:
- Longer injury durations are associated with rating declines  
- Frequent injuries have a stronger impact than isolated injury events  
- Younger players tend to recover ratings faster than older players  
- Injury impact varies across player positions  

## 📁 Project Structure
- `fifa_web_scraper.ipynb` → Web scraping injury data  
- `methods_part1.ipynb` → Data cleaning and feature engineering  
- `methods_part2.ipynb` → Modeling and evaluation  
- `final_report.ipynb` → Final analysis and conclusions  

## 🚀 Use Cases
- Sports analytics and football performance analysis  
- Injury impact assessment for scouting and valuation  
- Data science portfolio project  
- Academic research and coursework  

## 📌 Conclusion
This project demonstrates how **sports data, injury analytics, and machine learning** can be combined to extract meaningful insights from football data.  
It highlights the growing role of **data-driven decision-making** in sports analytics and player evaluation systems like FIFA.
