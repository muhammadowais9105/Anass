# 🧠 UtilityHub

UtilityHub is a modular, dark-themed Python web application built with **Streamlit**.  
It combines multiple everyday tools into a single dashboard while following a **component-based architecture**, making the project scalable, clean, and easy to extend.

This project focuses on writing practical software with real-world usability and structured design.

---

## ✨ Features

- 🌦 **Live Weather App**  
  Real-time weather data powered by the OpenWeatherMap API.

- 📊 **BMI Calculator**  
  Instantly calculates BMI with health category feedback.

- 🔐 **Password Generator**  
  Generates strong, secure passwords with user-controlled options.

- 💸 **Expense Tracker**  
  Tracks daily expenses using session-based state handling.

- 📐 **Unit Converter**  
  Converts values across length, weight, and temperature.

- 🌙 **Dark-First Interface**  
  Permanent dark mode for better readability and eye comfort.

---

## 🧩 Project Architecture

The app is designed with modular separation, where each feature works as an independent component:

```text
UtilityHub/
├── main.py              # App entry point & navigation
├── modules/             # Individual feature modules
│   ├── weather.py
│   ├── bmi.py
│   └── utilities.py
├── .streamlit/
│   ├── config.toml      # UI theme configuration
│   └── secrets.toml     # API keys (ignored in Git)
├── requirements.txt
└── .gitignore
## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/multi-utility-suit.git
cd multi-utility-suit


