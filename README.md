# Geospatial Analysis of Crimes in San Francisco (2016)

This project involves a geospatial analysis of crime incidents that occurred in San Francisco during the year 2016. Using a dataset from the San Francisco Police Department (SFPD), the goal of this analysis is to visualize the geographic distribution of various crimes and gain insights into patterns of criminal activity across the city.

**Project Overview**

This analysis uses Python and various data science libraries to clean, manipulate, and visualize crime data. The key objective is to explore and map out crime incidents to identify trends and hotspots that could be useful for law enforcement and public safety planning.

**Datasets**

San Francisco Police Department Incidents for 2016:
This dataset consists of 150,500 records of police department incidents reported throughout San Francisco in 2016. Each record contains information about the crime category, description, location, date, time, police district, and resolution status.

**Key Features:**

- IncidntNum: Unique incident number
- Category: Type of crime or incident
- Descript: Detailed description of the crime or incident
- DayOfWeek: Day of the week when the incident occurred
- Date: Date of the incident
- Time: Time of the incident
- PdDistrict: Police department district where the incident was reported
- Resolution: Outcome or resolution of the incident
- Address: Location of the incident
- X (Longitude), Y (Latitude): Geographic coordinates of the crime location
- Location: Tuple of latitude and longitude values
- PdId: Police department ID

**Tools and Libraries**

- Pandas: Used for data wrangling and manipulation.
- NumPy: Utilized for numerical operations and calculations.
- Folium: The primary library used for geospatial data visualization and mapping.

**Data Preparation**

- Data Loading: The dataset was loaded into a pandas DataFrame directly from a CSV file.
- Data Inspection: An initial inspection of the first five records was conducted to understand the structure and content of the data.
- Data Reduction: To simplify the analysis and reduce computational load, the dataset was trimmed to include only the first 500 incidents.
- Geospatial Visualization: The latitude and longitude values were used to map the crime incidents across San Francisco using Folium.

**Visualization**

- San Francisco Crime Map: A map was created using Folium, centered on San Francisco with a zoom level of 12. Crime incidents were plotted on the map using circle markers, with colors indicating different crime categories.
- Circle Markers: Each crime incident is represented by a circle marker, with the size and color of the marker providing additional information about the incident.
  
**Results**

The visualization provides a clear geographic representation of where crimes occurred in San Francisco during 2016, highlighting areas with high concentrations of criminal activity. This can help in identifying crime hotspots and patterns over the city, which could be useful for resource allocation by law enforcement agencies.

**Conclusion**

This project demonstrates the power of geospatial analysis in understanding crime patterns. By visualizing the geographic distribution of crimes, one can gain valuable insights into public safety and urban planning. The tools and techniques used in this analysis can be applied to other geospatial datasets for similar investigations.
