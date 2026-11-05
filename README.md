# Online Media Consumption during COVID-19

### **The Project**
This study examines how the 2020 lockdowns changed online media use and how respondents say it affected them. It uses a primary survey of 40 people and tests the main questions with Z-tests and correlation analysis.

### **The Core Insight: The "Consumption Paradox"**
Usage hours rose sharply, yet higher post-COVID usage was linked to a lower rate of believing fake news **(r = -0.46)**. A possible explanation is that much of the usage was for education and work, not aimless scrolling. The data here cannot prove why exactly.

### **Key Findings**
* **Consumption Shift:** The share of respondents using online media for 3+ hours a day rose from 17.5% before COVID to 60% during it (Two-proportion Z-test, p = 0.00005)
* **Mental health:** 57.5% of respondents (23 of 40) said online media affected their mental health. High impact ratings (4 to 5) were significantly more common than low ones (1 to 2) (Z-test, p = 0.002)
* **Misinformation:** 60% said they unknowingly believed fake news. Higher post-COVID usage was negatively correlated with believing fake news (r = -0.46), and believing fake news was positively correlated with the mental health impact rating (r = 0.27)
* **Social discomfort:** Higher post-COVID usage was weakly negatively correlated with social discomfort (r = -0.19). The difference between high and low comfort ratings was not significant (p = 0.10)

### **Technical Stack**
* **Language:** Python
* **Libraries:** Pandas, Statsmodels, Seaborn, Matplotlib

### **Data and Limitations**
* The survey was a Google Form shared through social media, mostly with people aged 18 to 30 (convenience sampling)
* The analysis uses 40 responses (Cleaned Survey Data.csv). Survey Data.xlsx contains one additional response that is not included since it came in after the analysis was done
* Responses are self-reported and the sample is small, so the results describe this group and show correlation, not causation

### **Repository Structure**
* `Analysis.ipynb`: Full analysis from data loading to Z-tests and the correlation heatmap
* `Cleaned Survey Data.xlsx`: The 40 responses used in the analysis
* `Survey Data.xlsx`: The 41 responses (40 used in the analysis plus one late response)
* `Correlation Heatmap.png`: Correlation matrix
* `Online Media Consumption during COVID-19.pdf`: Final PDF Report
* `Requirements.txt`: Python Libraries

### **How to Run**
1. pip install -r Requirements.txt
2. Open Analysis.ipynb and run all cells.
