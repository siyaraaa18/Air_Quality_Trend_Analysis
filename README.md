## 🌍 Air Quality Trends Across Major Indian Cities (2015–2024)

## 📘 Project Overview

This project analyzes air quality trends across major Indian cities from 2015 to 2024. Using Python, the analysis identifies pollution patterns, seasonal variations, and key pollutants contributing to poor air quality. The insights from this study can help policymakers and citizens understand the state of air pollution and its potential health impacts.

**🎯 Objectives**
- Analyze the severity and distribution of AQI across major Indian cities
- Evaluate seasonal variations and identify peak pollution periods  
- Compare regional differences (North vs South vs West)
- Assess public health impact through AQI category analysis
- Investigate data quality through correlation analysis
- Provide foundation for targeted intervention strategies

## 📊 Dataset
- **Source**: Kaggle 
- **Time Period**: 2015-2024
- **Cities Covered**: Delhi, Mumbai, Kolkata, Chennai, Bangalore
- **Parameters**: AQI, PM2.5, PM10, NO2, SO2, CO, O3
- **Records**: 18,265 daily observations

## 🛠️ Technical Stack
- **Python 3.13.7**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualizations
- **Jupyter Notebook** - Interactive development

## 🧠 Skills Demonstrated
- **Data Cleaning & Feature Engineering**
- **Exploratory Data Analysis (EDA)**
- **Data Visualization** with Matplotlib & Seaborn
- **Statistical Analysis** & Insight Generation
- **Trend & Pattern Recognition** in time-series data
- **Correlation Analysis** for multi-variable datasets

## 🔍 Key Features Analyzed

### 🧹 Data Cleaning & Preprocessing
- **Missing Values Handling** - Identified and treated null values
- **Data Type Conversion** - DateTime formatting for temporal analysis
- **Duplicate Removal** - Ensured data integrity
- **City Name Standardization** - Consistent naming conventions
- **Outlier Detection** - IQR method for statistical outliers
- **Feature Engineering** - Created Season, Month, AQI_Level columns

### 📊 Exploratory Data Analysis & Visualization
- **Distribution Analysis** - Histograms and KDE plots for AQI and pollutants
- **Statistical Summaries** - Descriptive statistics and correlation matrices
- **Trend Analysis** - Line plots for yearly and seasonal patterns
- **Comparative Analysis** - Bar charts for city-wise and region-wise comparisons
- **Categorical Analysis** - Pie charts for AQI category distributions
- **Box & Violin Plots** - Outlier detection and distribution spread

## 🔬 Analytical Insights & Impact
- **Uniform National Crisis**: All 5 cities show nearly identical AQI values (249-253), indicating nationwide challenge
- **Limited Lockdown Impact**: COVID-19 restrictions provided only temporary improvement, revealing need for systemic changes
- **Winter Peaks**: Cooler temperatures trap pollutants, leading to highest AQI in winter months  
- **Monsoon Relief**: Rainfall provides temporary air quality improvement
- **Northern Dominance**: Wider AQI spread in Northern regions indicates more extreme pollution fluctuations
- **Consistent Hazard**: Population faces dangerous air quality on 80% of days annually

 ## 📊 Key Findings
- **Nationwide Crisis**: All cities show nearly identical poor AQI (249-253 range)
- **Persistent Hazard**: 4 out of 5 days are in "Poor" to "Severe" categories
- **Regional Patterns**: Northern/Western regions show higher AQI than Southern cities
- **Seasonal Impact**: Winter shows highest AQI, monsoon provides limited relief
- **COVID Insight**: 2020 lockdowns provided only temporary, minimal improvement
- **Primary Pollutants**: PM2.5 and PM10 show highest concentrations and spread
- **Data Quality**: Near-zero correlations suggest monitoring inconsistencies

## 💡 Insights for Policy
- **Need for coordinated national-level strategies**
- **Focus on particulate matter reduction** 
- **Enhanced monitoring and data quality assurance**
- **Public health advisory systems**
- **Sustainable urban planning interventions**

## ⚠️ Data Quality & Limitations
- **Correlation Inconsistencies**: Near-zero relationships (0.0006-0.0111) between pollutants and AQI
- **Monitoring Challenges**: Potential methodological inconsistencies in AQI calculation
- **Scale Limitations**: AQI capped at 500 affects outlier detection and statistical analysis
- **Standardization Need**: Highlights requirement for consistent monitoring protocols

**Key Finding:** The near-zero correlations highlight the need for standardized AQI calculation methodologies across monitoring stations.

## 🎯 Conclusion

This project demonstrates Python's effectiveness in environmental data analysis, revealing India's persistent air quality crisis from 2015-2024. The analysis shows consistently hazardous AQI levels across all major cities with no decade-long improvement, highlighting an urgent public health emergency where 80% of days fall in "Poor" to "Severe" categories.

While data quality considerations emerged, the clear patterns provide a data-driven foundation for policymakers to develop coordinated national strategies, improve monitoring systems, and implement effective pollution control measures for sustainable air quality management.

---
## 👥 Author
**Siyara Sathar**  
Data Analytics Student  
📧 siyarasathar18@gmail.com  
