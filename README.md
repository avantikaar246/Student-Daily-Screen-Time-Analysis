# Student Daily Screen Time Analysis

[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)

---

## **Project Overview**
This repository contains an analysis of daily screen time among students using Python and Exploratory Data Analysis (EDA). The goal is to understand patterns in student screen time, analyze differences by **gender** and **day type (Weekday vs Weekend)**, and visualize insights with various plots.

The analysis includes:  
- Cleaning and preprocessing raw student screen time data  
- Descriptive statistics (Mean, Median, Mode, Std Deviation, etc.)  
- Visualizations: Histograms, Boxplots, Violin Plots, Lollipop Charts, Bar Charts, and Pie Charts  
- Interpretation of patterns and outliers  

---

## **Dataset**

### **Files**
| File | Description |
|------|-------------|
| `student_screen_time_raw.csv` | Raw dataset (uncleaned) |
| `student_screen_time_cleaned.csv` | Cleaned dataset generated via Python code |
| `Student_Screen_Time_Analysis.ipynb` | Jupyter Notebook containing data cleaning, EDA, and visualizations |
| `Graphs.pdf` | PDF file with all visualization plots |

### **Dataset Columns**
1. **Gender** – Student gender (Male/Female)  
2. **Screen Time (hrs)** – Daily screen time in hours  
3. **Day** – Day of the week (Mon-Sun)  
4. **Day Type** – Derived column: Weekday or Weekend  

---

## **EDA & Visualizations**
- **Histograms:** Distribution of screen time by gender and day type  
- **Boxplots & Violin Plots:** Compare screen time spread and density  
- **Lollipop Chart:** Top 20 student screen time visualization  
- **Bar Charts:** Average screen time by gender and day type  
- **Pie Chart:** Gender distribution among students  

*All plots are also available in `Graphs.pdf`.*

---

## **Key Insights**
- Average daily screen time: `~8 hrs`  
- Some students exhibit unusually high screen time (outliers)  
- Screen time differs slightly between weekdays and weekends  
- Gender-wise patterns are visible in histograms and boxplots  

---

## **Requirements**
- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statistics`, `warnings`  
- Jupyter Notebook to run `Student_Screen_Time_Analysis.ipynb`

---

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Student-Daily-Screen-Time-Analysis.git
    ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Student_Screen_Time_Analysis.ipynb
   ```
3. Run the notebook to reproduce all EDA and visualizations.

---

## **License**

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for more details.

---

## **Author**

R Avantikaa
