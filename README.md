# Soul-Scope
 Real-time personalized horoscope generator

Built an end-to-end astrology application that generates real-time, personalized horoscopes by combining astronomical calculations with generative AI. The app calculates precise birth charts using user inputs (date, time, and location of birth) via the Flatlib astrology library, interprets planetary positions, and generates tailored readings with a fine-tuned Hugging Face model.

Key Highlights:

Developed backend logic to compute accurate planetary positions and aspects from 1800 to present.

Integrated real-time horoscope generation using AI models, replacing static, template-based predictions.

Built an interactive Streamlit interface and deployed on Google Colab with ngrok for easy public access.

Designed prompt engineering workflows to transform raw astrological data into human-readable, insightful horoscopes.

Implemented modular architecture to allow future integration with live data sources (via SerpAPI) for trending astrological insights.

Tech Stack: Python, Flatlib, Hugging Face Transformers, Streamlit, ngrok, SerpAPI, Prompt Engineering.
