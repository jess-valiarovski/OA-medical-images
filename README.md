# 🏥 **Descriptive Analysis of User Data from a Medical Image Labeling Mobile Application**  

## 🚀 **Project Title:**  
**Evaluating Crowd vs. Expert Labeling for Medical Image Analysis**  

📅 **Timeframe:** *Feburary 2023-April 2023*  
📍 **Author:** **Jess Valiarovski**  
📚 **Company:** **Centaur Labs**  
🎓 **Acknowledgements:** Thank you **Anant Jain** for your mentorship and **Open Avenues** for the internship opprotunity!  


## 🚀 **Project Overview**  
This project examines **the reliability of crowdsourced medical image labeling** compared to expert annotations. The goal is to **justify reducing the number of experts needed** to create labeled medical image datasets for **artificial intelligence training**, while maintaining high accuracy.  

### 🔍 **Key Objectives:**  
- **Compare labeling accuracy** between crowdsourced users and medical experts.  
- **Analyze agreement rates** within and between groups.  
- **Identify whether crowdsourced annotations** can match expert consensus.  
- **Propose cost-saving strategies** by reducing the required number of experts.  

---
### **📊 Dataset Overview**  
- **Source:** Medical image labeling mobile application  
- **Task:** Users labeled medical images as **normal** or **abnormal**  
- **User Categories:**  
  - 🏥 **Medical Experts:** Verified professionals with domain expertise  
  - 🌍 **Crowd Workers:** General users with no medical background  
---

## 🛠️ **2. Methods & Data Processing**  

### 📊 **Data Cleaning & Transformation**  
- **Pandas (`pandas`):** Data wrangling & preprocessing  
- **NumPy (`numpy`):** Statistical calculations  
- **Regular Expressions (`re`):** Extracting expert votes from URLs  
- **Handling Missing Data:** Filtering out incomplete or irrelevant rows  

### 🔬 **Data Preparation**  
✔ **Removed irrelevant columns** (e.g., content metadata, unused votes).  
✔ **Filtered NA values** and standardized labels.  
✔ **Extracted expert vote counts** from dataset metadata.  
✔ **Created new variables** for agreement scores and error rates.  

### 📊 **Statistical Methods Applied**  
✔ **Agreement Analysis:** Calculated expert consensus and crowd consensus.  
✔ **Error Rate Calculation:** Measured expert/crowd misclassification rates.  
✔ **Confidence Categories:** Labeled cases based on labeling difficulty.  

### 📈 **Data Visualization (`plotly`, `matplotlib`)**  
- **Density Heatmaps** – Show relationship between group size & labeling accuracy  
- **Violin Plots** – Compare expert and crowd vote distributions  
- **Agreement Distributions** – Show variation in normal vs. abnormal classifications  
---
## 🛠  **Key Findings & Visuals**  
- **The crowd was overall more confident** while **experts were more frequently split** in their diagnostic labeling.
- **Only 0.92% of cases reached unanimous expert agreement**, while **5.77% of cases reached unanimous crowd agreement**.
- 
### 🔬 **Conclusion**  
📌 **Aggregated crowd opinions were more consistent** with final expert consensus than individual expert votes.
📌 **Crowdsourced medical image labeling can reduce reliance on medical experts and cut sourcing costs** and 
also **generate high-quality labeled medical imaging datasets for AI diagnostic training**.  

---

## 📌 **Technical Skills Demonstrated**  

🛠 **Python & Data Science Techniques**  
✅ **Data Wrangling & Cleaning:** `pandas`, `numpy`, `regex`  
✅ **Statistical Modeling & Analysis:** Agreement rates, difficulty scores, expert error rates  
✅ **Data Visualization:** `plotly`, `matplotlib`, `plotly.express`  
✅ **Hypothesis Testing:** Consensus comparison between experts and crowd  

---

## 📢 **How to View the Analysis**  

📌 **Jupyter Notebook:**  
📎 [exploratory_analysis-final-4.ipynb](./exploratory_analysis-final-4.ipynb)  

---
