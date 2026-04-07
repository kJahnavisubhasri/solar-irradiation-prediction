# Solar Irradiance Prediction System

## Project Overview
The Solar Irradiance Prediction System is a web-based application designed to simulate the forecasting of solar radiation using meteorological parameters. The system provides an interactive interface where users can select a geographic location, choose an area within the city, and specify a time to generate an estimated solar irradiance value.

The project demonstrates how renewable energy forecasting systems can assist in solar power planning and energy management. The interface simulates atmospheric data processing and displays predicted solar irradiance along with environmental parameters.

---

## Objectives

- To simulate solar irradiance prediction using meteorological variables.
- To demonstrate a user-friendly forecasting interface.
- To show how solar energy output varies with time of day and atmospheric conditions.
- To provide a conceptual model for renewable energy prediction systems.

---

## Features

- Interactive web interface for solar forecasting
- Location-based prediction simulation
- Area selection within cities
- Time-based irradiance estimation
- Simulated atmospheric parameters
- Step-by-step prediction process display
- Result visualization with environmental metrics

---

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Programming Concepts
- DOM Manipulation
- Asynchronous JavaScript
- Dynamic Page Navigation
- Data Simulation Techniques

---

## System Workflow

1. User opens the application.
2. User selects a location from the available cities.
3. User selects a specific area within the city.
4. User inputs a time for prediction.
5. The system simulates meteorological data.
6. The prediction engine estimates solar irradiance.
7. The final prediction and environmental data are displayed.

---

## Meteorological Parameters Used

The system simulates the following atmospheric variables:

- Temperature
- Humidity
- Atmospheric Pressure
- Time of Day

These parameters influence the solar irradiance reaching photovoltaic systems.

---

## Prediction Logic

The predicted solar irradiance is determined using time-based ranges that represent natural solar radiation patterns during the day.

| Time Range | Irradiance Range |
|------------|-----------------|
| 6 AM – 9 AM | 200 – 450 W/m² |
| 9 AM – 12 PM | 500 – 750 W/m² |
| 12 PM – 3 PM | 750 – 1000 W/m² |
| 3 PM – 5 PM | 400 – 650 W/m² |
| 5 PM – 6 PM | 200 – 350 W/m² |
| Night | 10 – 60 W/m² |

---

## Project Structure
project-folder
│
├── index.html # Main application interface
├── styles (internal CSS)
├── JavaScript logic
│
└── README.md # Project documentation


---

## Pages in the Application

### Home Page
Entry point of the system containing project title and navigation options.

### About Page
Displays project team member information.

### Location Selection Page
Allows users to select cities for solar prediction.

### Prediction Page
Users input:
- Area
- Time

The system processes the inputs and generates prediction data.

### Result Page
Displays:
- Location
- Area
- Predicted Solar Irradiance
- Temperature
- Humidity
- Pressure

---

## Limitations

The current implementation uses simulated atmospheric data rather than real meteorological datasets. The prediction algorithm is based on time-dependent ranges rather than machine learning models.

---

## Possible Future Enhancements

- Integration with real weather APIs
- Machine learning models such as Random Forest or LSTM
- Real-time solar irradiance forecasting
- Historical weather dataset integration
- Graphical visualization of solar trends
- Backend server integration using Python or Node.js

---

## Applications

- Solar power generation planning
- Smart grid energy management
- Renewable energy forecasting research
- Educational demonstrations of solar prediction systems

---

## Conclusion

The system demonstrates a simplified approach to solar irradiance forecasting through an interactive web interface. While the current implementation uses simulated data, the design reflects the workflow of modern renewable energy forecasting platforms and provides a foundation for integrating real AI-based prediction models in the future.

