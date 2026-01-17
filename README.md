🎾 Game Analytics: Unlocking Tennis Data with SportRadar API
📌 Project Overview

This project is an end-to-end sports data analytics application built using the SportRadar Tennis API, SQL databases, and Streamlit.
It focuses on extracting, structuring, analyzing, and visualizing tennis competition data, venue infrastructure, and competitor rankings to generate meaningful insights for analysts, sports organizations, and decision-makers.

The project was completed as part of a 6-month internship at Labmentix and serves as the final major capstone project.

🎯 Problem Statement

Sports data from APIs is often complex, deeply nested, and difficult to analyze directly.
This project aims to:

Parse and normalize complex tennis data from the SportRadar API

Store it in a structured relational database

Perform SQL-based analytics

Provide an interactive Streamlit dashboard for exploration and insight generation

🧠 Key Features

API-based data extraction from SportRadar

Relational database design with normalized schemas

SQL-based analytical queries

Interactive dashboards built using Streamlit

Competition hierarchy and infrastructure analysis

Competitor ranking and momentum analysis

🛠️ Tech Stack
Category	Technologies
Language	Python
API	SportRadar Tennis API
Database	PostgreSQL / MySQL
ORM	SQLAlchemy
Visualization	Plotly
Web App	Streamlit
Version Control	Git & GitHub

📂 Project Structure
Game-Analytics-Tennis-SportRadar/
│
├── 1_Competitions.py            # Competition hierarchy analytics
├── 2_Complexes_Venues.py        # Venues & infrastructure analytics
├── 3_Competitor_Rankings.py     # Competitor ranking & momentum analytics
│
├── api_config.py                # API configuration
├── api_data_extractor.py        # API data extraction logic
│
├── db_config.py                 # Database connection setup
├── db_loader.py                 # Data insertion into database
├── db_models.py                 # Database schema models
│
├── Home.py                      # Streamlit home dashboard
├── main.py                      # Streamlit app entry point
│
├── requirement.txt              # Python dependencies
├── .gitignore                   # Git ignore rules
└── README.md                    # Project documentation

📊 Streamlit Application Modules
🔹 Overview Pulse

High-level KPIs

Global competition and venue summaries

Entry point for the application

🔹 Competition Landscape

Competition hierarchy analysis

Distribution by category, level, and gender

Parent vs sub-competition insights

🔹 Competitor Spotlight

Points vs Rank analysis

Ranking momentum visualization

Performance density analytics

🔹 Trend Explorer

Ranking trends and momentum patterns

Country-level performance insights

Interactive filtering and exploration

▶️ How to Run the Project Locally
1️⃣ Clone the Repository
git clone https://github.com/Karthik-0917/Game-Analytics-Tennis-SportRadar.git
cd Game-Analytics-Tennis-SportRadar

2️⃣ Install Dependencies
pip install -r requirement.txt

3️⃣ Configure Environment Variables

Create a .env file and add:

SPORTSRADAR_API_KEY=your_api_key_here
DB_HOST=your_db_host
DB_NAME=your_db_name
DB_USER=your_db_user
DB_PASSWORD=your_db_password


⚠️ Do not upload .env to GitHub

4️⃣ Run the Streamlit App
streamlit run Home.py

📈 Business Use Cases

Event exploration across competition hierarchies

Infrastructure and venue density analysis

Talent scouting using ranking momentum

Data-driven decision support for sports bodies

Strategic planning for tournament organizers

👥 Team Contributions
Name	Contribution
Amal	Competition hierarchy analytics & Streamlit integration
Amit	Complexes & venues analytics & Streamlit integration
Karthik Neduri	Competitor rankings, momentum analysis, database integration, documentation
📌 Key Learnings

Working with real-world sports APIs

Designing normalized SQL schemas

Writing optimized SQL queries

Building interactive analytics dashboards

Managing end-to-end analytics workflows

Professional Git and GitHub practices

🚀 Future Enhancements

Match-level and historical performance analytics

Predictive modeling for ranking movement

Cloud deployment (AWS / Azure)

Role-based dashboards

Support for additional sports domains

📜 License

This project is developed for educational and analytical purposes as part of an internship program.