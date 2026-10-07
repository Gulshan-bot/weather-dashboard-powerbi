<img width="1320" height="738" alt="dashboard" src="https://github.com/user-attachments/assets/5314a82b-4658-45c0-8539-9c17b6468f78" />
I built a live Weather & Air Quality dashboard in Power BI 🌦️

Instead of using a ready-made dataset, I pulled the data straight from a REST API (WeatherAPI) using Power Query.

What it covers:
• 6 cities – Delhi, Noida, Bangalore, Mumbai, Surat, Kolkata
• Current weather + 7-day and hourly forecast
• Air quality (PM2.5, PM10, O₃, NO₂, SO₂, CO) with colour-coded status and health tips

What I worked on:
→ Parsing nested JSON in Power Query and combining 6 API calls into one master table
→ Splitting it into clean current / daily / hourly tables
→ DAX for dynamic AQI colours and status messages
→ A glass-style UI design

Biggest learning: most of the effort is in shaping API data, not building charts.


https://github.com/user-attachments/assets/d976672c-3f03-4c4d-a379-d068704496eb

