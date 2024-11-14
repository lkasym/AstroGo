

<h1 align="center">✨ AstroGo: Your AI-Powered Astrology Companion ✨</h1>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/Platform-React%20Native%20|%20Flask-green" alt="Platform">
  <img src="https://img.shields.io/badge/Language-JavaScript%20|%20Python-yellow" alt="Languages">
  <img src="https://img.shields.io/badge/OpenAI-GPT--4o-purple" alt="OpenAI">
  <br><br>
  <strong><em>Bringing ancient astrological wisdom to the modern era with the power of AI.</em></strong>
</p>

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/66814245/142984467-b7e2d3b1-13f5-4d69-b1ef-c7310a5c19a5.png" width="700" alt="AstroGo Mockup">
</p>

---

## 🌠 Key Features

- 🗣️ **AI Chatbot** - Receive instant answers to your astrology-related questions.
- 🔮 **In-Depth Chart Calculations** - From planetary positions to Dashas, get precise interpretations.
- 📍 **Location-Based Insights** - Accurate, personalized readings with OpenCage API geolocation.
- 🎨 **Elegant UI** - Smooth, responsive design with React Native for an engaging experience.
- 🚀 **Optimized Backend** - High-performance processing with Flask for real-time astrological data.

---

## 🛠️ Tech Stack

| **Component**       | **Technology**                              |
|---------------------|---------------------------------------------|
| 🌐 **Frontend**     | React Native, Expo Router                   |
| 🧑‍💻 **Backend**    | Flask, Python, OpenAI API                   |
| 🌍 **Geolocation**  | OpenCage API                                |
| 🔭 **Astrology**    | swisseph, Custom Astrology Scripts          |

---

## 📂 Project Structure

```plaintext
AstroGo/
├── backend/                    
│   ├── app.py                  # Main Flask API code
│   ├── models/                 # Model storage
│   └── utils/                  # Helper scripts
├── frontend/                   
│   ├── App.js                  # Main React Native app entry
│   ├── components/             # UI components
│   └── screens/                # Screens and views
├── dataset/                    
│   └── astro_data.json         # Custom dataset of astrology knowledge
└── requirements.txt            # Python dependencies
```

---

## 📚 Libraries Used

AstroGo is powered by a carefully curated set of libraries for precise astrological calculations, seamless frontend experience, and backend efficiency.

| Purpose                          | Library                                                |
| -------------------------------- | ------------------------------------------------------ |
| **Astrological Calculations**    | `swisseph`                                             |
| **Geolocation**                  | `OpenCageGeocode`                                      |
| **Time Management**              | `datetime`, `timedelta`, `pytz`                        |
| **Caching Optimization**         | `functools` (LRU Cache)                                |
| **Backend Framework**            | `Flask`, `Flask-CORS`                                  |
| **Astrology Calculations Script**| `kundali_calculations.py`                              |
| **AI Model Interaction**         | `openai`                                               |
| **React Native UI Components**   | `react-native`, `react-native-paper`                   |
| **Navigation**                   | `expo-router`                                          |

---

## 🌟 Features and Workflow

AstroGo uses a seamless combination of advanced AI and traditional astrology calculations to bring users an elevated astrological experience.

1. **Data Processing**:
   - Calculates planetary positions, Lagna, and houses for comprehensive astrological insights.
   - Considers each planet’s strength, weakness, or debilitation.
   - Calculates Mahadasha and Antardasha cycles for accurate life event forecasting.

2. **AI-Powered Chatbot**:
   - Leveraging OpenAI's fine-tuned GPT-4-turbo model to answer astrological questions based on user-specific data.

3. **Geolocation for Precision**:
   - Integrated with OpenCage API to tailor readings based on the user’s birth location, providing even more precise insights.

---

## 🧑‍💻 Installation Guide

### Prerequisites

- **Node.js** and **npm** for React Native setup
- **Python 3.x** for the backend
- **OpenAI API Key** and **OpenCage API Key**

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/lkasym/AstroGo
   cd AstroGo
   ```

2. **Backend Setup (Flask)**
   - Navigate to the `backend` directory:
     ```bash
     cd backend
     pip install -r requirements.txt
     ```
   - Add your **OpenCage API key** and **OpenAI API key** to `app.py`.
   - Start the Flask API:
     ```bash
     python app.py
     ```

3. **Frontend Setup (React Native)**
   - Go to the `frontend` directory:
     ```bash
     cd ../frontend
     npm install
     ```
   - Run the app:
     ```bash
     npm start
     ```

4. **Connecting Backend and Frontend**
   - Make sure the backend is running on `http://localhost:5000`. Update the API URL in the frontend code if necessary.

---

## 📚 Data Sources

AstroGo’s model has been trained and refined using reliable astrological sources, ensuring a depth and accuracy in predictions that users can trust.

- [Saptarishis Astrology Articles](https://saptarishisastrology.com/category/articles/)
- [Brihat Parashara Hora Shastra (English)](https://archive.org/details/BPHSEnglish)
- [Phaladeepika (2nd Edition, 1950)](https://archive.org/details/Phaladeepika2ndEd.1950ByVSubrahmanyaSastri)

---

## 🤖 AI Model Training

AstroGo’s chatbot is fine-tuned with **OpenAI GPT-4-turbo** on a dataset of astrological wisdom, making it highly accurate and responsive to user queries.

---



<p align="center">
  <strong>✨ Thank you for exploring AstroGo! ✨</strong><br>
  Your support means the stars to us! If you have feedback or suggestions, please reach out or contribute via <a href="https://github.com/lkasym/AstroGo">GitHub</a>.
</p>

