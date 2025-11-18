Here is the content for your README.md file:

DataTales: Student Performance Dashboard
An interactive web dashboard built with Plotly and Dash that explores the correlation between student lifestyle habits (e.g., sleep, social media use, diet) and their academic performance.

This project was created for the ICT305: Data Visualisation and Simulation course at Murdoch University Dubai.

(Note: To make this image appear, take a screenshot of your running dashboard, name the file DASHBOARD_SCREENSHOT.png, and add it to your GitHub repository.)

📖 Table of Contents
Project Overview

Features

Technical Stack

How to Run This Project

Live Demo

Team & Acknowledgments

🎯 Project Overview
In today's academic environment, a student's success is influenced by more than just study hours. This dashboard aims to answer questions like:

How strongly does class attendance predict exam scores?

Is there an "optimal" number of study hours before returns diminish?

What is the impact of social media usage, sleep quality, and part-time work on academic results?

The DataTales dashboard provides an interactive tool for educators, administrators, and students to visually explore these complex relationships and uncover actionable insights.

✨ Features
Multi-Page App: A clean and modern interface with separate pages for Home, Introduction, the Dashboard, and About Us.

Interactive Dashboard: The main dashboard features dynamic filters for:

Gender

Part-time Job Status

Age Range

Dynamic Visualizations: All charts and statistics update instantly based on filter selections.

Multiple Analysis Themes: Graphs are organized into logical tabs:

Academic Factors: Attendance vs. Scores, Study Hour Efficiency.

Lifestyle & Wellbeing: Sleep & Mental Health, Social Media Impact, Diet Quality.

Socioeconomic Factors: Part-Time Work & Internet Quality Analysis.

🛠️ Technical Stack
Dash (by Plotly): The core framework for building the web application.

Dash Bootstrap Components: Used for styling and layout to create a professional, responsive design.

Plotly Express & Graph Objects: The engine for creating all interactive charts and visualizations.

Pandas: Used for all data loading, cleaning, and manipulation.

Gunicorn: The web server used to run the app in production.

🚀 How to Run This Project
To run this dashboard on your local machine, follow these steps:

1. Prerequisites
Make sure you have Python 3.8 or newer installed on your system.

2. Clone the Repository
Bash

git clone https://github.com/wadiqabaig/Dashboard.git
cd Dashboard
(Replace wadiqabaig/Dashboard with your repository URL if it's different.)

3. Install Dependencies
All required libraries are listed in the requirements.txt file.

Bash

pip install -r requirements.txt
4. Run the Application
Bash

python app.py
5. View the Dashboard
Open your web browser and navigate to: http://127.0.0.1:8052/

🌐 Live Demo
This application is deployed and can be viewed live at the following URL:

(Add your Render app link here, for example: https://datatales-dashboard.onrender.com)

👥 Team & Acknowledgments
This project was developed by:

Wadiqa Baig

Areeba Shoaib

Warda Baig

Lidya Tesfay Adal

Hiba Zubairi

Data Source
Dataset: Student Habits vs Academic Performance by Jayaant Nath on Kaggle.
