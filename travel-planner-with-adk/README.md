<div align="center">
	<h1>Travel Planner (Multi‑Agent) – with Google ADK & uv</h1>
	<p><em>An experimental multi‑agent travel concierge that researches destinations, surfaces events & nearby places, and inspires trip ideas using Google ADK + open geodata.</em></p>
</div>

## Overview

This project demonstrates a lightweight travel planning assistant built on the **Google Agent Development Kit (ADK)**. It composes several specialized agents (news, places, inspiration, search grounding) into a root planner that can:

* Suggest destinations & trip ideas
* Surface relevant travel news / events (web grounded)
* Find nearby places (hotels, cafes, landmarks) using OpenStreetMap (no API key required)
* Geocode and contextualize location information

## Key Features

* Multi‑agent orchestration via Google ADK `Agent` and `AgentTool`
* Web search grounding (Google ADK search tool wrapper)
* Free nearby place lookup powered by Overpass + Nominatim (OpenStreetMap)
* Composable inspiration agent that internally invokes `news_agent` + `places_agent`
* Python 3.11+, minimal dependencies (`geopy`, `google-adk`, `python-dotenv`)

