# AunTea 🫖

A casual news analysis chatbot powered by Google Gemini API with RSS feed integration.

## Features

- Real-time news analysis from multiple RSS feeds
- Casual and quippy conversation style
- Chat history support
- Rich media support (images and reference links)
- Categories: Movies/TV, Music, Money, Photography/Videography, Pop Culture, Sports, Technology & AI

## Setup

1. Clone the repository
2. Copy `.env.example` to `.env` and fill in your credentials
3. Install dependencies: `pip install -r requirements.txt`
4. Run the server: `uvicorn main:app --reload`

## RSS Feeds

- Movies/TV: https://rss.app/feeds/v1.1/_6QzByBP0Y0E9bL0O.json
- Music: https://rss.app/feeds/v1.1/_p1hbSzosU9dbDQWx.json
- Money: https://rss.app/feeds/v1.1/_fcZVOvvC7xA6iz8u.json
- Pop Culture: https://rss.app/feeds/v1.1/_8Tib7bkE02swlmp7.json
- Sports: https://rss.app/feeds/v1.1/_5pZybCiMDbl5fBo8.json
- Technology & AI: https://rss.app/feeds/v1.1/_GNEAg9D5CvYRIxAQ.json

## API Key Setup

Before running the chatbot, you'll need to:
1. Obtain a Google Gemini API key
2. Set up a MongoDB instance for chat history
3. Configure the .env file with your credentials