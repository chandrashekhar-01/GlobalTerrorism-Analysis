# Global Terrorism Analysis

This project performs **exploratory data analysis (EDA)** and **data mining** on the [Global Terrorism Dataset](https://www.kaggle.com/datasets/START-UMD/gtd) from Kaggle.  
It aims to uncover insights and global trends in terrorism incidents across the world using **Python data analytics and visualization tools**.

---

## 📊 Project Overview

The **Global Terrorism Analysis** project focuses on analyzing patterns, trends, and the overall impact of terrorism globally.  
The dataset includes records of terrorist incidents from 1970 onwards, containing attributes like country, region, weapon type, target type, casualties, and more.

**Objectives:**
- Explore and preprocess the Global Terrorism Dataset.  
- Identify countries and regions most affected by terrorism.  
- Analyze trends in attacks, weapons used, and target types.  
- Visualize data patterns for better interpretation and policy insight.  

---

## 🧠 Key Insights

Some of the major insights derived from this analysis include:
- Countries with the highest number of terrorist incidents.  
- The most active terrorist organizations.  
- Yearly and regional trends in terrorism activities.  
- Common attack types and target categories.  
- Fatalities and casualties distribution over time.  

---

## 🧰 Tools & Technologies Used

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python 3 |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Data Source** | Kaggle Global Terrorism Dataset |
| **Environment** | Jupyter Notebook / Google Colab |

---

## 🗂️ Folder Structure

```text
Global_Terror_Analysis/
│
├── terror_analysis.ipynb        # Main Jupyter Notebook
├── globalterrorismdb.csv        # Dataset (Kaggle source)
├── README.md                    # Project documentation
└── outputs/                     # (Optional) Exported plots or reports
```
## ⚙️ How to Run the Project

### 🧩 Clone the Repository
```bash
git clone https://github.com/<your-username>/Global-Terror-Analysis.git
cd Global-Terror-Analysis
```
## 📈 Visualizations & Analysis Performed

-  **Yearly Terrorism Trends**  
-  **Geographical Distribution by Country & Region**  
-  **Most Common Targets and Attack Types**  
-  **Weapon Usage Statistics**  
-  **Top Terrorist Groups by Activity**  
-  **Casualties and Fatalities Over Time**

## 🔮 Future Improvements

-  Add **interactive dashboards** using Plotly Dash or Power BI  
-  Apply **Machine Learning** for attack type prediction  
-  Integrate **Geospatial visualization** using Folium or Mapbox  
-  Automate **report generation** through scripts or dashboards  

---
## 🧾 About the Dataset

The **Global Terrorism Database (GTD)** is an open-source dataset that includes **systematic information on terrorist events worldwide** from **1970 through recent years**.  
It is maintained by the [National Consortium for the Study of Terrorism and Responses to Terrorism (START)](https://www.start.umd.edu/gtd).

### 📊 Dataset Details

- **Source:** [Kaggle – Global Terrorism Database](https://www.kaggle.com/datasets/START-UMD/gtd)  
- **Records:** Over **180,000 terrorist incidents**  
- **Time Period:** 1970 – 2017  
- **File Format:** CSV  
- **Size:** ~150 MB  

### 📂 Key Columns
| Column | Description |
|---------|-------------|
| `iyear` | Year of the incident |
| `imonth` | Month of the incident |
| `iday` | Day of the incident |
| `country_txt` | Country where the incident occurred |
| `region_txt` | Geographical region |
| `attacktype1_txt` | Type of attack (e.g., Bombing, Armed Assault) |
| `targtype1_txt` | Target type (e.g., Military, Civilians) |
| `weaptype1_txt` | Weapon type used |
| `gname` | Name of the terrorist group |
| `nkill` | Number of people killed |
| `nwound` | Number of people wounded |
| `summary` | Short description of the incident |

### 🧠 Data Usage in This Project

- Used for **Exploratory Data Analysis (EDA)** and **visualization**.  
- Focused on **global trends, country-wise incidents, and attack patterns**.  
- Aggregated data to show **most affected regions and groups**.  
- Cleaned and preprocessed missing values for consistent analysis.  

### ⚠️ Disclaimer
This dataset is intended **for academic and analytical purposes only**.  
It should not be used to make political, ideological, or security-related generalizations.

---


