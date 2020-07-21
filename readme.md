# DC Rat Map
## Version 0.1

- [Goals](#goals)
- [Description](#description)
- [Measuring_Progress](#measuring_progress)
- [Acknowledgements](#acknowledgements)

## Goals

- Build a database of rodent inspection and treatment in D.C. 
- Produce a heat map, using some opensource/public/free map library
- Integrate tools to take screenshots, track past events and hold authorities accountable. 

## Description 

This project makes use of DC's Rodent Inspection and Treatment in Last 30 Days dataset, which can be found here: https://opendata.dc.gov/datasets/rodent-inspection-and-treatment-in-last-30-days. 

It creates a map using Mapbox (https://www.mapbox.com) and assigns points to geospatial coordinates in the earlier saved datasets. The data is downloaded in CSV format, cleaned and then converted to GeoJSON for easier use of Mapbox's JS/Web libraries. 

The site should also eventually have a suite of tools to accompany the dataset, to faciliate communication with local officials and encourage civic engagement around rodents. 

Once a month, someone needs to pull the data, update the database and ensure the visuals are updated. Currently, this is done by Paul-Emmanuel, though there are plans to use the API instead. 

## Measuring_Progress

To measure progress, we should track: 
- Site visits and traffic data.
- Usage statistics for the "Complain to authorities" button. 
- Compile optional user survey data with their thoughts on the project and website. 
