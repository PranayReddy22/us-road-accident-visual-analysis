# 🚧 U.S. Road Accident Analysis using Visual Analytics

This project investigates road accident patterns across the United States by leveraging the large-scale **U.S. Accidents** dataset. Using advanced visualizations and data exploration techniques, we analyze the impact of environmental conditions, geography, infrastructure, and time on accident severity and frequency.

Developed as part of our Insight Foundry project, this work aims to help city planners, traffic management agencies, and public safety officials better understand accident triggers and develop localized safety interventions.

---

## 🎯 Objectives

- Identify accident hotspots at both national and city levels
- Understand correlations between accident severity and weather, road features, and time of day
- Propose actionable insights for improving emergency response and road infrastructure
- Create interactive and accessible visualizations to support data-driven policy-making

---

## 📊 Key Visualizations & Insights

- **Accident Severity vs Weather**  
  Stacked bar charts and violin plots showed that accidents in conditions like *scattered clouds* and *overcast* had higher severity than "clear" or "fair" weather.

- **Geospatial Analysis**  
  Heatmaps and interactive maps revealed dense clusters of accidents in cities like Los Angeles, Miami, and Houston, highlighting urban congestion and infrastructure strain.

- **Temporal Trends**  
  - Morning (7–9 AM) and evening (4–6 PM) rush hours had the highest accident counts.  
  - Winter months showed higher accident rates, especially in states with icy road conditions.  
  - Fridays recorded the most weekday accidents.

- **Infrastructure Risk Zones**  
  Features like *traffic signals*, *junctions*, and *crossings* were strongly associated with both high frequency and high severity of accidents.  
  Roundabouts and turning loops showed the least severe incidents, indicating safer design.

- **Accident Survivability & Amenities**  
  Cities with fewer nearby amenities and longer accident durations (like Atlanta) had more non-survivable cases, emphasizing the need for improved emergency accessibility.

- **Sentiment Analysis**  
  Word clouds and sentiment histograms of accident descriptions showed a slight skew toward negative sentiment, with frequent terms like “caution,” “exit,” and “northbound” pointing to common high-risk road contexts.

---

## 🧠 Data Source

- **U.S. Accidents Dataset (Kaggle)**  
  7.7 million records  
  46 attributes (weather, timestamps, location, infrastructure, etc.)

---

## 🛠️ Technologies Used

- Python (Pandas, Matplotlib, Seaborn, Plotly)
- NLP (TextBlob for Sentiment Analysis)
- Geospatial Visualization (Folium, Choropleth Maps)
- Jupyter Notebook, PowerPoint

---

## 🧾 Reports

- 📘 [Final Report PDF](TeamInsightFoundry_Final_Paper.pdf)
- 📊 [Presentation Slides](TeamInsightFoundry_Project_Presentation.pptx)

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).
