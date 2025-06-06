# Water Quality Prediction using IoT and Machine Learning
-This project implements a real-time smart water quality monitoring system using the ESP32 microcontroller, cloud services, and an embedded machine learning model.

🛠️ Key Features
Sensor Integration: Measures four key water quality parameters:
-pH
-Turbidity
-Temperature
-TDS (Total Dissolved Solids)

Edge Processing: The ESP32 microcontroller collects and processes sensor data in real-time.
Cloud Sync: Data is uploaded to a Firebase real-time database for storage and further processing.
Embedded ML Model: A TensorFlow Lite model runs on the platform, analyzing sensor data to predict whether the water is safe or unsafe.
Visual Dashboard: Real-time dashboards display visual analytics of all parameters and prediction outcomes.

AI-Powered Explanations: If water is predicted unsafe, the system provides scientific context based on threshold limits for each parameter.

✅ Tech Stack
Hardware: ESP32, pH sensor, Turbidity sensor, Temperature sensor, TDS sensor
Software: Arduino IDE, Firebase, TensorFlow Lite, Web dashboard (possibly with HTML/JS)

🧠 ML Component
-Trained on historical water quality data.
-Deployed using TensorFlow.
-Model predicts binary outcome: Safe / Unsafe.

📊 Dashboard
-Real-time data charts for each parameter.
-Prediction status displayed.
-Alerts and explanations for unsafe water quality.

# Team:
-Hrudhay Devoju
-Santosh Keshetty
