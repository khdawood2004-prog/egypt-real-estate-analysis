# egypt-real-estate-analysis
An end-to-end data analysis project investigating the key drivers of residential property prices in Egypt using a dataset of ~20,000 listings. Includes data cleaning, hypothesis testing, and a price prediction ML model.

# Egyptian Real Estate Market Analysis 🏠

## Project Overview
This project explores the key drivers of residential property prices in Egypt. By analyzing ~20,000 real estate listings, we identify how features like size, location, and property type influence market value.

## 📊 Dataset
The data is sourced from **Kaggle (Hassan Khaled)**, containing 19,925 records of real-world scraped listings from Egyptian property websites.

## 🛠️ Key Steps Taken
1. **Data Preprocessing**: 
   - Cleaned missing values and handled outliers.
   - Feature engineering: Extracted city names from addresses and parsed bedroom counts.
2. **Exploratory Data Analysis (EDA)**: 
   - Identified that property size, bathrooms, and bedrooms explain over 80% of price variation.
3. **Hypothesis Testing**: 
   - Confirmed significant relationships for size and property type (Villas vs Apartments).
   - Found that Cairo is not significantly more expensive than premium coastal areas in this dataset.
4. **Machine Learning**: 
   - Built a Linear Regression model ($R^2 = 0.53$) for price prediction.

## 📈 Key Findings
- **Physical Traits Matter Most**: Size and bedroom count are the primary price drivers.
- **Payment Method**: There is no significant price difference between Cash and Installment listings.
- **Location**: Coastal destinations (North Coast/Red Sea) compete closely with Cairo in pricing.

## 💻 Tech Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn

## Team Members
- Razan Waleed
- Khaled Ahmed
- Youssef Mohamed
- Hamza Mohamed

---
*This project was developed as part of the C-DE211: Data Analysis course at Egypt University of Informatics.*
