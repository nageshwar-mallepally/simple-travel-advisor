
---

```markdown
# AI Travel Itinerary Planner

A smart travel planning application that generates personalized travel itineraries using **Google's Gemini AI**. Plan your perfect **Indian vacation** with AI-powered recommendations for transportation, accommodation, and daily activities.

---

## Features

- **AI-Powered Itinerary Generation**  
  Create detailed travel plans using Google Gemini AI.

- **Smart Transportation Recommendations**  
  Get optimal travel options based on distance and preferences.

- **Hotel Area Suggestions**  
  Receive curated accommodation recommendations for Indian destinations.

- **Daily Activity Planning**  
  Structured day-by-day itineraries with morning, afternoon, and evening activities.

- **Travel Tips & Budget Planning**  
  Comprehensive travel advice including local customs and safety tips.

- **Downloadable Itineraries**  
  Export your travel plans as text files for offline use.

- **User-Friendly Interface**  
  Built with Streamlit — intuitive and easy to use.

---

## Requirements

All dependencies are listed in `requirements.txt`. Here's a quick overview:

```

streamlit==1.28.0
google-generativeai==0.3.2
beautifulsoup4==4.12.2
requests==2.31.0
python-dotenv==1.0.0
scikit-learn==1.3.2
numpy==1.24.3

````

---

## Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd travel-itinerary-planner
````

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Get Google Gemini API Key

* Visit [Google AI Studio](https://makersuite.google.com/)
* Create a new API key
* Copy your API key (starts with `AIza...`)
* Create a `.env` file in the root directory of your project and add the following:

```env
GEMINI_API_KEY=your-api-key-here
```

---

## Usage

### 1. Run the Application

```bash
streamlit run travel_planner.py
```

### 2. Open in Your Browser

Navigate to:

```
http://localhost:8501
```

### 3. Configure the AI

* Paste your Gemini API key in the sidebar
* Click the **"Configure AI"** button to initialize the system

### 4. Plan Your Trip

* Enter your **departure** and **destination** cities
* Select **travel dates** and **duration**
* Choose your **travel style**:

  * Budget
  * Comfort
  * Luxury
  * Adventure
  * Family
* Click **"Generate Travel Plan"**

---

## Download & Share

* Review your personalized itinerary
* Click the **"Download"** button to save it as a `.txt` file
* Share or print for offline access

---

## License

This project is open-source. See the [LICENSE](LICENSE) file for license details.

---

## Contributions

Contributions are welcome!

To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Make your changes
4. Commit your changes (`git commit -m "Add some feature"`)
5. Push to the branch (`git push origin feature-name`)
6. Open a pull request

```

---

Let me know if you want to:
- Add a demo image or video
- Prepare for deployment (e.g. Streamlit Cloud)
- Include CI/CD or Docker support

This README is now ready to be used in a real-world open-source or production repository.
```
