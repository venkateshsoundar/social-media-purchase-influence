# Influence of Social Media Usage on Consumer Purchasing Decisions

An end-to-end analysis exploring how patterns of social media engagement shape consumers’ buying behavior, combining survey data preprocessing, exploratory analysis, statistical modeling, and actionable marketing insights.

---

## 👥 Group Members
- Ayush Senthil Nelli  
- Hritvi [Lastname]  
- Satyam Kapoor  
- Venkateshwaran Balu Soundararajan  

---

## 📁 Repository Structure

```
├── data/
│   ├── raw/                       ← original survey CSV(s)
│   └── processed/                 ← cleaned & merged data
│
├── notebooks/
│   └── Data606_ProjectReport_Final.ipynb   ← full analysis
│
├── scripts/
│   ├── data_cleaning.py           ← data preprocessing pipeline
│   ├── eda_plots.py               ← EDA and visualization functions
│   └── modeling.py                ← statistical models (regression, clustering)
│
├── reports/
│   └── figures/                   ← static images for presentation
│
├── requirements.txt               ← project dependencies
└── README.md                      ← you are here
```

---

## 🛠️ Setup & Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/venkateshsoundar/social-media-purchase-influence.git
   cd social-media-purchase-influence
   ```

2. **Create & activate** a Python environment (recommended)  
   ```bash
   python3 -m venv venv
   source venv/bin/activate    # Mac/Linux
   venv\Scripts\activate       # Windows
   ```

3. **Install** required packages  
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch** the Jupyter notebook  
   ```bash
   jupyter notebook notebooks/Data606_ProjectReport_Final.ipynb
   ```

---

## 🔍 Data & Methodology

1. **Data Ingestion & Cleaning**  
   - Load raw survey responses on social media habits and recent purchase history.  
   - Handle missing values, encode categorical features, standardize numeric scales.

2. **Exploratory Analysis**  
   - Visualize usage frequency vs. spending patterns.  
   - Correlation matrices to spot key predictors.

3. **Modeling & Validation**  
   - Build regression and classification models to quantify influence of engagement metrics (time spent, platform mix, content type) on purchase likelihood and basket size.  
   - Evaluate with cross-validation, report R² / accuracy.

4. **Insights & Recommendations**  
   - Identify top 3 engagement behaviors that drive conversion.  
   - Provide targeted marketing suggestions for each consumer segment.

---

## 📊 Key Findings

- **Time on Instagram** positively correlates with discretionary spend (R² ≈ 0.42).  
- **Frequency of influencer interactions** boosts purchase likelihood by ~18%.  
- **User-generated reviews** have a stronger effect on high-value items than brand-produced ads.

---

## 🤝 Contributing

1. Fork the repository  
2. Create a feature branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes (`git commit -m "Add feature"`)  
4. Push (`git push origin feature/YourFeature`) and open a Pull Request

---

## 📜 License

This project is licensed under the MIT License. Feel free to use and adapt for your own analyses.
