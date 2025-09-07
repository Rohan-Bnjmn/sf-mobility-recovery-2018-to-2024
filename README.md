# San Francisco Mobility Recovery (2014–2024)

## 📌 Project Overview
Has San Francisco really bounced back after the pandemic?  
This project explores urban recovery using **mobility signals**: parking meter revenue, Muni ridership, and BART station exits.  
By combining open data sources and geospatial analysis, the notebook uncovers how different parts of the city are recovering — and where the core still lags behind.

---

## 🔍 Key Questions
- How did **parking revenue** change between 2018, 2020, and 2024?  
- Which neighborhoods rebounded fastest, and which remain below pre-pandemic levels?  
- How has **Muni ridership** shifted by route since 2018?  
- What do **BART exits** at San Francisco stations tell us about commuting and office return?  

---

## 📊 Data Sources
- **Parking meters**: SFgov open data (2018, 2020, 2024 transaction chunks + metadata).  
- **Muni ridership**: SFMTA average daily boardings + route shapefiles.  
- **BART exits**: Daily station exits (2014–2024), with SF station codes filtered.  
- **Neighborhood boundaries**: SF Find Neighborhoods shapefile.  

---

## ⚙️ Tools & Libraries
- **Python**: pandas, numpy, geopandas  
- **Visualization**: folium, matplotlib, plotly  
- **Mapping**: shapefiles, choropleths, heatmaps  
- **Notebook Environment**: Jupyter  

---

## 📈 Results & Insights
- 🚗 **Parking Revenue**: Down ~50% in 2020, partially recovered by 2024 but **downtown neighborhoods remain 25–30% below 2018**.  
- 🚌 **Muni Ridership**: Still below baseline, but some central lines show relative strength in 2024 vs 2018.  
- 🚇 **BART Exits**: Downtown stations (Embarcadero, Montgomery, Powell, Civic Center) remain only **60–70% recovered**, reflecting the shift to remote work.  
- 📍 **Spatial Patterns**: Mixed-use and residential neighborhoods (Mission Bay, Union Street) recovered faster than the Financial District and Union Square.  

---

## 📷 Sample Visuals 

**Parking Revenue Recovery (2024 vs 2018)**  
<img src="https://imgur.com/mm2Jpkw.png" alt="Parking Revenue" width="600"/>

**Muni Ridership Ratios (2024 vs 2018)**  
<img src="https://imgur.com/GH6Tw9x.png" alt="Muni Ridership" width="600"/>


**BART Exits at SF Stations (2014–2024)**  
<img src="https://imgur.com/Jjpf6xX.png" alt="BART Exits" width="600"/> 

---

## ⚠️ Limitations
- Parking revenue may be influenced by pricing or enforcement changes, not just demand.  
- Transit ridership doesn’t capture tourism or foot traffic patterns.  
- BART recovery is commuter-focused; it doesn’t reflect neighborhood activity.  

---

## 🚀 Future Directions
- Add **office occupancy (Kastle Systems)** to measure return-to-office.  
- Layer in **foot traffic data** (SafeGraph, Placer.ai) for retail/tourism trends.  
- Compare SF recovery against other Bay Area cities (Oakland, San Jose).  
- Build a **Streamlit dashboard** for interactive exploration.  

---

## ✍️ Author
**Rohan Benjamin**  
- [LinkedIn](https://www.linkedin.com/in/rohanbenjamin)  
- [GitHub](https://github.com/rohanbenjamin)  

---

## 📜 License
This project is for educational and portfolio purposes.  
Data sources belong to their respective agencies (SFMTA, BART, City of SF).  
