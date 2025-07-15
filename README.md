# Reddit Persona Generator

A Python tool to scrape a Reddit user's posts and comments, then generate an AI-based persona profile using OpenAI's GPT API.

## 🚀 Features

- Scrapes public Reddit activity
- Summarizes tone, interests, and personality
- Uses OpenAI to generate persona insights
- Simple CLI-based usage

## 🛠️ Setup

1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/reddit_persona_generator.git
   cd reddit_persona_generator
## Install requirements:
pip install -r requirements.txt

## Add .env file:

REDDIT_CLIENT_ID=your_id
REDDIT_CLIENT_SECRET=your_secret
REDDIT_USER_AGENT=your_agent
OPENAI_API_KEY=your_openai_key


## Run 
python main.py

## Output Example

Persona for u/username:
- Interests: Tech, Gaming
- Tone: Friendly, Informative
- Activity: Mostly evening (IST)

  ## Requirements
Python 3.8+

PRAW

OpenAI

python-dotenv
