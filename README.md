# TravelBuddy: AI-Powered Trip Itinerary Chatbot

## Overview
TravelBuddy is an intelligent Streamlit chatbot that generates personalized, detailed travel itineraries using advanced language models from Groq.

## Features
- Interactive chat interface
- Multiple language model selections
- Configurable conversational memory
- Dynamic itinerary generation

## Prerequisites
- Python 3.8+
- Groq API Key

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/travelbuddy.git
cd travelbuddy
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Environment Configuration
1. Create a `.env` file in the project root directory
2. Add your Groq API key to the `.env` file:
```
GROQ_API_KEY=your_groq_api_key_here
```
**Important Notes:**
- Replace `your_groq_api_key_here` with your actual Groq API key
- Do not share your `.env` file or commit it to version control
- Add `.env` to your `.gitignore` file to prevent accidental exposure of sensitive credentials

## Usage
Run the application:
```bash
streamlit run chatbot.py
```

## Configuration
- Select language models from the sidebar
- Adjust conversational memory length

## Dependencies
- Streamlit
- Groq
- LangChain
- Python-dotenv
