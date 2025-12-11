**🌦️ Flask Weather App**

A lightweight Flask application that fetches real-time weather updates using the OpenWeather API. Users can enter a city name and instantly view temperature, humidity, wind speed, and overall conditions through a clean HTML interface.

**🚀 Features**

Real-time weather data

API integration with OpenWeather

Clean UI using HTML + Jinja2 templates

Organized project structure

Beginner-friendly Flask example

**📂 Project Structure**

flask-weather-app/
│── app.py
│── requirements.txt
│── templates/
│   └── index.html
│── static/
│   └── style.css  (optional)

**🔧 Setup & Installation**
1. Create a virtual environment
python -m venv venv

2. Activate it

 Windows:-
 venv\Scripts\activate

 macOS/Linux:-
source venv/bin/activate

3. Install dependencies:-
pip install -r requirements.txt

4. Add your API key

Create a .env file:

API_KEY=YOUR_OPENWEATHER_API_KEY

▶️ Run the App
python app.py


Then visit:

http://127.0.0.1:5000

**📌 Notes**

Do not upload your venv/ folder.

Add venv/ to .gitignore.

Keep .env private.

**🌱 Future Improvements**

5-day forecast

Better UI styling

Weather icons

Error handling for invalid cities
