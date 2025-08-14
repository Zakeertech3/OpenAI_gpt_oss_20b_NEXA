# AI News Reporter & Analyst

This project is an interactive web application that uses a locally-run, 20-billion-parameter open-source Large Language Model (gpt-oss:20b) to analyze news articles. The application takes any news article as input and automatically generates a headline, a concise summary, and a list of key entities (people, organizations, and locations).


# Features

Automated Headline Generation: Creates a catchy, single-sentence headline for any article.

Concise Summarization: Provides a 3-sentence summary of the article's main points.

Key Entity Extraction: Identifies and lists important people, places, and organizations mentioned in the text.

Interactive UI: A simple and clean user interface built with Gradio allows for easy interaction.

Powered by Open-Source LLM: All analysis is performed by the gpt-oss:20b model running locally via Ollama.

# Tech Stack

Language: Python

LLM Framework: Ollama

LLM Model: gpt-oss:20b

Web UI: Gradio

Data Handling: Hugging Face datasets
