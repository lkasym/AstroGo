

<h1 align="center">🌌 AstroGo: The Future of Astrology, Powered by AI 🌌</h1>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/Platform-React%20Native%20|%20Flask-green" alt="Platform">
  <img src="https://img.shields.io/badge/Language-JavaScript%20|%20Python-yellow" alt="Languages">
  <img src="https://img.shields.io/badge/OpenAI-GPT--4o-purple" alt="OpenAI">
  <br><br>
  <strong><em>A unique blend of ancient wisdom and modern AI technology, giving you insights like never before.</em></strong>
</p>

---

## 🌠 About AstroGo

AstroGo is your personal AI-powered astrology companion. With a seamless combination of React Native and Flask, it uses advanced AI and traditional astrological calculations to deliver detailed, personalized readings. Perfect for astrology enthusiasts and anyone curious about their cosmic journey.

---

<p align="center">
  <strong>✨ App Screenshots ✨</strong>
</p>

<p align="center">
  <img src="https://github.com/lkasym/AstroGo/blob/main/Screenshot_20241113_114151_Expo%20Go.jpg" width="220" style="padding: 10px;">
  <img src="https://github.com/lkasym/AstroGo/blob/main/Screenshot_20241113_114209_Expo%20Go.jpg" width="220" style="padding: 10px;">
  
  <br>
  <img src="https://github.com/lkasym/AstroGo/blob/main/Screenshot_20241113_114226_Expo%20Go.jpg" width="220" style="padding: 10px;">
  <img src="https://github.com/lkasym/AstroGo/blob/main/Screenshot_20241113_114230_Expo%20Go.jpg" width="220" style="padding: 10px;">
</p>

---

## ✨ Key Features

- **AI Chatbot** 🤖: Powered by GPT-4-turbo, it provides real-time answers to all your astrology questions.
- **In-Depth Astrological Calculations** 🔮: Delivers insights into planetary positions, Dashas, ascendant, and more.
- **Location-Based Insights** 📍: Personalized readings based on precise geolocation with OpenCage API.
- **User-Friendly Interface** 🎨: A beautifully crafted UI with React Native for a seamless experience.
- **Optimized for Performance** 🚀: Real-time astrological data processing through a Flask API backend.

---

## 🛠️ Tech Stack

| Component       | Technology                    |
|-----------------|-------------------------------|
| 🌐 Frontend     | React Native, Expo Router     |
| 🔧 Backend      | Flask, Python, OpenAI API     |
| 🌍 Geolocation   | OpenCage API                  |
| 🔭 Astrology    | swisseph, Custom Python Scripts |

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

| Purpose                           | Library                                                |
|-----------------------------------|--------------------------------------------------------|
| **Astrological Calculations**     | `swisseph`                                             |
| **Geolocation**                   | `OpenCageGeocode`                                      |
| **Time Management**               | `datetime`, `timedelta`, `pytz`                        |
| **Caching Optimization**          | `functools` (LRU Cache)                                |
| **Backend Framework**             | `Flask`, `Flask-CORS`                                  |
| **Astrology Calculations Script** | `kundali_calculations.py`                              |
| **AI Model Interaction**          | `openai`                                               |
| **React Native UI Components**    | `react-native`, `react-native-paper`                   |
| **Navigation**                    | `expo-router`                                          |

---

## 🌟 Features and Workflow

AstroGo delivers an elevated astrology experience with the best of AI and classic Vedic calculations:

1. **Data Processing**:
   - Calculates planetary positions, Lagna, malefic/benefic influences, and Dasha cycles.
   - Determines planetary strength (strong, weak, neutral, or debilitated).

2. **AI Chatbot**:
   - Built with OpenAI’s fine-tuned GPT-4-turbo model, generating astrological insights and answering queries based on user-specific data.

3. **Geolocation for Precision**:
   - Integrates OpenCage API to refine predictions based on the user’s birth location, ensuring highly accurate readings.

---

## 🧑‍💻 Installation Guide

### Prerequisites

- **Node.js** and **npm** for setting up the React Native frontend
- **Python 3.x** for the Flask backend
- **OpenAI API Key** and **OpenCage API Key**

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/lkasym/AstroGo
   cd AstroGo
   ```

2. **Backend Setup**
   - Navigate to `backend` and install dependencies:
     ```bash
     cd backend
     pip install -r requirements.txt
     ```
   - Add your **OpenCage API key** and **OpenAI API key** to `app.py`.
   - Start the Flask API:
     ```bash
     python app.py
     ```

3. **Frontend Setup**
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
   - Ensure the Flask API is running on `http://localhost:5000`. Update the API URL in the frontend if necessary.

---

## 📜 Data Sources

AstroGo’s knowledge base draws from respected sources in Vedic astrology, providing authenticity and depth in its predictions:

- [Saptarishis Astrology Articles](https://saptarishisastrology.com/category/articles/)
- [Brihat Parashara Hora Shastra (English)](https://archive.org/details/BPHSEnglish)
- [Phaladeepika (2nd Edition, 1950)](https://archive.org/details/Phaladeepika2ndEd.1950ByVSubrahmanyaSastri)

---

## 🤖 AI Model Training

AstroGo’s chatbot is powered by a fine-tuned **GPT-4-turbo model**, trained on a custom astrology dataset to provide accurate and insightful responses.

---

## 🚀 Future Enhancements

- **User Profiles & History**: Track and save previous readings for future reference.
- **Social Media Integration**: Enable users to share personalized readings.
- **Expanded Astrological Techniques**: Incorporate more complex interpretations for deeper insights.

---

## 📝 License

AstroGo is licensed under the MIT License. For more details, refer to the [LICENSE](LICENSE) file.

---

<p align="center">
  <strong>✨ Thank you for exploring AstroGo! ✨</strong><br>
  We’d love to hear your feedback and suggestions! Contribute, open an issue, or give a ⭐️ on <a href="https://github.com/lkasym/AstroGo">GitHub</a>.
</p>

