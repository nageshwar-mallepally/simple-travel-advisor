AI Travel Itinerary Planner 🌍
A smart travel planning application that generates personalized travel itineraries using Google's Gemini AI. Plan your perfect Indian vacation with AI-powered recommendations for transportation, accommodation, and daily activities.

🚀 Features
AI-Powered Itinerary Generation: Create detailed travel plans using Google Gemini AI

Smart Transportation Recommendations: Get optimal travel options based on distance and preferences

Hotel Area Suggestions: Receive curated accommodation recommendations for Indian destinations

Daily Activity Planning: Structured day-by-day itineraries with morning, afternoon, and evening activities

Travel Tips & Budget Planning: Comprehensive travel advice including local customs and safety tips

Downloadable Itineraries: Export your travel plans as text files

User-Friendly Interface: Simple Streamlit-based web interface

📋 Requirements
txt
streamlit==1.28.0
google-generativeai==0.3.2
beautifulsoup4==4.12.2
requests==2.31.0
python-dotenv==1.0.0
scikit-learn==1.3.2
numpy==1.24.3
🛠️ Installation
Clone the repository

bash
git clone <repository-url>
cd travel-itinerary-planner
Install dependencies

bash
pip install -r requirements.txt
Get Google Gemini API Key

Visit Google AI Studio

Create a new API key

Copy your API key (starts with AIza...)

🎯 Usage
Run the application

bash
streamlit run travel_planner.py
Configure AI

Open your browser to http://localhost:8501

Enter your Gemini API key in the sidebar

Click "Configure AI" to initialize the system

Plan Your Trip

Enter departure and destination cities

Select travel dates and duration

Choose travel style (Budget, Comfort, Luxury, Adventure, Family)

Click "Generate Travel Plan"

Download & Share

Review your personalized itinerary

Download as text file for offline access

Share with travel companions