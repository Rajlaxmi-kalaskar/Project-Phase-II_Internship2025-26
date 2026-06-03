
YouTube Channel Performance and Engagement Dashboard
📌 Project Overview

The YouTube Channel Performance and Engagement Dashboard is a data analytics platform developed to help content creators, researchers, marketers, and businesses analyze YouTube channel performance and audience engagement. The system collects channel and video data using the YouTube Data API, stores the information in a database, and presents interactive visualizations and AI-powered insights through a user-friendly dashboard.

The dashboard enables users to monitor channel growth, compare multiple channels, identify trending content, evaluate audience engagement, and receive actionable recommendations for improving channel performance.

🎯 Objectives
Analyze YouTube channel performance using key metrics.
Measure audience engagement and channel growth.
Compare multiple YouTube channels.
Identify top-performing videos and content trends.
Generate AI-powered growth recommendations.
Provide interactive visualizations for better decision-making.
✨ Features
1. Channel Analytics
Channel Name and Description
Subscriber Count
Total Views
Total Uploaded Videos
Channel Creation Date
Country Information
2. Video Analytics
Video Title Analysis
Views Count
Likes Count
Comments Count
Video Duration
Publish Date
Top Performing Videos
3. Performance Metrics
Average Views per Video
Engagement Rate
Subscriber-to-View Ratio
Upload Frequency
Channel Growth Indicators
4. AI-Powered Growth Analysis
Strength Identification
Weakness Detection
Content Improvement Suggestions
Growth Recommendations
Audience Engagement Insights
5. Channel Comparison Module
Compare up to 5 YouTube Channels
Subscriber Comparison
Views Comparison
Video Count Comparison
Leaderboard Ranking
Performance Share Analysis
6. Interactive Dashboard
KPI Cards
Charts and Graphs
Trend Analysis
Data Tables
Visual Performance Reports
🏗️ System Architecture
User Input
     │
     ▼
YouTube Data API
     │
     ▼
Data Collection Module
     │
     ▼
Database Storage
     │
     ▼
Data Processing & Analytics
     │
     ▼
AI Growth Analysis
     │
     ▼
Streamlit Dashboard
🛠️ Technologies Used
Frontend
Streamlit
HTML
CSS
Backend
Python
Database
SQLite / MySQL
Libraries
Pandas
NumPy
Plotly
Matplotlib
Streamlit
Google API Client
Transformers
Scikit-learn
APIs
YouTube Data API v3
📂 Project Structure
youtube-performance-dashboard/
│
├── streamlit_app/
│   ├── modules/
│   │   ├── channel_analysis.py
│   │   ├── video_analysis.py
│   │   ├── channel_comparison.py
│   │   ├── ai_growth.py
│   │   └── engagement_analysis.py
│   │
│   ├── dashboard.py
│   └── app.py
│
├── database/
│   ├── database.db
│   └── db_operations.py
│
├── api/
│   └── youtube_api.py
│
├── assets/
│   ├── images
│   └── icons
│
├── requirements.txt
├── README.md
└── LICENSE
⚙️ Installation
1. Clone the Repository
git clone https://github.com/your-username/youtube-performance-dashboard.git
cd youtube-performance-dashboard
2. Create Virtual Environment
python -m venv venv
3. Activate Environment

Windows

venv\Scripts\activate

Linux/Mac

source venv/bin/activate
4. Install Dependencies
pip install -r requirements.txt
5. Configure API Key

Create a .env file:

YOUTUBE_API_KEY=YOUR_API_KEY
▶️ Running the Application
streamlit run app.py

The application will open in your browser:

http://localhost:8501
📊 Key Performance Metrics
Engagement Rate
Engagement Rate =
(Total Likes + Total Comments) / Total Views × 100

Measures how actively viewers interact with the content.

Average Views Per Video
Average Views Per Video =
Total Channel Views / Total Uploaded Videos

Measures average video reach.

Subscriber-to-View Ratio
Subscriber-to-View Ratio =
Subscribers / Total Views

Indicates the relationship between audience size and total reach.

Upload Frequency
Upload Frequency =
Total Videos / Channel Age

Measures content publishing consistency.

📈 Dashboard Outputs
Channel Overview Dashboard
Engagement Analysis Dashboard
Performance Trend Analysis
Top Videos Analysis
Channel Comparison Reports
AI Growth Recommendation Reports
🔒 Future Enhancements
Real-time Analytics
Sentiment Analysis of Comments
YouTube Shorts Analytics
Revenue Estimation
Predictive Growth Modeling
Export Reports to PDF
Multi-language Support
=======
# Project-Phase-II_Internship2025-26
Students should include the following documents and materials during project submission: source code, README file, requirements.txt file, project poster, published research paper, copyright documents, course completion certificates, and the final project report in PDF format.
