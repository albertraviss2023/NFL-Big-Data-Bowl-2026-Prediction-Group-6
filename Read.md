# NFL Big Data Bowl 2026: Prediction Competition

## 🏈 Overview
Note: The Big Data Bowl 2026 features two competitions. This repository focuses on the **Prediction Competition**. For details on the Analytics Competition, visit the official Kaggle page.

The downfield pass is the crown jewel of American sports. When the ball is in the air, anything can happen—touchdowns, interceptions, or contested catches. This uncertainty keeps fans on the edge of their seats.

The 2026 Big Data Bowl aims to enhance the NFL's understanding of player movement during pass plays, from the moment the ball is thrown until it's caught or ruled incomplete.

- **Offensive focus**: Targeted receiver moving to the landing spot.
- **Defensive focus**: Multiple players preventing catches and contesting the ball.

This year's challenge invites participants to model these movements.

## 🎯 Prediction Task
Predict player trajectories while the ball is in the air using:
- Pre-pass Next Gen Stats tracking data
- Targeted receiver information
- Pass landing location

Models are evaluated on how closely predictions match actual movements.

## 📊 Competition Specifics
- **Tracking Data**: 10 frames per second (e.g., 2.5 seconds in air = 25 frames to predict)
- **Exclusions**: Quick passes (<0.5s), deflected passes, and throwaways are removed
- **Data Split**: 
  - Training: Historical data
  - Leaderboard: Unseen 2025 NFL season data (last 5 weeks)

## 🧮 Evaluation
- Metric: Root Mean Squared Error (RMSE) between predicted and observed x/y positions
- Full details: See Kaggle Evaluation page

## 📤 Submission Format
- Use the provided evaluation API for single-play inference
- Predict x/y for each row in the test dataframe
- Submit via Kaggle Notebooks only

## 🗓️ Timeline (as of November 17, 2025)

### Training Phase
- Sep 25, 2025: Competition launched  
- Nov 26, 2025: Team merger/entry deadline  
- Dec 3, 2025: Final submissions due  
- **Status**: Training phase active. Entry deadline approaching in 9 days.

### Forecasting Phase
- Dec 4, 2025 – Jan 5, 2026: Live leaderboard updates after weekly NFL games  
- Jan 6, 2026: Competition closes; results published

> All times: 11:59 PM UTC. Organizers may adjust timelines.

## 🏆 Prizes

| Place | Amount   |
|-------|----------|
| 1st   | $25,000  |
| 2nd   | $15,000  |
| 3rd   | $10,000  |

## 💻 Code & Submission Requirements
- **Notebook Only**: CPU/GPU ≤ 9 hours runtime  
- **Internet**: Disabled  
- **External Data**: Allowed if free/public (e.g., pre-trained models)

See the Code Competition FAQ and Debugging Guide for help.

## 📁 Repository Structure
- `data/`: Sample datasets (tracking, plays, etc.)
- `notebooks/`: Exploration, modeling, and submission notebooks
- `src/`: Utility scripts for data processing and visualization
- `models/`: Saved model artifacts

## 🚀 Getting Started
```bash
git clone https://github.com/yourusername/nfl-bdb-2026-prediction-group-6.git
pip install -r requirements.txt