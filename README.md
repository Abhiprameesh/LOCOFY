# LOCOFY 🌍  
**An AI-Assisted Local Tourism Planner**  

Locofy is an intelligent travel companion that crafts personalized travel plans and recommendations tailored to your preferences. By leveraging real-time data from APIs, it ensures accurate and up-to-date suggestions for hotels, attractions, and restaurants. With its integrated chatbot, Locofy transforms trip planning into an efficient and engaging experience.  

---

## 🚀 Features  
- **AI-Generated Travel Plans**: Personalized itineraries and queries using Google's Gemini AI.  
- **Real-Time API Integration**: Data from RapidAPI (TripAdvisor) provides the latest details about top local hotels and attractions. Language detection and translation features using Google Translate API.
- **Chatbot Integration**: Seamless interaction for quick queries, enhancing user experience and trip planning efficiency.  

---

## 🛠️ Tech Stack  
- **Frontend**: React, Vite, JSX, CSS, Tailwind CSS  
- **Backend**: Node.js, Express.js, MongoDB (Mongoose)  
- **APIs**: RapidAPI (TripAdvisor, Google Translate)  
- **AI/Chatbot**: Google Generative AI (Gemini Pro) for conversational capabilities  

---

## 📖 How It Works  
1. Enter your travel preferences: location, dates, trip type, and budget.  
2. Locofy fetches real-time data using integrated APIs.  
3. The AI crafts a personalized itinerary with recommendations for accommodations, attractions, and dining.  
4. Use the chatbot to modify or inquire about your plans effortlessly.  

---

## 🖥️ Installation & Setup  

### Prerequisites  
- Node.js and npm installed  
- MongoDB connection string
- API keys for [RapidAPI](https://rapidapi.com/) and [Google Gemini API](https://ai.google.dev/)

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Abhiprameesh/LOCOFY.git  
   cd LOCOFY  
   ```  

2. Install dependencies for the root, server, and client:  
   ```bash  
   npm install
   cd server && npm install
   cd ../client && npm install
   cd ..
   ```  

3. Set up environment variables:  

   **Backend (`server/.env`)**
   Create a `.env` file in the `server` directory and add:  
   ```env  
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   PORT=8080
   ```  

   **Frontend (`client/.env`)**
   Create a `.env` file in the `client` directory and add:  
   ```env  
   VITE_GEMINI_API_KEY=your_google_gemini_api_key
   VITE_RAPIDAPI_KEY=your_rapidapi_key
   ```  

4. Run the development server (starts both backend and frontend):  
   ```bash  
   npm run dev  
   ```  

5. Access Locofy in your browser at: `http://localhost:5173`  

---

## 🌟 Future Enhancements  
- Multilingual support for a global audience.  
- Integration with more travel APIs for broader coverage.  
- Offline mode for itinerary viewing and saving.  

---

## 🤝 Contributions  
Contributions are welcome! Feel free to:  
- Submit issues or feature requests.  
- Fork the repository and create pull requests.  
