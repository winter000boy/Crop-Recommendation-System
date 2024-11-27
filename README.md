# Crop Recommendation System

The **Crop Recommendation System** is a machine learning-based web application that assists farmers in determining the most suitable crop to grow based on various environmental factors. This tool leverages data analytics and predictive modeling to enhance agricultural decision-making and productivity.

## Features

- **Crop Prediction**: Suggests the best crop to grow based on user-provided parameters such as temperature, humidity, pH, and rainfall.
- **Web-Based Interface**: User-friendly web interface developed with Flask and HTML.
- **Data-Driven Insights**: Uses machine learning models trained on real-world agricultural data.
- **Scalable Architecture**: Can be extended to include additional features like weather integration or pest detection.

---

## Table of Contents

1. [Tech Stack](#tech-stack)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Dataset](#dataset)
5. [Project Structure](#project-structure)
6. [Model Description](#model-description)
7. [Future Scope](#future-scope)
8. [License](#license)

---

## Tech Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **Visualization**: Jupyter Notebook
- **Tools**: Pickle for model serialization

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/winter000boy/Crop-Recommendation-System.git
   cd Crop-Recommendation-System

2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate

3. Install the required dependencies:
   pip install -r requirements.txt

4. Run the application:   
   Open the application in your browser at http://127.0.0.1:5000.


Here’s a detailed README file in Markdown for your Crop Recommendation System project:

markdown
Copy code
# Crop Recommendation System

The **Crop Recommendation System** is a machine learning-based web application that assists farmers in determining the most suitable crop to grow based on various environmental factors. This tool leverages data analytics and predictive modeling to enhance agricultural decision-making and productivity.

## Features

- **Crop Prediction**: Suggests the best crop to grow based on user-provided parameters such as temperature, humidity, pH, and rainfall.
- **Web-Based Interface**: User-friendly web interface developed with Flask and HTML.
- **Data-Driven Insights**: Uses machine learning models trained on real-world agricultural data.
- **Scalable Architecture**: Can be extended to include additional features like weather integration or pest detection.

---

## Table of Contents

1. [Tech Stack](#tech-stack)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Dataset](#dataset)
5. [Project Structure](#project-structure)
6. [Model Description](#model-description)
7. [Future Scope](#future-scope)
8. [License](#license)

---

## Tech Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS
- **Machine Learning**: Scikit-learn, Pandas, NumPy
- **Visualization**: Jupyter Notebook
- **Tools**: Pickle for model serialization

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/winter000boy/Crop-Recommendation-System.git
   cd Crop-Recommendation-System
   
2. Create and activate a virtual environment:

   ```bash
      Copy code
      python -m venv env
      source env/bin/activate  # On Windows: env\Scripts\activate

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   
4. Run the application:

   ```bash
   python app.py
Open the application in your browser at http://127.0.0.1:5000.

Usage
Launch the web application.
Enter the environmental parameters:
Temperature (°C)
Humidity (%)
pH level
Rainfall (mm)
Click "Submit" to get the crop recommendation.
View the recommended crop along with any additional insights.


## Project Structure
Crop-Recommendation-System/
├── static/                     # Static files (CSS, JS, images)
├── templates/                  # HTML templates for the Flask app
├── Crop Recommendation System.ipynb  # Jupyter notebook for model training
├── Crop_recommendation.csv     # Dataset for model training
├── app.py                      # Flask application script
├── crop_recommendation_model.pkl  # Trained ML model
├── minmaxscaler.pkl            # Scaler used for normalization
├── standscaler.pkl             # Standard Scaler for preprocessing
└── README.md                   # Project documentation


