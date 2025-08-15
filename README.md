# decision-buddy
my attempt to deal w indecisiveness in everyday life.

## **Randomized but Weighted Suggestions**
User can input options (movies, menu items, activities).
App assigns weights based on your past preferences, ratings, or mood.
Algorithm randomly picks but biases toward higher-weighted choices.

## **“This or That” Rapid Elimination Mode**
Shows you two options at a time → you click the one you feel more drawn to → repeats until one winner remains.
Makes the process feel like a game.

## **AI-Generated Summaries**
If choosing a movie: fetch ratings + plot summaries from APIs (OMDb/TMDB) and give a brief personalized recommendation.
If choosing food: fetch images & reviews, give a mood-based choice.

## **Past Decision Tracking**
Stores what you chose and how satisfied you were (simple 1–5 stars).
Over time, the algorithm learns your patterns.

## **Tech Stack Ideas**
Frontend: React / Next.js (quick, responsive UI)

Backend: Node.js + Express or FastAPI (Python)

Database: SQLite/PostgreSQL for storing choices & feedback

Extras:
APIs: OMDb API (movies), Yelp/Foursquare API (food), or Spotify API (songs)
Simple ML model (Scikit-learn or TensorFlow Lite) for preference learning
