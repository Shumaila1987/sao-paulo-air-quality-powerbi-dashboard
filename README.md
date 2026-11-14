# sao-paulo-air-quality-powerbi-dashboard
São Paulo Air Quality Monitoring — Interactive Map
 
An interactive dashboard built in Power BI that maps PM2.5 readings from the official air quality monitoring network across São Paulo state, Brazil.
 
## Project Overview
 
Air quality data is often published as raw spreadsheets — difficult to interpret and hard to visualise geographically. This project takes real sensor data and station locations, combines them, and presents the information as an interactive map that anyone can explore.
 
I built this to practice working with geospatial data, merging separate datasets, and turning raw readings into something visually clear and useful.
 
## Features
 
  Interactive map — Shows all 30+ monitoring stations across São Paulo state
​
  Station selector — Pick any station from the list and the map automatically zooms to that exact location
​
  Details on hover — Move your cursor over any dot to see the station name and its PM2.5 reading
​
  Navigation controls — Zoom buttons for easier viewing; map labels for reference
​
  Clean design — Road-map style background so the focus stays on the data

  ## 📂 Data Sources

| Dataset | Contents |
|---|---|
| **Station Coordinates** | Station names, latitude, and longitude for every monitoring point |
| **Sensor Readings** | Time‑series air‑quality measurements including PM2.5, NO₂, O₃, CO, and more |

Both datasets come from the official São Paulo state air quality monitoring network. I cleaned and prepared them separately before linking them together in Power BI — the coordinates tell the map where to place each marker, and the sensor data provides the readings shown in the tooltips.

## What I Did
 
1. Prepared the data — Checked both files for consistency, made sure station names matched between datasets, and removed any duplicates or incomplete entries
​
2. Built the model — Connected the station list with the sensor readings using the station name as the common key
​
3. Created the map — Used latitude and longitude from the coordinates table to place each station correctly
​
4. Added interactivity — Set up the station list as a slicer so users can jump directly to specific locations
​
5. Configured tooltips — Added PM2.5 values so the latest reading appears when hovering over each station
​
6. Finalised the layout — Added a clear title, page label, and adjusted map settings for readability
 
 
 
## What I Learned
 
- How to design around two related but different datasets — one for locations, one for measurements
​
- Why it's important to keep reference data (like station coordinates) clean and separate from time-series readings
​
- How to make dashboards more useful: filters that zoom automatically and tooltips that show exactly what people need to know
​
- Small design choices matter — consistent naming, clear titles, and not cluttering the view make a big difference

  ## Files in This Repository

| File |	Description |
|---|---|
| **Air_quailty_Monitoring_Map_SaoPaulo.pbix** | The full Power BI project file |
| **README.md** | This project overview |
| **sao-paulo-air-quality-pm25-powerbi-dashboard.png** | Screenshort of the Dashboard |

This project overview
Preview image of the map dashboard
Thanks for stopping by! If you have any questions or spot something that could be improved, feel free to reach out. 😊

##  Credits
Project designed and built by **Shumaila**

Connect with me on [LinkedIn](
www.linkedin.com/in/shumaila-liaqat) or view more of my portfolio!
www.shumailaliaqat
