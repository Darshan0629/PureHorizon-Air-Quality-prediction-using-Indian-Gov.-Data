# PureHorizon-Air-Quality-prediction-using-Indian-Gov.-Data

## Overview
PureHorizon is a web application designed to predict air quality using data provided by the Indian Government. This project utilizes a Flask backend to process data, which is visualized on the frontend using Streamlit and Plotly.

## Features
- Real-time air quality index (AQI) predictions.
- Interactive charts and graphs to display data.
- API data retrieval from Indian Government sources.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.6 or higher installed on your machine.
- PIP for installing Python packages.

## Installation
To install PureHorizon, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PureHorizon-Air-Quality.git
   cd PureHorizon-Air-Quality
   ```

2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Application
To run PureHorizon, use the following command:

- For Flask backend:
  ```bash
  flask run
  ```

- For Streamlit frontend:
  ```bash
  streamlit run your_streamlit_app.py
  ```

Make sure to replace `your_streamlit_app.py` with the path to your main Streamlit application file.

## Data Source
This project uses air quality data provided by the Indian Government. The data is regularly updated and publicly accessible, ensuring that the application provides real-time and accurate predictions.
Link: https://data.gov.in/resource/real-time-air-quality-index-various-locations

## Contributing
Contributions to PureHorizon are welcome! If you have suggestions or improvements, please fork the repository and create a pull request, or open an issue with the tag "enhancement".

## License
This project is licensed under the [MIT License]
