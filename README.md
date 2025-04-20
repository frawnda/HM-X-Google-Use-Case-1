# Predicting Box Office Revenue
Our team was given Use Case 1 as our task for the hackathon, where we were asked to use Google Auto-ML to predict movie revenue based on a select number of variables. Our goal was to minimize the Mean Absolute Percentage Error (MAPE) using the TMDB dataset that we were generously provided. (The time we were given was 4 hours!)

Resources and Tools:
    - TMDB dataset (50 Lionsgate films)
    - API Key for Gemini
    - GCP AutoML
    - GCP AiPlatform
    - Google Colab

Python Libraries:
    - pandas
    - numpy
    - kagglehub (for kaggle dataset adapter)
    - sklearn, metrics (for MAPE)
    - google, genai
    - matplotlib

MVP and Key Takeaways:
    - 139.48% Current Hold-Out MAPE (record 129.26%), Model 3.0
    - End-to-end solution that lets you enter a movie's budget, cast, release month, genre, and short description as determinants for revenue prediction
    - Business Proposals: Audience Feedback Agent, Dynamic Ad Spend Optimizer, Pre-Production Greenlight Engine