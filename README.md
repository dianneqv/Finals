# 👨‍💻 Final Assessment — Machine Learning Model

## ℹ️ 1. Pair Information
- ✍️ **Pair Name**: Navigators
- 👥 **Members**: Jhun Kenji Jusay and Dianne Mae Vinegas
- 🤖 **Topic**: Robot Navigation in Dynamic 3D Environments
- ✅ **Chosen Model**: Logistic Regression

## 📰 2. Dataset Overview

- **Dataset Source**: https://www.kaggle.com/datasets/ziya07/robot-navigation-in-dynamic-3d-environments 
- **Description**: This dataset evaluates the performance of pathfinding algorithms in robot navigation tasks across varying levels of environmental complexity and obstacle density. It contains simulated data for robot navigation in dynamic 3D environments, intended for studying path planning and obstacle avoidance.
- **Target Variable**: Pathfinding Success
- **Features Used**:
- Start Position (X, Y, Z)
- Destination Position (X, Y, Z)
- Static Object Count
- Dynamic Object Count
- Obstacle Position (X, Y, Z)
- Obstacle Velocity (X, Y, Z)
- Path Length (m)
- Obstacle Height (m)
- Obstacle Width (m)
- Obstacle Depth (m)
- Energy Efficiency (%)
- Collision Avoidance (%)
- Computation Time (ms)
- Pathfinding Algorithm_ABC
- Pathfinding Algorithm_MABC

## 📃 3. Preprocessing Summary
- **Encoding**: All categorical variables were converted into numerical values to make them compatible with the machine learning model.
- **Scaling**: Numerical features were scaled to a common range to prevent any single feature from dominating the model.
- **Cleaning steps**:
- **Train–test split**:

## 📊 4. Model & Results
- **Model used**: Logistic Regression
  - **Metrics**:
  -  **Accuracy** =
  -  **Precision** =
  -  **Recall** =
  -  **F1-Score** =
  <p align="center">

- **Visualizations**:
- **Insights**: (3–5)

## ▶️ 5. How to Run
1. Install VS Code + Python + Jupyter Extension
2. Install dependencies:

pip install -r requirements.txt

3. Open the `.ipynb` notebook
4. Run all cells
