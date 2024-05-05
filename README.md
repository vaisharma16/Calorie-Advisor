# Calorie Advisor

## Summary

Calorie Advisor is a Python app that analyzes food images to provide nutritional information and determine healthiness. It utilizes the Gemini Pro Large Image Model (LMI) API to identify food items in images and extract their calorie content.

## Key Features

- **Image Upload**: Users upload images of their meals.
- **Calorie Calculation**: The app calculates the total calories based on food item recognition.
- **Nutritional Breakdown**: It provides a detailed breakdown of nutrients, including calories, carbohydrates, fats, fiber, sugar, and other components.
- **Healthiness Assessment**: The app determines whether the meal is healthy based on nutrient balance.
- **Percentage Split of Ratio**: It displays the percentage distribution of macronutrients (carbohydrates, fats, fiber, sugar).

## Instructions for Implementation

1. Create a Python virtual environment and install required libraries (streamlit, google.generative_ai).
2. Configure the API key for Gemini Pro.
3. Define functions to prepare image data and interact with the Gemini Pro API.
4. Create a streamlit app with an upload button and a submit button.
5. Use the defined functions to process uploaded images and display the nutritional information and healthiness assessment.
6. Run the command "Streamlit run health.py".

## Benefits of Using the App

- **Improved Calorie Tracking**: Users can accurately monitor their calorie intake.
- **Informed Food Choices**: The app provides insights into the nutritional value of various foods.
- **Health Monitoring**: It allows users to make healthier food choices based on their health goals.

