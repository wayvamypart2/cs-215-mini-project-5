---

# Mini Project 5: Working with Geospatial Data

Name: Amelia Pucek

Date: 04/27/2026

Course: CS-215

## Overview

This project analyzes GPS movement data from Professor Wirfs-Brock’s visit in March 2022. The goal is to understand spatial movement patterns using geospatial distance calculations and interactive visualization.

---

## Key Methods

- Haversine distance calculations to measure geographic distance
- Identification of closest and farthest points from Brasserie Four (Walla Walla)
- Interactive Plotly maps to visualize movement over time
- Geospatial clustering using rounded latitude/longitude values

---

## Part 1A: Distance Analysis

A reference location (Brasserie Four in Walla Walla, WA) was selected and distances were computed for all GPS points.

### Key Results:
- Closest point: ~0.046 km (subject was physically at the location)
- Farthest point: ~1307 km (outside Washington state)

These results show both local presence and long-distance travel within the dataset.

---

## Part 1B: Geospatial Visualization

Interactive maps were created to explore movement patterns over time.

- Movement Map: (upload your HTML file and link it here)
- Cluster Map: (upload your HTML file and link it here)

---

## Findings

- The dataset contains both local and long-distance movement
- 11 geographic clusters were identified based on rounded coordinates
- Movement is concentrated in distinct regions rather than continuous paths

---

## Conclusion

The analysis reveals structured geographic movement patterns, with clear separation between regional clusters and travel events.

# Mini Project 5: Working with Geospatial Data

**Amelia Pucek**  
CS-215 | April 27, 2026  

---

## Overview

This project analyzes GPS movement data from Professor Wirfs-Brock’s visit in March 2022.  
Using geospatial techniques, I explored how her movement varied over time and space.

The analysis includes:
- Distance calculations using the Haversine formula  
- Identification of closest and farthest points from Brasserie Four (Walla Walla)  
- Interactive Plotly maps  
- Geospatial clustering to identify movement regions  

---

## Part 1A: Distance Analysis

I used Brasserie Four in Walla Walla as a reference location and computed distances from all GPS points.

### Key Results:
- Closest point: ~0.046 km (subject was physically at Brasserie Four)
- Farthest point: ~1307 km (outside Washington state)

These results show both local presence and long-distance travel.

---

## Part 1B: Movement Visualization

The dataset was visualized using interactive Plotly maps to show spatial movement patterns over time.

[Open Movement Map](movement_map.html)

---

## Geospatial Clustering

To better understand movement structure, I grouped GPS coordinates into geographic clusters based on rounded latitude and longitude values.

The analysis revealed:
- 11 distinct clusters
- A major concentration around ~39.7–39.8 latitude and -105 longitude (Denver region)
- A smaller cluster in Walla Walla

[Open Cluster Map](cluster_map.html)

---

## Conclusion

The data shows structured movement patterns with clear geographic separation between regions rather than continuous travel.
