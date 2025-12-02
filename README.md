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


## 🚀 About the notebooks
```bash
git clone https://github.com/yourusername/nfl-bdb-2026-prediction-group-6.git
- The training notebook (Iteration 5) trains the models and saved them to a kaggle working directory
- Before the session ends, you need to download these models and put them in a zip file
- Now import the submission notebook in kaggle and import the saved models as dataset. Make sure the paths are correct pointing to the models and also that the compatition dataset is added as input.
- Submit and the score shoulc reflect.
