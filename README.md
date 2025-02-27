# War-Maps :  Historic Battles Interactive Map in Power BI


## Overview
This Power BI project visualizes historic battles across different continents using an **interactive map**. The dataset includes **battle names, locations (latitude & longitude), and casualties**, with bubbles on the map representing each battle's location.

### **Features**
- **Hover Functionality**: Displays battle name, latitude, longitude, and casualty count when hovering over a bubble.
- **Bubble Size Representation**: Larger bubbles indicate battles with higher casualties.
- **Accurate Geolocation**: Latitude and longitude ensure precise placement of battles on the map.

## **Data Fields Used**
- **Battle Name**: The name of the historic battle.
- **Latitude & Longitude**: Geographic coordinates for accurate map placement.
- **Casualties**: The estimated number of casualties in the battle (used to scale bubble size).

## **Steps to Recreate in Power BI**
1. **Load Dataset**: Import the Excel file into Power BI.
2. **Create a Map Visual**: Select a **Map** or **Filled Map** visual.
3. **Add Data Fields**:
   - **Latitude Field** - Latitude
   - **Longitude Field** - Longitude
   - **Bubble Size** - Casualties (to scale bubble size)
4. **Adjust Formatting**:
   - Ensure Latitude & Longitude are set to **Don’t Summarize**.
   - Adjust bubble transparency & size scaling if needed. well I didn't need to 
5. **Test Hover Effect**: Confirm that battle details appear when hovering over bubbles.

## **Troubleshooting**
- **Bubbles Overlapping**: Check if Power BI is rounding coordinates; increase decimal places if needed.
- **Missing Data**: Ensure all necessary fields are added to the tooltip.
- **Incorrect Locations**: Verify latitude and longitude values in the dataset.

## **Future Enhancements**
- Add **battle descriptions** for more historical context.
- Include **date filters** to visualize battles over time.
- Integrate additional statistics like **commanders involved** or **winning side**.


**Tools Used:** Power BI, Excel  
**Dataset Source:** Custom-created for this project

