 Weather Recognition System using Python and CLAHE

 Project Overview
The Weather Recognition System is a Python-based application designed to identify and classify weather conditions based on user input or predefined weather features. The project demonstrates the application of rule-based logic and basic decision-making techniques to determine weather states such as sunny, rainy, cloudy, or foggy.

 Objectives
- To classify weather conditions using predefined rules
- To simulate a simple weather recognition system
- To understand decision-making logic in AI-based systems
- To build a structured and extensible Python project

 Technologies Used
- Python
- Rule-based logic
- CSV-based sample dataset
- Basic data processing techniques



System Architecture
User Input
   │
   ▼
Input Processing Module
   │
   ▼
Weather Feature Analysis
   │
   ▼
Rule-Based Classification Engine
   │
   ▼
Weather Condition Output

 Working Principle
1. The user provides weather-related inputs such as temperature, humidity, wind condition, or descriptive keywords.
2. The system processes and normalizes the input values.
3. Predefined rules are applied to match input features with known weather patterns.
4. The most suitable weather condition is selected.
5. The system displays the identified weather condition.

 Dataset Information
- The project uses a sample image dataset for demonstration.
- Dataset format: .png files 

 Sample Dataset Structure
| Weather Condition | Temperature | Humidity | Wind   |
| -- | -- | -- |  |
| Sunny             | High        | Low      | Mild   |
| Rainy             | Moderate    | High     | Strong |
| Cloudy            | Moderate    | Medium   | Mild   |
| Foggy             | Low         | High     | Low    |


 How to Run the Project
1. Clone the repository
git clone https://github.com/your-username/weather-recognition-system.git
cd weather-recognition-system
2. Run the Python script
python weather_recognition.py

 Key Features
- Simple and interpretable rule-based system
- Easy to understand project structure
- Suitable for beginners in AI and Python
- Extendable for machine learning or computer vision approaches

 Future Enhancements
- Integration of real-time weather APIs
- Machine learning–based weather classification
- Image-based weather recognition
- Web or mobile-based interface
- Time-series weather prediction


Author
Niharika Kulkarni


**Disclaimer**
This project is developed strictly for educational purposes.
It should not be used for real-world weather forecasting or safety-critical applications.
