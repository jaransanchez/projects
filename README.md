### 🎯 Objective
To analyze telecommunications customer behavior and determine which prepaid plan (Surf or Ultimate) generates higher revenue, supporting advertising budget optimization through statistical analysis.

---

### 📂 Dataset
Five datasets containing information on **500 customers** from 2018 were used:

- **users**: demographic data, city, and subscribed plan  
- **calls**: call records and duration  
- **messages**: number of SMS sent  
- **internet**: data usage per session  
- **plans**: plan features and pricing  

The data includes company rounding rules for minutes and gigabytes.

---

### 🛠️ Tools
- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scipy.stats  
- Jupyter Notebook  

---

### 🔍 Process
1. Data loading and initial exploration  
2. Data cleaning and type conversion  
3. Monthly per-user calculation of:
   - Minutes, SMS, and data usage  
   - Total revenue including overages and fixed fees  
4. Descriptive analysis (mean, variance, and standard deviation)  
5. Distribution visualization using histograms  
6. Hypothesis testing to compare revenue by plan and region  

---

### 📊 Visualizations
- Histograms of minutes, SMS, and data usage by plan  
- Monthly revenue distribution per plan  
- Revenue comparison by region (NY-NJ vs others)  

---

### ✅ Conclusions
The Surf plan generates higher but less predictable revenue due to frequent overage usage, while the Ultimate plan provides more stable income. Although Surf produces significant unexpected revenue, encouraging high-consumption users to switch to Ultimate would improve revenue predictability.

| Distribution of Monthly Messages by Plan | Distribution of Monthly Minutes by Plan|
|-------|-------|
<img width="984" height="574" alt="image" src="https://github.com/user-attachments/assets/d2a2df9e-1751-426c-86fb-39883623f7e8" /> | <img width="992" height="582" alt="image" src="https://github.com/user-attachments/assets/09ef8bcd-166f-4837-8e4b-3a4be8b3dfe7" />

