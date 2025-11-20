Travel Planner — Multi-Agent System using Google ADK

This project is a lightweight, intelligent AI-powered travel planning assistant built using the Google Agent Development Kit (ADK).
It orchestrates multiple specialized agents—news, places, inspiration, and grounded search—into one unified root planner that creates smart, contextual, and personalized travel ideas.
The result: a clean, modular, and multi-agent workflow capable of generating end-to-end trip suggestions.

✨ Features

🧠 Multi-Agent Architecture powered by Google ADK

📍 Destination insights with real-time grounding

📰 Travel-related news context for better planning

💡 Inspiration suggestions to shape unique travel plans

🔎 Intelligent search agent for structured and validated outputs

⚡ Fast, modular, and easy to extend

🧱 Tech Stack

Google ADK (Agent Development Kit)

Python

UV (ultra-fast package & environment management)

dotenv for environment variables

How It Works

The root travel planner agent receives the user’s travel query.

It delegates parts of the task to specialized agents:

News Agent → recent travel-related updates

Places Agent → top attractions & details

Inspiration Agent → ideas based on user preferences

Grounding Agent → validated search results

Each agent returns structured responses that are merged into a final formatted itinerary.

JSON / Schema-based structured outputs

Modular agent-oriented architecture
