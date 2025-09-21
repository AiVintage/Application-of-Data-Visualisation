🕵️‍♂️ EDA Report – US Arrests

📌 Project Overview  
This project performs an **Exploratory Data Analysis (EDA)** on the **US Arrests dataset (1973)**.  
The dataset contains violent crime statistics for the 50 U.S. states, focusing on murder, assault, rape, and urban population.  
The goal is to uncover crime patterns, correlations, and trends across different states.

📂 Dataset  
- **Source:** USArrests (1973)  
- **Features:**  
  - Murder: Arrests for murder (per 100,000 residents)  
  - Assault: Arrests for assault (per 100,000 residents)  
  - Rape: Arrests for rape (per 100,000 residents)  
  - UrbanPop: % of population living in urban areas  
- **Index:** State names (used instead of "City")  

Sample Data:

| State       | Murder | Assault | UrbanPop | Rape |
|-------------|--------|---------|----------|------|
| Alabama     | 13.2   | 236     | 58       | 21.2 |
| Alaska      | 10.0   | 263     | 48       | 44.5 |
| Arizona     | 8.1    | 294     | 80       | 31.0 |
| Arkansas    | 8.8    | 190     | 50       | 19.5 |
| California  | 9.0    | 276     | 91       | 40.6 |

⚙️ Approach  

**Data Cleaning**  
- No missing values detected  
- All columns numeric and ready for analysis  
- Index renamed to represent state names  

**Exploratory Steps**  
- Histograms for variable distributions  
- Correlation heatmap & pairplot  
- Boxplots for outlier detection  
- Ranking of top states by Murder, Assault, and Rape  

📊 Results  

**Top 5 States by Murder Rate:** Georgia, Mississippi, Louisiana, Florida, South Carolina  
**Top 5 States by Assault Rate:** North Carolina, Florida, Maryland, Arizona, New Mexico  
**Top 5 States by Rape Rate:** Nevada, Alaska, California, Colorado, Michigan  

**Findings:**  
- Murder and Assault are strongly correlated.  
- UrbanPop does not strongly explain violent crime.  
- Rape moderately correlates with Murder & Assault.  
- Georgia, Florida, and Mississippi consistently rank high in crime.  
- Lower-crime states are concentrated in the Midwest and Northeast (e.g., Vermont, North Dakota).  
- Outliers exist in Assault and Rape metrics.  

✅ Key Takeaways  
- Violent crime variables cluster together (Murder, Assault, Rape).  
- Urbanization alone doesn’t predict crime levels.  
- Regional differences suggest socio-economic or cultural influences.  
- Outlier states highlight potential anomalies in reporting or genuine spikes.  

🛠️ Tech Stack  
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, reportlab  
- **Tools:** Jupyter Notebook  

👨‍💻 Author  
**AiVintage (Veli)**  
_Data Science Graduate | Skilled in Python, Machine Learning, AI, SQL & Data Analysis_  
[GitHub](https://github.com/AiVintage) | [LinkedIn](#)  
