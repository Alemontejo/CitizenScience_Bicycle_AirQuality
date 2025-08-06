# Bicycle Mobility & PM₂.₅ Study — Citizen Science Bicycle Air Quality

This notebook performs a complete analysis of PM₂.₅ measurements collected by bicycle-mounted sensors as part of SIATA’s citizen science program in Medellín, Colombia.  

**Key Innovations in This Analysis:**
- **Trip validation** using time gaps, GPS filtering, and displacement thresholds.
- **Distance calculation** for each trip segment and cumulative kilometers traveled.
- **Automatic segmentation** of trips per sensor and globally.
- Integration of **air quality analysis** with mobility patterns.

---

## Figures & Results

### 1. Monthly Bicycle Trips and Active Sensors (2022–2024)
![Figure 1]([https://github.com/Alemontejo/CitizenScience_Bicycle_AirQuality/tree/main/BicycleMobility_PM25_Study](https://github.com/Alemontejo/CitizenScience_Bicycle_AirQuality/blob/main/BicycleMobility_PM25_Study/1.%20Monthly%20Bicycle%20Trips%20and%20Active%20Sensors%20(2022%E2%80%932024).png))
Shows the monthly total of bicycle trips and number of active sensors, revealing seasonal variations and periods of increased activity.

---

### 2. Monthly Comparison of Bicycle Trips and Active Sensors by Year
![Figure 2](https://github.com/Alemontejo/CitizenScience_Bicycle_AirQuality/blob/main/BicycleMobility_PM25_Study/2.%20Monthly%20Comparison%20of%20Bicycle%20Trips%20and%20Active%20Sensors%20by%20Year%20(2022%E2%80%932024).png)
Compares monthly trip and active sensor counts across 2022, 2023, and 2024 to detect yearly differences in activity patterns.

---

### 3. Monthly Trips-to-Active-Sensors Index (2022–2024)
![Figure 3](https://github.com/Alemontejo/CitizenScience_Bicycle_AirQuality/blob/main/BicycleMobility_PM25_Study/3.%20Monthly%20Trips-to-Active-Sensors%20Index%20(2022%E2%80%932024).png)
Normalizes bicycle usage by sensor availability, providing a comparable indicator across years regardless of the number of active sensors.

---

### 4. Daily PM₂.₅ Levels by Time of Day — October 2024
![Figure 4](https://github.com/Alemontejo/CitizenScience_Bicycle_AirQuality/blob/main/BicycleMobility_PM25_Study/4.%20Daily%20PM2.5%20Levels%20by%20Time%20of%20Day%20%E2%80%94%20October%202024.png)
Shows average daily PM₂.₅ concentrations for different time intervals, highlighting variations in air quality depending on the time of day.

---

### 5. PM₂.₅ Spatial Distribution and Measurement Density — Medellín Metropolitan Area
![Figure 5](https://github.com/Alemontejo/CitizenScience_Bicycle_AirQuality/blob/main/BicycleMobility_PM25_Study/5.%20PM2.5%20Spatial%20Distribution%20and%20Measurement%20Density%20%E2%80%94%20Medelli%CC%81n%20Metropolitan%20Area.png)
Left: DBSCAN clusters colored by average PM₂.₅ concentration.  
Right: Kernel Density Estimation (KDE) heatmap showing areas with higher measurement density.

---

### 6. Daily Active Sensors and Average — October 2024
![Figure 6](https://github.com/Alemontejo/CitizenScience_Bicycle_AirQuality/blob/main/BicycleMobility_PM25_Study/6.%20Daily%20Active%20Sensors%20and%20Average%20%E2%80%94%20October%202024.png)
Daily count of active sensors compared with the monthly average, showing fluctuations in network coverage.

---

## Data Privacy
The SQL queries and raw SIATA data used for this analysis are **not included** in the repository for confidentiality reasons.

---

