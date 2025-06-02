# 🚀 AI-Driven Stock Selection and Portfolio Optimization

This project is an AI-powered stock selection and portfolio optimization system built using Python and Flask. It predicts stock prices, evaluates investment risks, and provides portfolio recommendations based on fundamental and historical data.

## Features

- 📈 Stock price prediction for the next 2 years using AI models
- ⚖️ Risk-to-reward ratio calculation
- ⚠️ Warnings for small-cap stocks, high P/E ratios, and declining sales growth
- 🏆 Comparison of stock performance with gold over the past 10 years
- 🌐 Interactive web interface built with Flask
- 📊 Visualizations including predicted price graphs, past performance charts, and EMA overlays

## Project Structure

├── app.py # Flask application

├── main.py # AI model training and prediction logic

├── fundamentals.pkl # Pickled fundamental data

├── models.pkl # Pickled trained AI models

├── static/ # Static files (CSS, images)

│ ├── css/

│ └── images/

└── templates/ # HTML templates

└── home.html
