# Well Head Protection Area Project

## 📖 Overview
This project involves calculating the **Well Head Protection Area** using **Capture Zone Analysis**. The analysis focuses on understanding the area of influence around a specific well based on groundwater flow, transmissivity, and pumping rates. Find the video here : https://youtu.be/4bZZsDr-Uls

The project outputs:
- A **capture zone polygon** for the selected well.
- An overlay visualization of the capture zone on the Jefferson County map.

## 🎯 Well Selection
During a class exercise, we were asked to choose a well IDs for analysis. I selected **Well ID: 6424502** (it was the very last well ID in the dataset).
## 📋 Steps Performed
1. **Data Preparation**:
   - Load spatial data for wells and Jefferson County.
   - Reproject data to **EPSG:6350** for accurate calculations.
2. **Well Selection**:
   - Select **Well ID: 6424502** from the dataset.
3. **Capture Zone Calculation**:
   - Calculate the stagnation point, maximum capture zone width, and boundary equation.
   - Rotate coordinates to align with groundwater flow direction.
4. **Visualization**:
   - Overlay the capture zone polygon on the Jefferson County map.
   - Highlight the well location and stagnation point.
5. **Export**:
   - Save the capture zone polygon to a GeoPackage file.
