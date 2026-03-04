# Fi-Res : Forest Fire Detection and Alert System
Fi-Res is an advanced forest fire detection and alert system that utilizes satellite imagery deep learning and machine learning to detect active wildfires and identify fire-prone areas and detect active wildfires. The system provides real-time alerts to rescue squads, wildlife officers, and community heads, ensuring a quick response to mitigate damage. Additionally, Fi-Res features an AI-powered chatbot that enables users to retrieve information about wildfires, safety measures, and contact details of firefighters, enhancing preparedness and response efforts.

## Overview
Fi-Res is designed to provide a comprehensive solution for forest fire detection and alerting. The system consists of the following components:
* **Satellite Image Analysis**: Detects wildfires from live satellite imagery using deep learning image recognition models.
* **Real-time Alerts**: Sends instant notifications via Telegram bot to concerned authorities.
* **Live Dashboard**: Displays live satellite images of affected areas, severity stats, environmental conditions such as temperature, humidity, and wind speed and historical data.
* **High-risk Area Prediction**: Highlights high-risk areas by prediction from live environmental data with the help of machine learning.
* **Data Visualization**: Provides charts and statistics on fire severity, spread patterns, and historical data.

## Features
* **Satellite Image Analysis**: Detects wildfires from live satellite imagery using deep learning image recognition models.
* **Real-time Alerts**: Sends instant notifications via Telegram bot to concerned authorities.
* **Live Dashboard**: Displays live satellite images of affected areas, severity stats, environmental conditions such as temperature, humidity, and wind speed and historical data.
* **High-risk Area Prediction**: Highlights high-risk areas by prediction from live environmental data with the help of machine learning.
* **Data Visualization**: Provides charts and statistics on fire severity, spread patterns, and historical data.

## Technologies Used
* **Frontend**: StreamLit
* **Backend**: Python
* **Deep Learning**: Image recognition models trained on satellite imagery
* **Machine Learning**: Prediction of high-risk areas from environmental data
* **Alert System**: Telegram Bot API for real-time notifications

## Prerequisites
* Python 3.8 or higher
* StreamLit
* TensorFlow
* Keras
* OpenCV
* NumPy
* Pandas
* Scikit-learn
* Telegram Bot API

## Installation
1. Clone the repository: `git clone https://github.com/your-username/your-repo-name.git`
2. Install the required packages: `pip install -r requirements.txt`
3. Set up the Telegram Bot API: Create a Telegram bot and obtain the API token.
4. Replace the `bot_token` variable in `alertbot.py` with your API token.

## Usage
1. Run the application: `streamlit run Home.py`
2. Open the web browser and navigate to `http://localhost:8501`
3. Interact with the live dashboard to view satellite images, severity stats, and environmental conditions.
4. Use the chatbot to retrieve information about wildfires, safety measures, and contact details of firefighters.

## API Documentation
The API documentation is available in the `api` directory.

## Testing
The testing framework is available in the `tests` directory.

## Deployment
The deployment instructions are available in the `deployment` directory.

## Contributing
Contributions are welcome! Please submit a pull request with your changes.

## License
Fi-Res is licensed under the MIT License. See `LICENSE` for details.