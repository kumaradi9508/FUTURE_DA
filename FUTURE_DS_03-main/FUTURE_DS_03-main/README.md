# 🎓 Student Satisfaction Survey Analysis


![Student Satisfaction Dashboard](https://github.com/Harriet-ngomo/FUTURE_DS_03/blob/4e4ce04fd9a445958813816ebf2a49a8bf70596d/images/Student%20satisfaction%20Dashboard.png)

This project analyzes **student feedback data** collected through a survey (Google Forms export).  
The aim is to understand **satisfaction trends**, map **ratings to sentiment categories** and generate **actionable recommendations** for improving campus events and learning experiences.



##  Project Objectives
1. **Data Cleaning & Preparation**  
   - Import CSV, handle duplicates, missing values, and formatting.  
   - Generate an overview: shape, data types, metadata, and statistical summary.  

2. **Quantitative Feedback Analysis (Ratings)**  
   <img width="788" height="473" alt="Overall Rating Disribution" src="https://github.com/user-attachments/assets/672551c3-6645-4648-afbd-6225b336e27c" />
   - Study distribution of ratings (1–5 scale).  
   - Compare responses across departments and courses.  

3. **Sentiment Analysis (Ratings-Based)**
<img width="727" height="488" alt="Overall sentiment Distribution" src="https://github.com/user-attachments/assets/36d3d878-b8be-4563-aa36-a50a92e62b5e" />

   - Map ratings to sentiment categories:  
     - Positive → Ratings of 4 and 5  
     - Neutral → Rating of 3  
     - Negative → Ratings of 1 and 2  
   - Calculate sentiment distribution overall and by department.  

4. **Visualization of Satisfaction Trends**  
   - Bar charts, pie charts, and heatmaps using **Matplotlib** and **Seaborn**.  
   - Visualize rating distribution, average scores per question, and sentiment breakdowns.  
<img width="885" height="492" alt="Screenshot 2025-09-06 163051" src="https://github.com/user-attachments/assets/860813b7-95a7-4baf-b0ba-ab8de7c8da89" />

5. **Actionable Recommendations**  
   - Highlight areas of improvement based on feedback patterns.  
   - Support decision-making for better student engagement and academic delivery.  



##  Tools & Libraries
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Data Cleaning:** Handling duplicates, formatting, missing values  
- **Visualization:** Bar plots, heatmaps, pie charts, line plots  
- **Sentiment Mapping:** Ratings → Sentiment (Positive, Neutral, Negative)  
- **Power BI** for interactive dashboarding  



##  Key Insights
- **Most feedback is Positive** (70% of responses).  
- **Neutral responses are very low** (0.18%).  
- **Negative feedback is minimal** (0.12%).  
- Average student satisfaction score: **3.89 / 5**.  



## Visual Highlights

###  Python Visualizations
- Overall rating distribution  
- Sentiment distribution by department  
- Average score per question  
- Trends of average scores across questions  

### Power BI Dashboard
Below is a sample **dashboard** built in Power BI to present insights interactively:  

![Student Satisfaction Dashboard](https://raw.githubusercontent.com/Harriet-ngomo/FUTURE_DS_03/a65ce70d08bc442f380c10b91eb375a19684b373/images/Screenshot%202025-09-03%20161717.png)
<img width="1217" height="581" alt="report" src="https://github.com/user-attachments/assets/90642b34-c94a-484e-a5ee-79a7bdf9186b" />
<img width="1177" height="580" alt="Student Satisfaction Report" src="https://github.com/user-attachments/assets/5be4dc3f-daba-4665-baa8-f4246bf8b2bf" />

![Student Satisfaction Report](https://github.com/Harriet-ngomo/FUTURE_DS_03/blob/2144c81bcfa8698033bf41fdc1f5059df8fbd6b3/images/Screenshot%202025-09-02%20223354.png)

![Student Satisfaction Dashboard](https://github.com/Harriet-ngomo/FUTURE_DS_03/blob/4e4ce04fd9a445958813816ebf2a49a8bf70596d/images/Student%20satisfaction%20Dashboard.png)



## 📂 Dataset Overview
- **Shape:** 580 rows × 12 columns  
- **Key Columns:**  
  - `Questions` → Survey questions  
  - `Weightage 1–5` → Counts of ratings  
  - `Average/ Percentage` → Average rating per question  
  - `Basic Course` → Department/Program name  

---

##   Future Improvements
- Incorporate **open-text comment sentiment analysis** (TextBlob/VADER).  
- Apply **clustering** to group similar student feedback patterns.  
- Automate **dashboard creation** in Power BI/Tableau.  

---

## Author
 **Harriet Ngomo**  
- Data Analyst | Data Scientist | Economic Analyst  
-  [GitHub](https://github.com/Harriet-ngomo)  

✨ *Transforming raw student feedback into actionable insights for better learning outcomes.*  
