# 🏠 Real Estate Data Analysis - Mexico & Brazil

## 📌 Overview
This project is part of the **WorldQuant University Applied Data Science Lab**.  
The goal was to explore real estate market data from **Properati.com** for Mexico and Brazil, and answer the key question:

> **Are housing prices influenced more by property size or by location?**

The analysis covers **data cleaning, exploratory data analysis (EDA), and visualization** using Python.

---

## 📂 Project Structure

### 1. Lessons - Mexico Housing Data
- **Lesson 1:** Organizing Tabular Data in Python  
  *Python lists, dictionaries, and tabular data basics.*
- **Lesson 2:** Preparing Mexico Data  
  *Data cleaning with pandas (NaN removal, column transformations).*
- **Lesson 3:** Exploratory Data Analysis  
  *Scatter plots, box plots, and correlations.*
- **Lesson 4:** Location vs Size Analysis  
  *Determining the stronger price predictor.*

### 2. Assignment - Brazil Housing Data
Replicates the Mexico analysis with a **new dataset** to uncover:
- Regional differences in home prices.
- Price vs. size correlation in Southern Brazil.

---

## 🛠 Skills & Tools Used
- **Languages:** Python  
- **Libraries:** pandas, matplotlib, plotly  
- **Techniques:**
  - Data import & cleaning  
  - Feature extraction & transformation  
  - Data visualization (scatter, box, histograms, bar charts)  
  - Correlation analysis  
  - Regional grouping and aggregation

---

## 📊 Key Steps in Brazil Analysis
1. **Data Cleaning:**
   - Handle missing values.  
   - Extract latitude/longitude from combined fields.  
   - Create `state` column from location strings.  
   - Convert price values to USD.

2. **Data Exploration:**
   - Summary statistics for area and price.  
   - Price distribution histograms.  
   - Home size distribution boxplots.  
   - Regional mean price analysis.

3. **Southern Brazil Focus:**
   - Identify states with most properties.  
   - Scatter plots of price vs. area.  
   - Correlation coefficient calculation per state.

---

## 📈 Insights
- **Location** often had a stronger correlation with price than size.  
- Regional price differences were significant, especially between urban and rural areas.  
- Some southern states showed moderate to high positive correlations between property size and price.

---

## 🚀 How to Run the Project
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/real-estate-analysis.git
   cd real-estate-analysis
