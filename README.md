

<h1 align="center">🌌 AstroGo: Your Personalized AI Astrology App 🌌</h1>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License"> 
  <img src="https://img.shields.io/badge/Platform-React%20Native%20|%20Flask-green" alt="Platform"> 
  <img src="https://img.shields.io/badge/OpenAI-GPT--4o-purple" alt="OpenAI">
</p>

<p align="center">AstroGo is a state-of-the-art astrology app that combines classical astrological wisdom with cutting-edge AI technology. Built with an intuitive React Native frontend, a Flask API backend, and a fine-tuned GPT-4 AI model, AstroGo offers interactive, personalized readings like never before.</p>

---

## ✨ Key Features

- 🗣️ **AI-Powered Chatbot** - Get personalized responses to all your astrology-related questions.
- 🔮 **Advanced Astrological Calculations** - Provides deep insights into planetary positions, houses, and Dasha cycles.
- 📍 **Location-Specific Predictions** - Integrated with the OpenCage API for precise geolocation-based readings.
- 🎨 **Smooth UI** - A responsive, visually appealing interface crafted with React Native.
- 🚀 **Optimized API** - High-speed backend in Flask, processing astrological data seamlessly.

---

## 📁 Project Structure

```plaintext
AstroGo/
├── backend/                    # Flask API backend files
│   ├── app.py                  # Main API code
│   ├── models/                 # Model storage
│   └── utils/                  # Helper scripts
├── frontend/                   # React Native frontend files
│   ├── App.js                  # Main app entry point
│   ├── components/             # Reusable UI components
│   └── screens/                # App screens
├── dataset/                    # Dataset files
│   └── astro_data.json         # Custom astrology dataset
└── requirements.txt            # Python dependencies
```

---

## ⚙️ Tech Stack

| Component     | Technology    |
| ------------- | ------------- |
| **Frontend**  | React Native  |
| **Backend**   | Flask, Python |
| **AI Model**  | OpenAI GPT-4-turbo, fine-tuned |
| **Geolocation** | OpenCage API |

---

## 🛠️ Setup and Installation

### Prerequisites

- **Node.js** and **npm** (for React Native)
- **Python 3.x**
- **OpenAI API Key** and **OpenCage API Key**

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/lkasym/AstroGo
   cd AstroGo
   ```

2. **Backend Setup**
   - Navigate to `backend` folder:
     ```bash
     cd backend
     pip install -r requirements.txt
     ```
   - Insert your **OpenCage API key** in `app.py`.
   - Run the Flask API:
     ```bash
     python app.py
     ```

3. **Frontend Setup**
   - Navigate to `frontend` folder:
     ```bash
     cd ../frontend
     npm install
     ```
   - Start the app:
     ```bash
     npm start
     ```

4. **Connecting Frontend and Backend**
   - Ensure the backend is running on `http://localhost:5000` and update the API URL in the frontend if needed.

---

## 🧑‍💻 How It Works

AstroGo combines traditional astrology and AI to give users an enhanced reading experience. Here’s a breakdown of its core processes:

1. **Data Processing**:
   - Calculates planetary positions, Lagna, and planetary influences (malefic/benefic).
   - Evaluates planet strength (strong, weak, neutral, or debilitated).
   - Determines Dasha and Antardasha periods for life events.

2. **Interactive Chatbot**:
   - AI chatbot (fine-tuned on classical astrological texts) interprets and responds to users’ questions, providing insight based on planetary placements and houses.

3. **Location-Based Precision**:
   - Geolocation-based readings with OpenCage API, allowing predictions tailored to the user’s birth location.

---

## 📚 Data Sources

AstroGo's dataset has been meticulously curated from renowned sources, including:

- [Saptarishis Astrology Articles](https://saptarishisastrology.com/category/articles/)
- [Brihat Parashara Hora Shastra (English)](https://archive.org/details/BPHSEnglish)
- [Phaladeepika (2nd Edition, 1950)](https://archive.org/details/Phaladeepika2ndEd.1950ByVSubrahmanyaSastri)

These sources provide a foundation for AstroGo’s AI, enhancing prediction accuracy and depth.

---

## 🧠 Model Training

AstroGo’s AI model is powered by **OpenAI GPT-4-turbo**, fine-tuned on a rich dataset of astrology literature to generate accurate and insightful predictions.

---

## 🌟 Future Enhancements

- **User Profiles & History** - Save and track past readings.
- **Social Sharing** - Enable users to share readings on social media.
- **Expanded Interpretation Techniques** - Add advanced astrological methods for in-depth insights.

---

## 📜 License

AstroGo is open-source software licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

<p align="center">
✨ Thanks for exploring AstroGo! If you have any feedback or suggestions, feel free to reach out or contribute on <a href="https://github.com/lkasym/AstroGo">GitHub</a>. ✨
</p>

