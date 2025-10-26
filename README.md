# 🕵️ Surrey Police Crime Analysis (2022)
Data-driven analysis of Surrey Police crime reports for 2022, exploring crime distribution, trends, and hotspots through visualization and statistical methods

## 📊 Project Overview
This project presents an exploratory data analysis (EDA) of **Surrey Police crime reports for 2022**. 
This investigation examines crime data collected by the Surrey Police for 2022. The crime data was obtained from the Surrey Police Department record , where it has been updated regularly, and is publicly available. The data set contains information on crimes such as anti-social behaviour, bicycle theft, burglary, criminal damage and arson, drugs, weapon possession, public order, robbery, shoplifting, person theft, vehicle crime, violence and sexual assaults, and other crimes. The data collection additionally includes each crime's month, location, LSOA code, LSOA name, Crime ID, and Context.

To begin the investigation, the data was collected from the police department website and was filtered for only crimes reported in the surrey police department from January to December of 2022, for accurate analysis the data was cleaned by checking for missing values, duplicates, and invalid data so as to ensure the data is suitable for analysis Exploratory data analysis (EDA) techniques were employed to better understand the data set. The exploratory data analysis involves evaluating the data distribution, identifying patterns or trends, visualizing the data using various statistical and graphical techniques, and validating any observed patterns or trends.

The use of cleaning and exploratory data analysis enabled a thorough and accurate study of the data, thereby making sure that the analysis is founded on an accurate and dependable methodology. The insights gathered from the data were used to form recommendations and conclusions.

## 🔍 Key Insights
- **Top Crime Locations:** High streets, parking areas, and supermarkets had the highest reported incidents.  
- **Monthly Trends:** Crime rates peaked in summer months, with noticeable fluctuations throughout the year.  
- **Common Crime Types:** Violence and sexual offences were the most reported crime categories.  
- **Geospatial Hotspots:** Central Surrey areas showed higher concentrations of crime reports.

## 🧰 Tools & Technologies
- **Language:** Python  
- **Libraries:** `pandas`, `matplotlib`, `seaborn`, `geopandas`, `folium`  
- **Visualization Techniques:**  
  - Grouped histograms comparing monthly crime types  
  - Time-series trend analysis of monthly counts  
  - Top 10 crime locations visualization  
  - Interactive geospatial mapping  

## 📁 Project Structure
📂 surrey-crime-analysis-2022
┣ 📜 README.md
┣ 📊 data/
┃ ┗ crime_data_2022.csv
┣ 📓 notebooks/
┃ ┗ surrey_crime_analysis.ipynb
┣ 📈 visuals/ 
┗ 📄 requirements.txt


🧠 Future Work

Extend analysis to include 2023–2024 data for comparison

Incorporate predictive modeling for hotspot detection

Develop an interactive dashboard using Plotly or Streamlit

📜 License

This project is licensed under the MIT License
.

👨‍💻 Author

dayozken@yahoo.com
