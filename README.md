# 🌾 AgriTech AI: Intelligent Farming Ecosystem

AgriTech AI is a comprehensive, data-driven agricultural decision-support system. It leverages Machine Learning, Real-Time Weather APIs, and secure database management to empower farmers with actionable insights.

## 🚀 Key Features

* **AI Command Center:** A unified dashboard for soil health monitoring and system diagnostics.
* **Precision Crop Prediction:** Uses a Random Forest Classifier to recommend the most suitable crop based on N-P-K levels, pH, and environmental factors.
* **Digital Soil Health Card:** Generates and exports official PDF reports for record-keeping and government subsidies.
* **Live Weather Intelligence:** Real-time 4-day forecasts tailored to the farmer's specific location.
* **Investment Prediction:** AI-driven financial forecasting to estimate farming costs based on acreage and soil quality.
* **Secure Authentication:** Multi-user support with hashed password security and role-based access.

## 🛠️ Technology Stack

* **Frontend:** Streamlit (Glassmorphism UI)
* **Language:** Python 3.x
* **Machine Learning:** Scikit-Learn (Random Forest, Linear Regression)
* **Database:** SQLite3 (Encrypted & Secure)
* **Reporting:** FPDF Engine
* **Visualization:** Plotly Interactive Charts

## 📂 Project Structure

The project follows a **Modular Architecture** for scalability and clean code management:
```text
AgriTech_AI/
├── main.py                    # Application Entry Point
├── Modules/                   # Core Logic
│   ├── auth_manager.py        # Security & Login
│   ├── database.py            # SQLite CRUD Operations
│   ├── report_generator.py    # PDF Generation Logic
│   ├── weather_service.py     # API Integrations
│   └── price_engine.py        # Financial AI Logic
├── Intelligence_Pages/        # Dashboard Components
│   ├── regional_intelligence.py
│   └── weather_intelligence.py
├── Models/                    # Pre-trained AI Models
│   ├── my_crop_model.pkl      # Crop Prediction Model
│   └── price_model.pkl        # Cost Estimation Model
└── requirements.txt           # Dependency List

