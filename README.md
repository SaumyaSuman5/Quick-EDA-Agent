This project is a lightweight Data Insight Agent built for the Google × Kaggle Agentic AI Hackathon (Freestyle Track).
It performs Exploratory Data Analysis using natural-language questions without needing any API key or LLM.

The agent loads the Titanic dataset (via seaborn) and answers questions like:

“How many rows are there?”

“Which columns have the most missing values?”

“Top values of Sex?”

“Mean Age?”

“Female survival rate?”

“Histogram of Age” (auto-plots)

This makes EDA easy, fast, and beginner-friendly.

Tech Stack

Python 3

Google Colab

pandas for data manipulation

numpy for statistics

matplotlib for plotting

seaborn for dataset loading

Custom rule-based agent logic
