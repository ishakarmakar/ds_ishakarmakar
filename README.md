# Trader Behavior vs Market Sentiment Analysis

#### **FOLDER STRUCTURE**

ds\_ishakarmakar/

│

├── notebook\_1.ipynb       

├── csv\_files/              

│   ├── fear\_greed\_index.csv

│   ├── historical\_data.csv

│

├── outputs/

│   ├── avg\_pnl\_by\_sentiment.png

│   ├── long\_vs\_short\_performance.png

│   ├── trade\_counts.png

│   ├── regression\_line.png

│   ├── predicted\_vs\_actual.png

│   ├── residual\_plot.png

│   ├── rf\_feature\_importance.png

│   └── risk\_volatility.png

│

├── ds\_report.pdf           

│

└── README.md

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

#### PROJECT OVERVIEW

This project analyzes how trader performance (profitability, risk, activity levels) aligns or diverges from the overall Bitcoin market sentiment as measured by the Fear \& Greed Index.

Two key datasets were used:

* Fear \& Greed Sentiment Data
* Hyperliquid Historical Trader Data

The analysis includes:

* Data cleaning \& preprocessing
* Merging sentiment with trade timestamps
* EDA (profitability, trade volume, BUY/SELL behavior)
* Risk analysis (volatility, downside risk)
* Regression modeling
* Random Forest nonlinear modeling
* Strategy recommendations

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

#### SETUP INSTRUCTIONS 

1\. Open notebook in Google Colab

All work should be done in Google Colab to match the assignment requirements.

•	Upload notebook\_1.ipynb into Google Colab

•	Make sure runtime = Python 3

2\. Create folder structure in your Drive

Inside your Colab environment or Google Drive:

csv\_files/

outputs/

Upload the provided datasets inside the csv\_files/ folder.

3\. Install dependencies 

Colab already includes all standard libraries, but in case you need:

!pip install pandas numpy seaborn matplotlib statsmodels scikit-learn

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

#### OUTPUT FOLDER OVERVIEW

The outputs/ folder contains all visual results, including:

•	Profitability by sentiment

•	Long vs short performance

•	Trade volume distribution

•	Regression line

•	Predicted vs actual plot

•	Residual plot

•	Random Forest feature importance

•	Risk volatility chart

These visuals support the conclusions in the final report.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

#### FINAL REPORT

The ds\_report.pdf summarizes:

•	Key insights

•	Relationship between sentiment \& performance

•	Market behavior patterns

•	Risk \& volatility patterns

•	Best trading strategies

•	Modeling results

•	Actionable recommendations

&nbsp;             



