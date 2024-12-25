# Smart Community Dashboard

This project simulates a smart community dashboard to monitor sensor data, build ML models, and provide insights.

## Features
- Data ingestion and processing from simulated IoT sensors.
- Machine learning for anomaly detection and forecasting.
- Interactive dashboard for visualizing insights.

## Installation
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the scripts in the following order:
   - `data_pipeline.py`
   - `ml_modeling.py`
   - `api_server.py`
   - `dashboard.py`

## Usage
- Access the dashboard at `http://127.0.0.1:8050`
- API endpoint for data: `http://127.0.0.1:5000/get-data`

## License
MIT
