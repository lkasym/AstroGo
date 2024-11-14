# 🌌 AstroGo 🌌

![License](https://img.shields.io/badge/license-MIT-blue) ![Platform](https://img.shields.io/badge/platform-React%20Native%20|%20Flask-green) ![OpenAI API](https://img.shields.io/badge/OpenAI-GPT--4o-purple)

AstroGo is a personalized astrology app that delivers insightful and interactive horoscopes using a custom AI chatbot fine-tuned on classical astrology texts. Our application combines astrological wisdom with the latest in AI technology to provide users with tailored readings.

---

## 🌟 Features

- 🗣️ **Interactive AI Chatbot** - Ask astrology-related questions and receive personalized readings.
- 🔮 **Advanced Astrology Calculations** - Planetary positions, houses, and Dashas for insightful analyses.
- 📍 **Location-Based Insights** - Integrated with OpenCage API for precise location-based readings.
- 🎨 **Intuitive Frontend** - Responsive design built in React Native.
- 🚀 **Optimized Backend** - Flask API with high-performance data processing.

---

## 📂 Project Structure
```plaintext
AstroGo/
├── backend/
│   ├── app.py              # Flask API backend code
│   ├── models/             # Directory for saved model files
│   └── utils/              # Helper scripts for data processing
├── frontend/
│   ├── App.js              # Main React Native application file
│   ├── components/         # React Native components
│   └── screens/            # Screens and views for the app
├── dataset/
│   └── astro_data.json     # Custom curated dataset
├── README.md               # Project README file
└── requirements.txt        # Backend dependencies
```

---

## ⚙️ Tech Stack

- **Frontend**: [React Native](https://reactnative.dev/)
- **Backend**: [Flask](https://flask.palletsprojects.com/), Python
- **AI Model**: [OpenAI GPT-4-turbo](https://platform.openai.com/), fine-tuned on custom dataset
- **Geolocation**: [OpenCage API](https://opencagedata.com/)

---

## 🚀 Setup and Installation

### Prerequisites
- **Node.js** and **npm** for React Native
- **Python 3.x**
- **OpenAI API key** and **OpenCage API key**

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/lkasym/AstroGo
   cd AstroGo
   ```

2. **Backend Setup (Flask API)**
   ```bash
   cd backend
   pip install -r requirements.txt
   ```
   - Insert your OpenCage API key into `app.py`.
   - Run the Flask API:
     ```bash
     python app.py
     ```

3. **Frontend Setup (React Native)**
   ```bash
   cd ../frontend
   npm install
   ```
   - Start the app:
     ```bash
     npm start
     ```

4. **Connect Backend and Frontend**
   - Make sure the backend is running on `http://localhost:5000` or update the API URL in the frontend if different.

---

## 🔧 Data Processing

AstroGo performs extensive data processing to create a detailed horoscope, including:
- **Planetary Positions**: Calculates each planet’s position in the horoscope.
- **Lagna (Ascendant)**: Determines the first house in the chart.
- **House Effects**: Analyzes houses influenced by planets, along with malefic/benefic effects.
- **Planet Strength**: Evaluates if a planet is strong, weak, neutral, or debilitated.
- **Mahadasha and Antardasha**: Tracks major and sub-periods for predicting life events.

---

## 📚 Data Sources

AstroGo’s custom dataset is curated from trusted astrological sources, including:
- [Saptarishis Astrology Articles](https://saptarishisastrology.com/category/articles/)
- [Brihat Parashara Hora Shastra (English)](https://archive.org/details/BPHSEnglish)
- [Phaladeepika (2nd Edition, 1950)](https://archive.org/details/Phaladeepika2ndEd.1950ByVSubrahmanyaSastri)

---

## 🤖 Model Training

The dataset was fine-tuned using **OpenAI’s GPT-4-turbo**, which powers the app's AI chatbot, allowing it to generate accurate and meaningful astrology predictions.

---


### ✨ Thank you for exploring AstroGo! ✨

For any questions or suggestions, feel free to reach out or open an issue in the [GitHub repository](https://github.com/lkasym/AstroGo).

