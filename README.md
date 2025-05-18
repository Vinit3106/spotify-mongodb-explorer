#  Spotify MongoDB Explorer – Midterm Assignment



---

##  Project Overview

This project explores how to build a **MongoDB JSON document database** using the **Spotify API** to extract, store, analyze, and visualize music-related data. It focuses on:

- **Top albums and artists** by genre  
- **Albums with highest track counts**  
- **Genre distribution** and market availability  
- **Interactive geographic visualizations**

We used **MongoDB Atlas**, Python, and the **Spotify Web API** to fetch real-time data, and then ran **advanced queries** to explore insights about music trends globally.

---

## 🛠️ Technologies Used

- **MongoDB Atlas** (Cloud NoSQL Database)  
- **Spotify Developer API**  
- **Python (Requests, Pandas, PyMongo)**  
- **Folium for Interactive Maps**  
- **Jupyter Notebook**

---

## 📦 Files Included

| File                                               | Description                                                    |
|----------------------------------------------------|----------------------------------------------------------------|
| `Vinit_Kataria_DBMS.ipynb`                         | Full notebook with data extraction, storage, and analysis      |
| `top_albums_map.html`                              | Interactive Folium map showing album markets                   |


---

##  Key Insights

- **Hans Zimmer** had the highest album count and dominated the soundtrack genre  
- **Cynthia Erivo** had the highest average tracks per album (27.38)  
- **Rap** was the genre with the most distinct artists  
- **Musicals** had the highest average track count per album  
- **Top albums by track count** included soundtracks and deluxe editions  

All results were retrieved using **MongoDB queries** and Python-based aggregation.

---

##  Map Visualization

The included `top_albums_map.html` file visualizes the **top 3 albums** by market across countries using **Folium**. Interactive popups display:

- Artist Name  
- Album Title  
- Total Tracks  
- Genre  

Markers are geocoded based on country market availability from Spotify.

---

##  Future Enhancements

- Add user input for **custom genre search**  
- Integrate **sentiment analysis** on album reviews (if available)  
- Deploy as a lightweight **Flask or Streamlit app**  
- Add support for **Spotify playlist export**

---
