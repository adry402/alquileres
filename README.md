Predict Buenos Aires Rent – README
Welcome! This repository contains everything you need to train, evaluate and use a machine‑learning model that predicts monthly apartment rents in the City of Buenos Aires (CABA).
The project is designed to be reproducible from scratch and easy to adapt to new data or modeling approaches.
Data Sources
Dataset	URL / Reference	Refresh	Notes
Properati public listings	https://data.properati.com.ar	Monthly	Raw CSV includes price, m², rooms, lat/lon, barrio

Feature Set
Category	Variables (examples)
Core	rooms, bedrooms, bathrooms, surface_total_m2, surface_covered_m2
Location	neighborhood (categorical), comuna, distance to Subte stop, distance to green area
Property Type	property_type (apartment, PH, house, studio)
Building Age & Floor	floor, building_age_yr, has_elevator
Amenities	balcony, parking_spot, pet_friendly, laundry_in_building
Macro‑economics (optional)	year, month, cpi_index
