# 🏆 English Premier League Match Analysis and Prediction System 🏆

**Developers:**  
- Mohamed Helmy (20102540)  
- Yousef Ali (20101108)  

**Supervisor:**  
- Dr. Essam Seddik  
- Eng. Aya Mohamed  

---

## 📋 **Project Overview**
This project explores the match day statistics of the **2021-2022 English Premier League season** and applies **Machine Learning (Naive Bayes)** to predict match outcomes. With an in-depth analysis of teams, goals, and referees, the project delivers valuable insights for football enthusiasts, analysts, and sports betting systems.

The system is backed by interactive data dashboards, CSV data processing, and predictive models to enhance understanding and forecasting of game results.

---

## 📊 Data Source  
We use the **2021-2022 English Premier League Match Data** available on **[Kaggle](https://www.kaggle.com/datasets/evangower/premier-league-match-data)**.

---

## 📈 Dataset Columns  

| Column        | Description                                   |
|---------------|-----------------------------------------------|
| Date          | Date when the match was played               |
| Home Team     | The home team of the match                   |
| Away Team     | The away team of the match                   |
| FTHG          | Full-time home goals scored                  |
| FTAG          | Full-time away goals scored                  |
| FTR           | Full-time match result (H=Home, A=Away, D=Draw) |
| HTHG          | Halftime home goals scored                   |
| HTAG          | Halftime away goals scored                   |
| HTR           | Halftime result (H, A, D)                    |
| Referee       | Referee who officiated the match             |

---

## 🚀 How to Run the Project  

### 1. **Data Exploration**  
Open and run `code.ipynb` to explore match statistics, clean the dataset, and visualize important patterns.


bash
jupyter notebook code.ipynb
## 📚 Key Features  

- **Data Exploration:** Analyze match outcomes, team stats, and referee decisions.  
- **Machine Learning:** Predict match outcomes using the Naive Bayes model.  
- **Interactive Dashboard:** Visualize match details, win rates, and other stats via Power BI.  
- **Prediction CSV:** Export and review model predictions for further analysis.  

---

## 🤖 Machine Learning Model  

We implemented the **Naive Bayes classifier**, a probabilistic machine learning model, to predict match outcomes (Home win, Away win, Draw). The following steps were followed:

1. **Data Cleaning and Preprocessing**  
   - Handling missing data  
   - Encoding categorical variables  
   - Feature scaling  

2. **Model Training and Evaluation**  
   - Training the Naive Bayes model on match statistics  
   - Testing its performance  

3. **Saving Predictions**  
   - Predicted outcomes for the test dataset are saved to `prediction.csv`.  

---

## 📊 Power BI Dashboard  

### **Key Insights:**  
- **Team performance** over the season  
- **Top goal-scoring teams**  
- **Impact of referees** on match outcomes  

To explore, open `Dashboard.pbix` using **Power BI Desktop**.
