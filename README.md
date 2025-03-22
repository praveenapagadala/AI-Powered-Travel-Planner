# AI-Powered-Travel-Planner

This project uses **Google Gemini API** to provide travel options (flights, trains, buses, and cabs) between two locations on a specific date. It is built with **Streamlit** to create an interactive web interface for users to explore travel options.

## Features

- **AI-powered Travel Planner**: Uses Gemini AI to suggest the best travel options.
- **Multiple Travel Modes**: Provides options for Flights, Trains, Buses, and Cabs.
- **Date Selection**: Allows users to select the travel date and get the best options.
- **Cost Comparison**: Displays travel options with their cost, duration, and other details.
- **Fast and Interactive**: An easy-to-use web interface using Streamlit.

## Prerequisites

- Python 3.7 or above
- Google Gemini API key (for fetching AI-generated travel options)
- Streamlit library
- Google Generative AI library

## Installation

1. Clone this repository:
   
   git clone https://github.com/yourusername/ai-powered-travel-planner.git
   cd ai-powered-travel-planner

## How to Use

Once you have the dependencies set up and the API key configured, run the Streamlit app:

streamlit run app.py

Open your browser and go to http://localhost:8501 to use the app.

Enter the source location, destination location, and travel date.

Click on Explore Travel Plans to get the best travel options between the two locations.

The app will display: Flights, Trains, Buses, and Cabs options with their respective details (cost, departure, arrival, duration, etc.)

A summary of the cheapest and fastest options.

## Example Usage

Source Location: New York

Destination Location: San Francisco

Travel Date: 2025-06-15

## How it Works

User Input: The user enters the source, destination, and travel date.

Gemini API: The app sends a prompt to the Gemini API, asking for travel options between the two locations on the selected date.

AI Response: The AI generates a JSON response with options for flights, trains, buses, and cabs.

Summary Generation: The app processes this JSON response, providing a summary of the cheapest and fastest travel options.

Display Results: The app displays detailed travel options for each mode of transport.

## Dependencies

1.streamlit: For creating the web app.

2.google-generativeai: For interacting with the Gemini API.

3.json: For parsing and handling JSON data.

4.datetime: For handling date-related operations.

## Acknowledgments

Google Gemini API: For providing the AI-powered travel options.

Streamlit: For creating an interactive and easy-to-use web interface.


