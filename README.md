# 🌬️ Wind Turbine Fault Detection Platform
An End-to-End Machine Learning Solution for Predictive Maintenance
Built for the Data Science & Engineering Community

## 📖 Abstract
The Wind Turbine Fault Detection Platform is a full-stack, real-time web application engineered to facilitate rigorous monitoring and analysis of wind turbine health. Moving away from manual inspections, this platform introduces an automated prediction system augmented by Machine Learning. The system autonomously processes sensor data, predicts fault classifications using XGBoost, and detects anomalies using DBSCAN clustering to ensure operational efficiency.

## 🌐 Live Demo
https://wind-turbine-fault-detection.onrender.com/login

### 1. 🧠 AI-Powered Automation
- **Predictive Analytics:** An advanced XGBoost classifier automatically evaluates turbine sensor readings to categorize operational risk levels and predict potential faults.
- **Anomaly Detection:** Utilizes DBSCAN (Density-Based Spatial Clustering of Applications with Noise) to identify outlier data points and unusual behavior in turbine sensors autonomously.
- **Smart Feedback:** Generates immediate, data-driven feedback and detailed analysis logs for each dataset uploaded to enhance maintenance strategies.

### 2. 🏛️ Structured Data Processing
- **Dataset Library:** Seamlessly run analyses on pre-generated, simulated sensor data directly from the integrated dataset library.
- **Custom Uploads:** Engineers can easily upload custom `.csv` data files containing live turbine metrics for immediate ML pipeline processing.
- **Historical Tracking:** All past predictions, including accuracy metrics and anomaly counts, are securely stored and accessible via an interactive history dashboard.

### 3. 📊 Real-Time Interaction & Analytics
- **Interactive Dashboards:** Real-time data visualization of the ML model's output immediately after processing.
- **Actionable Insights:** Provides clear, quantifiable results such as model accuracy percentages and the exact number of anomalies detected per batch.

### 4. 🛡️ User Authentication & Control
- **Secure Access:** Built-in user registration, login, and secure password management powered by an SQLite database.
- **Personalized Experience:** Tracks user sessions and provides a tailored interface for authenticated engineers and administrators.

### Prerequisites
- [Python](https://www.python.org/) (v3.8 or higher)
- [pip](https://pip.pypa.io/en/stable/) (Python Package Installer)

### Steps to Run Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ankit-kesarwani-2006/Wind-Turbine-Fault-Detection.git
   cd Wind-Turbine-Fault-Detection
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application:**
   ```bash
   python app.py
   ```
   The server will start on `http://127.0.0.1:5000`.

## 📸 System Interface
- **Home/Dashboard:** Complete overview of the platform features and user actions.
- **ML Pipeline Results:** Instantaneous readouts of XGBoost and DBSCAN results.
- **History Portal:** Tabular view of all past datasets and their respective analysis outcomes.

## 👨‍💻 Project Team / Authors
This project was developed by:
- **Ankit Kesarwani**

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
