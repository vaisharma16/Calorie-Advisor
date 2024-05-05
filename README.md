# Calorie Advisor

## Summary

Calorie Advisor is a Python app that analyzes food images to provide nutritional information and determine healthiness. It utilizes the Gemini Pro Large Image Model (LMI) API to identify food items in images and extract their calorie content.

## Key Features

- **Image Upload**: Users upload images of their meals.
- **Calorie Calculation**: The app calculates the total calories based on food item recognition.
- **Nutritional Breakdown**: It provides a detailed breakdown of nutrients, including calories, carbohydrates, fats, fiber, sugar, and other components.
- **Healthiness Assessment**: The app determines whether the meal is healthy based on nutrient balance.
- **Percentage Split of Ratio**: It displays the percentage distribution of macronutrients (carbohydrates, fats, fiber, sugar).


## Benefits of Using the App

- **Improved Calorie Tracking**: Users can accurately monitor their calorie intake.
- **Informed Food Choices**: The app provides insights into the nutritional value of various foods.
- **Health Monitoring**: It allows users to make healthier food choices based on their health goals.


## Installation

To set up the project locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/your_username/yt-transcriber.git

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Set up your environment variables by creating a .env file and adding your Google API key:
   ```bash
   GOOGLE_API_KEY=your_api_key_here
   
4. Run the application:
   ```bash
   streamlit run yt_transcriber.py

