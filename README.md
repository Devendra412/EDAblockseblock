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
1. **Passenger Count by Class*
  <img width="887" height="623" alt="Screenshot 2025-09-17 004336" src="https://github.com/user-attachments/assets/d60faf25-fead-408b-9f2c-ad3edfb9f178" />

  
2. **Survival Rate by Class**
   
    <img width="873" height="608" alt="Screenshot 2025-09-17 004349" src="https://github.com/user-attachments/assets/317f7116-2d52-4a93-9904-55998797a31d" />

3. **Survival by Sex**
   <img width="878" height="614" alt="Screenshot 2025-09-17 004406" src="https://github.com/user-attachments/assets/d270fd93-0b0d-4afa-88df-3eb23e23cc97" />

4. **Age Distribution by Survival (KDE)**
   <img width="899" height="616" alt="Screenshot 2025-09-17 004418" src="https://github.com/user-attachments/assets/21736e2d-fba3-4fed-a58d-5a1ed2a03f78" />

5. **Age Distribution by Survival (Violin)**
    <img width="865" height="620" alt="Screenshot 2025-09-17 004429" src="https://github.com/user-attachments/assets/77cdb5bf-ef1a-4315-8869-cce42578042e" />

6. **Fare Distribution by Class**
    <img width="881" height="615" alt="Screenshot 2025-09-17 004439" src="https://github.com/user-attachments/assets/5e6789fd-c87c-493f-81df-85020095c359" />

7. **Correlation Heatmap**
   
    <img width="635" height="592" alt="Screenshot 2025-09-17 004449" src="https://github.com/user-attachments/assets/2215d640-e7a7-4dc9-b96d-3fc10784e739" />


🔑 Key Insights
- **Class & Survival**: First-class passengers had higher survival rates.  
- **Sex & Survival**: Females survived at a much higher rate than males.  
- **Age**: Children/younger passengers had better survival odds.  
- **Fare**: Higher fares (wealthier passengers) correlate with better survival.  
▶️ How to Run
```bash
pip install pandas seaborn matplotlib
python titanic_eda.py
