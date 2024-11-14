

<h1 align="center">🌌 AstroGo: Your AI-Powered Astrology Companion 🌌</h1>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/Platform-React%20Native%20|%20Flask-green" alt="Platform">
  <img src="https://img.shields.io/badge/Language-JavaScript%20|%20Python-yellow" alt="Languages">
  <img src="https://img.shields.io/badge/OpenAI-GPT--4o-purple" alt="OpenAI">
  <br><br>
  <strong><em>Blending ancient astrological wisdom with modern AI technology.</em></strong>
</p>

---

<p align="center">
  
  <img src="https://github.com/lkasym/AstroGo/blob/main/Screenshot_20241113_114209_Expo%20Go.jpg" width="250" style="padding: 5px;">
  <img src="https://github.com/lkasym/AstroGo/blob/main/Screenshot_20241113_114213_Expo%20Go.jpg" width="250" style="padding: 5px;">
  <br>
  <img src="https://github.com/lkasym/AstroGo/blob/main/Screenshot_20241113_114226_Expo%20Go.jpg" width="250" style="padding: 5px;">
  <img src="https://github.com/lkasym/AstroGo/blob/main/Screenshot_20241113_114230_Expo%20Go.jpg" width="250" style="padding: 5px;">
</p>

---

## 🌠 Key Features

- 🗣️ **AI Chatbot** - Get real-time answers to your astrology questions.
- 🔮 **In-Depth Chart Calculations** - Analyze planetary positions, Dashas, and more.
- 📍 **Location-Based Insights** - Accurate, personalized readings powered by OpenCage API.
- 🎨 **Elegant UI** - Designed with React Native for an intuitive user experience.
- 🚀 **Optimized Backend** - Efficient data processing with Flask for real-time insights.

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

AstroGo combines advanced AI with traditional astrology for a unique, personalized experience:

1. **Data Processing**:
   - Analyzes planetary positions, Lagna, houses, and Dasha cycles.
   - Considers planetary strength, weakness, or debilitation.

2. **AI-Powered Chatbot**:
   - Built with OpenAI’s fine-tuned GPT-4-turbo model for real-time, personalized responses.

3. **Geolocation for Precision**:
   - Uses OpenCage API to enhance predictions based on the user’s birth location.

---

## 🧑‍💻 Installation Guide

### Prerequisites

- **Node.js** and **npm** for React Native setup
- **Python 3.x** for the backend
- **API Keys** for OpenAI and OpenCage

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
   - Ensure the backend is running on `http://localhost:5000`. Update the API URL in the frontend if needed.

---

## 📜 Data Sources

AstroGo’s model is based on respected astrological texts, ensuring accurate and insightful predictions:

- [Saptarishis Astrology Articles](https://saptarishisastrology.com/category/articles/)
- [Brihat Parashara Hora Shastra (English)](https://archive.org/details/BPHSEnglish)
- [Phaladeepika (2nd Edition, 1950)](https://archive.org/details/Phaladeepika2ndEd.1950ByVSubrahmanyaSastri)

---

## 🤖 AI Model Training

AstroGo’s chatbot is fine-tuned with **OpenAI GPT-4-turbo** on a rich dataset, enabling it to provide accurate and insightful astrological guidance.

---

## 🚀 Future Enhancements

- **User Profiles & History** - Save and revisit past readings.
- **Social Media Integration** - Share unique insights with friends and followers.
- **Expanded Interpretations** - Incorporate additional astrological methods for even deeper insights.

---

## 📝 License

AstroGo is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

<p align="center">
  <strong>✨ Thank you for exploring AstroGo! ✨</strong><br>
  We’d love to hear your feedback and suggestions! Contribute, open an issue, or give a ⭐️ on <a href="https://github.com/lkasym/AstroGo">GitHub</a>.
</p>

