# 🌍 AI Travel Itinerary Planner

A smart travel planning application that generates personalized travel itineraries using **Google's Gemini AI**. Plan your perfect **Indian vacation** with AI-powered recommendations for transportation, accommodation, and daily activities.

---

## 🚀 Features

- 🤖 **AI-Powered Itinerary Generation**  
  Create detailed travel plans using Google Gemini AI

- 🚗 **Smart Transportation Recommendations**  
  Get optimal travel options based on distance and preferences

- 🏨 **Hotel Area Suggestions**  
  Receive curated accommodation recommendations for Indian destinations

- 📅 **Daily Activity Planning**  
  Structured day-by-day itineraries with morning, afternoon, and evening activities

- 💡 **Travel Tips & Budget Planning**  
  Comprehensive travel advice including local customs and safety tips

- 📥 **Downloadable Itineraries**  
  Export your travel plans as text files for offline use

- 🖥️ **User-Friendly Interface**  
  Built with Streamlit — intuitive and easy to use

---

## 📋 Requirements

All dependencies are listed in `requirements.txt`. Here's a quick overview:

streamlit==1.28.0
google-generativeai==0.3.2
beautifulsoup4==4.12.2
requests==2.31.0
python-dotenv==1.0.0
scikit-learn==1.3.2
numpy==1.24.3

yaml
Copy code

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd travel-itinerary-planner
2. Install Dependencies
bash
Copy code
pip install -r requirements.txt
3. Get Google Gemini API Key
Visit Google AI Studio

Create a new API key

Copy your API key (starts with AIza...)

Add it to a .env file like:

ini
Copy code
GEMINI_API_KEY=your-api-key-here
🎯 Usage
1. Run the App
bash
Copy code
streamlit run travel_planner.py
2. Open in Browser
Visit: http://localhost:8501

3. Configure AI
Paste your Gemini API key in the sidebar

Click "Configure AI" to initialize the system

4. Plan Your Trip
Enter departure and destination cities

Select travel dates and duration

Choose travel style:
Budget, Comfort, Luxury, Adventure, Family

Click "Generate Travel Plan"

📥 Download & Share
Review your personalized itinerary

Click "Download" to save as a .txt file

Share or print for offline access