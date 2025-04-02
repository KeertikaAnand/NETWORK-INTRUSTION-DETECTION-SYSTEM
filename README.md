# Network Intrusion Detection System (NIDS)

This repository contains the code and resources for a machine learning-based Network Intrusion Detection System (NIDS). The system is designed to detect and classify network attacks using various machine learning models and provides interactive tools for analysis and monitoring.

## Table of Contents

-   Project Overview
-   Features
-   Installation
-   Usage
-   Dataset
-   Models
-   Visualizations
-   Contributing
-   License

## Project Overview

The goal of this project is to develop a robust NIDS that can accurately detect and classify network intrusions. It utilizes machine learning algorithms to analyze network traffic data and identify malicious patterns. The system includes an interactive user interface, real-time monitoring simulation, and model explainability tools.

## Features

-   Data Preprocessing: Handles categorical and numerical features, including scaling and encoding.
-   Model Training and Evaluation: Trains and evaluates multiple machine learning models (RandomForest, XGBoost, etc.).
-   Interactive Prediction Interface: Allows users to input network traffic features and receive real-time predictions.
-   Real-time Monitoring Simulation: Simulates network traffic and provides alerts for detected attacks.
-   Model Explainability (SHAP): Explains model predictions using SHAP values.
-   Comprehensive Dashboard: Visualizes model performance, feature importance, and attack distributions.
-   Network Traffic Visualization: Visualizes traffic flow as a network graph.
-   Attack Category Classification: Classifies the type of attack, if available in the dataset.

## Installation

1.  Clone the repository:

    ```bash
    git clone [https://github.com/your-username/network-intrusion-detection-system.git](https://www.google.com/search?q=https://github.com/your-username/network-intrusion-detection-system.git)
    cd network-intrusion-detection-system
    ```

2.  Create a virtual environment (recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    venv\Scripts\activate  # On Windows
    ```

3.  Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4.  Google Drive (if using Google Colab):
    If running this project in Google Colab, you will need to mount your Google Drive and set the `drive_path` variable.

## Usage

1.  Run the Jupyter Notebook:

    ```bash
    jupyter notebook NIDS.ipynb
    ```

2.  Follow the notebook instructions:

    -   The notebook contains cells for data loading, preprocessing, model training, and visualization.
    -   Execute the cells in order to build and use the NIDS.
    -   Use the interactive widgets and visualizations to analyze the results.

3.  Main Functions:

    -   `create_dashboard()`: Displays a comprehensive dashboard.
    -   `create_traffic_visualization()`: Visualizes network traffic as a graph.
    -   `explain_model_with_shap()`: Explains model predictions using SHAP.
    -   `create_prediction_ui()`: Displays the prediction interface.
    -   `create_monitoring_ui()`: Displays the monitoring simulation.

## Dataset

The project uses a network traffic dataset (e.g., UNSW-NB15 or similar). Ensure that the dataset is available in the specified location or modify the data loading cells in the notebook.

## Models

The project evaluates and uses various machine learning models, including:

-   RandomForest
-   XGBoost
-   Support Vector Machines (SVM)

The best-performing model is selected based on metrics like accuracy, F1-score, and ROC AUC.

## Visualizations

The project includes various visualizations:

-   Model performance comparison charts.
-   Feature importance plots.
-   Feature correlation heatmaps.
-   Attack category distributions.
-   Network traffic graphs.
-   SHAP summary plots and force plots.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to improve the project.

## License

This project is licensed under the [MIT License](LICENSE).
