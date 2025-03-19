# **Military Expenditure vs. Global Conflicts**

## **Motivation**  
Military spending is a mandatory and crucial aspect of national security and geopolitical strategy. Understanding how military expenditure fluctuates in response to global conflicts can provide insights into defense policies, economic trade-offs, and international relations. This is a crucial step in the analysis of different countries in the geopolitical world. I personally find geopolitics, global conflicts and history very interesting and tend to keenly follow current conflicts, mainly trying to keep up with what is going on around the world, thats why i decided to make my project on this topic.
 
---

## **Goal**  
This study aims to analyze the relationship between military spending and global conflicts, investigating whether military budgets tend to increase before, during, or after major wars and geopolitical tensions.

---

## **Research Questions**  
This project seeks to answer the following key questions:  

1) How does military expenditure fluctuate in response to global conflicts, and is there a pattern in spending before, during, or after conflicts?

2) Do countries involved in prolonged conflicts exhibit sustained increases in military budgets compared to those experiencing short-term conflicts?

3) Are there regional differences in military spending trends related to geopolitical tensions (e.g., Middle East vs. Europe vs. Asia)?

4) Can historical data on military spending and conflicts be used to predict future military expenditure trends?  

---

## **Data Sources**  
The primary dataset for this project is the Military Expenditure by Country (1970-2020) dataset from Kaggle. It contains information on the military spending of various countries over several decades. It contains data about the military expenditure of the countries over the course of 50 years and it shows these percentages with respect to GDP and government sepnding. 

*Source:* [Military Expenditure by Country (1970-2020) - Kaggle](https://www.kaggle.com/datasets/prasertk/military-expenditure-by-country-from-19702020)  
*Description:* Contains military spending data for various countries over five decades. It includes military expenditure as a percentage of **GDP** and **government spending**.  

### **Conflict Dataset**  
*Source:* [Uppsala Conflict Data Program (UCDP)](https://ucdp.uu.se/)  
*Description:* Provides detailed records of armed conflicts, including **start and end dates, severity, and involved nations**. This dataset helps analyze military spending trends in relation to conflict occurrences.  

---

## **Data Collection Plan**  
🔹 **Military Expenditure Data**  
- Extract **military spending data** by country and year.  
- Adjust for **inflation** (if needed) for accurate comparisons.  

🔹 **Conflict Data (UCDP)**  
- Identify **years when conflicts occurred** for each country.  
- Categorize conflicts by **intensity** (e.g., low-intensity conflicts vs. full-scale wars).  

🔹 **Data Merging & Analysis**  
- Combine **military expenditure** data with **conflict data** to identify spending trends before, during, and after conflicts.  

---

## **Data Analysis Process**  
The project follows these key phases:  

### **Data Cleaning & Preprocessing**  
Handle **missing or inconsistent data**.  
Standardize **monetary values** for accurate comparisons.  

### **Exploratory Data Analysis (EDA)**  
**Trend Analysis:**  
🔹 Visualize **military spending trends** across different decades.  
🔹 Compare spending **during peacetime vs. wartime**.  

**Regional Analysis:**  
🔹 Identify regions with the **most significant spending fluctuations** due to conflicts.  

**Country-Specific Case Studies:**  
🔹 Analyze military budgets of key nations involved in long-term conflicts (e.g., **U.S., Russia, Middle Eastern nations**).  

### **Statistical Tests & Correlations**  
Conduct **hypothesis tests** to determine whether military spending significantly increases **before, during, or after** conflicts.  
Correlate the **intensity of conflicts** (e.g., casualties, duration) with **military expenditure growth rates**.  

---

## **Expected Findings**  
Military spending likely spikes before or during major conflicts as countries prepare for war.
Some countries may maintain high defense budgets post-conflict, possibly due to prolonged security concerns.
Regions with frequent conflicts (e.g., the Middle East, Eastern Europe) may show more volatile military budgets.
Economic constraints may limit military spending, even during high-conflict periods, in some developing nations

---

## **Limitations**  
The datasets may not capture secretive military budgets and secret projects for example during the cold war how various arms race projects were unreported.
Conflicts vary in scale and nature, making causal relationships difficult to establish.
Economic and political factors may influence military budgets beyond conflicts alone.

---

## **Future Work**  
🔹 **Predict future military spending trends** based on past conflicts.  
🔹 Analyze **alliance-driven spending**.  
🔹 Investigate the impact of **nuclear deterrence policies** on military budgets.  

