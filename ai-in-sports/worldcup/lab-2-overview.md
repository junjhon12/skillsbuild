# Lab Overview

In this lab, learners create a basic, interactive “player intelligence board” that displays player information and simple AI‑assisted insights when a user selects a player.The emphasis is on:
- Data grounding (AI summarizes only what exists in data)
- Simple UI interactions
= Responsible use of publicly available or open datasets

| This is not a full drag‑and‑drop canvas or custom UI project.

## Lab Duration

60–90 minutes

## Learning Objective

Learn how to use IBM Bob to combine structured sports data and AI assistance to build a simple, interactive player intelligence board while avoiding hallucination and IP issues.

## Data and Tech

### Inputs

To keep the lab simple and sustainable, SMEs must choose one of the following:
**Option A (Recommended): Static Open Dataset**
Use a CSV dataset from:
- Kaggle (e.g., public FIFA / soccer player datasets)
- GitHub (open-license sports datasets)
Dataset should include:
- Player name
- Position
- Age
- Team/league
- Basic performance metrics (appearances, goals, assists, rating)

| Advantages - No API keys required, faster setup, predictable lab timing

** Option B (Optional): API‑FOOTBALL (Read‑Only Sample)**
If API‑FOOTBALL is used:
- Provide a small, pre-extracted JSON/CSV sample
- Learners do not authenticate live
- API is explained conceptually, not fully implemented

| Learners should not be blocked by API limits or setup.


### Outputs

- A single-page interactive intelligence board
- Player selection via:
  - Dropdown menu (preferred)
- AI‑generated summary panel grounded in data

## Technology Stack

- IBM Bob
- Python (optional, if using notebook-based UI)
- Streamlit or Jupyter Widgets (choose one)

## Lab Tasks

What Learners Will Do (Lab Intent)Learners will:
1. Load a prepared player dataset
   - CSV or sample API export
1. Use IBM Bob to generate data exploration code
   - View player stats
   - Filter by position or team
1. Create a simple interactive UI
   - Dropdown to select a player
   - Auto-update stats panel
1. Use IBM Bob to generate AI-backed summaries
   - “Current form” or “player profile”
   - Derived only from dataset values (no external knowledge)
1. Display results in a clean, minimal board
   - Table + text summary
   - Optional simple bar chart
