# 🏠 Realty API Data Extraction

## 📌 Overview
This project demonstrates how to connect to the **Realty Mole Property API** to retrieve real estate property listings, transform the raw JSON response into a structured dataset, and export the results for further analysis. It highlights practical skills in **API integration, data wrangling, and reproducible workflows**.

---

## 🔑 What the Code Does
- **Imports core libraries**: Uses Python’s data stack (`numpy`, `pandas`, `matplotlib`, `seaborn`) for analysis and visualization, along with `requests` for API calls and `tqdm` for progress tracking.  
- **Connects to an external API**: Establishes a connection to the Realty Mole Property API through the `requests` library, passing authentication headers and query parameters.  
- **Defines query parameters**: Specifies latitude, longitude, search radius, and record limits to filter property listings.  
- **Handles authentication**: Uses API keys securely through request headers.  
- **Retrieves property data**: Sends a GET request to the API and receives a JSON response containing property details.  
- **Parses JSON into a DataFrame**: Converts the API response into a structured `pandas` DataFrame for easier manipulation and analysis.  
- **Exports results**: Saves the cleaned dataset into a CSV file (`Prop_Sale_Data_Sample.csv`) for downstream use in analytics or BI tools.  

---

## 🛠️ Skills Demonstrated
- **API Integration**: Connecting to and retrieving data from a third-party API.  
- **Data Wrangling**: Transforming semi-structured JSON into tabular format.  
- **Reproducibility**: Exporting results to CSV for consistent downstream analysis.  
- **Python Data Stack**: Leveraging `pandas` for data handling and preparing for visualization with `matplotlib` and `seaborn`.  

---

## 🚀 How to Use
1. Clone this repository.  
2. Install required Python libraries (`requests`, `pandas`, etc.).  
3. Insert your **RapidAPI key** into the headers section of the script.  
4. Run the notebook or script to generate the property dataset.  
5. Open the exported CSV file to explore property listings.  

---

## 📊 Potential Extensions
- Automate data pulls for multiple locations.  
- Build visualizations such as price distributions or geospatial heatmaps.  
- Integrate with BI dashboards (Power BI, Tableau).  
- Schedule recurring API calls to build a historical property dataset.  

---

## 🎯 Why This Project Matters
This project is a concise but powerful demonstration of how to **source, structure, and prepare real-world data** for analysis. It reflects the workflow of a data analyst or data scientist working with external APIs and showcases the ability to turn raw data into actionable insights.  

---

## 👤 About Me
I’m **Joseph Tulani Aytch**, a mission-driven Data Analyst based in the San Francisco Bay Area. With 5+ years of experience across insurance, HR, operations, and public sector analytics, I specialize in:  
- Translating complex data into actionable strategies for decision-makers.  
- Building reproducible workflows and recruiter-friendly documentation.  
- Driving impact in mission-driven organizations through compliance, budget monitoring, and stakeholder communication.  

I’m passionate about using **data storytelling and business intelligence** to create measurable community impact, particularly in areas like affordable housing, higher education, and public sector programs.  

---
