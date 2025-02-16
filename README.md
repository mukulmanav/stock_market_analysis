# 📈 Stock Market Analysis

## 📌 Objective
This project aims to analyze stock market trends and price movements using historical stock data from major tech companies (**Apple, Amazon, Google, Microsoft**). The analysis focuses on price changes over time, moving averages, correlation between stock prices, and resampling techniques.

## 📊 Libraries Used
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical operations
- **matplotlib**: Data visualization
- **seaborn**: Statistical data visualization
- **glob**: File handling
- **plotly**: Interactive visualizations

## 📂 Data Extraction & Preprocessing
- Extracted multiple CSV files containing stock data.
- Combined stock data from **Apple, Amazon, Google, and Microsoft** into a single DataFrame.
- Checked for missing values and converted the `date` column to a proper datetime format.

## 🔍 Key Analyses Performed

### 1️⃣ **Stock Price Change Over Time**
- **Checked for null values** and cleaned the dataset.
- Created **trend charts** showing stock price movements over time.

### 2️⃣ **Moving Average Analysis**
- Calculated **moving averages** for different window sizes (10, 20, and 30 days).
- Compared stock prices with moving averages using **line plots**.

### 3️⃣ **Daily Return Calculation**
- Used the **daily return formula**:
  
  \[ \text{Daily Return} = \frac{\text{Closing Price} - \text{Opening Price}}{\text{Opening Price}} \times 100 \]
  
- Plotted **daily return trends** for Apple stock.

### 4️⃣ **Resampling Analysis of Closing Stock Prices**
- Resampled stock prices on different time intervals:
  - **Yearly (`Y`)**
  - **Quarterly (`Q`)**
  - **Monthly (`M`)**
  - **Weekly (`W`)**
  - **Daily (`D`)**
  - **Minute (`3T`)**
  - **30-second bins (`30S`)**

### 5️⃣ **Stock Price Correlation Analysis**
- Checked whether **closing prices of major tech companies are correlated**.
- Used a **heatmap** to visualize the correlation matrix.

### 6️⃣ **Daily Return Correlation Analysis**
- Analyzed whether **daily percentage changes in closing prices of different stocks** are correlated.
- Created a **PairGrid plot** with different visualizations:
  - **Histogram on the diagonal**
  - **KDE plots on the upper diagonal**
  - **Scatter plots on the lower diagonal**

## 📈 Visualizations
- **Line Plots**: Trend analysis of stock prices and moving averages.
- **Heatmaps**: Correlation of stock closing prices and daily returns.
- **Pair Plots**: Relationship between daily percentage changes of different stocks.
- **Resampling Charts**: Yearly and monthly trends in closing stock prices.

## 🏆 Conclusion
- **Apple and Amazon stock price changes show a linear relationship to some extent**.
- **Moving averages** help smooth price fluctuations and identify trends.
- **Tech stocks show some correlation in daily returns**, but they do not move identically.
- **Resampling allows for better understanding of stock trends over different time periods**.

