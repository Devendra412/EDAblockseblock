Titanic EDA (Seaborn / Kaggle) 

📊 Project Overview
This repository contains Exploratory Data Analysis (EDA) of the Titanic dataset using **Seaborn** and **Matplotlib**.

The analysis explores how passenger survival was influenced by class, sex, age, and fare.

📂 Repository Structure
- `titanic_eda.py` → Main analysis script
- `outputs/`
  - `titanic_dataset.csv` → Cleaned dataset copy
  - `*.png` → All generated graphs
- `README.md` → Project documentation

📈 Visualizations
1. **Passenger Count by Class**  
2. **Survival Rate by Class**  
3. **Survival by Sex**  
4. **Age Distribution by Survival (KDE)**  
5. **Age Distribution by Survival (Violin)**  
6. **Fare Distribution by Class**  
7. **Correlation Heatmap**

🔑 Key Insights
- **Class & Survival**: First-class passengers had higher survival rates.  
- **Sex & Survival**: Females survived at a much higher rate than males.  
- **Age**: Children/younger passengers had better survival odds.  
- **Fare**: Higher fares (wealthier passengers) correlate with better survival.  
▶️ How to Run
```bash
pip install pandas seaborn matplotlib
python titanic_eda.py
