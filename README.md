# WhentobullAI
<img src="images/chartscan.png" alt="WhentobullAI Logo" width="200"/>


## Overview
WhentobullAI is an advanced application designed for detecting patterns in stock and cryptocurrency charts using deep learning techniques. This project extends their approach by implementing the model with YOLOv8 and integrating it into a user-friendly Streamlit app. This application aims to automate the process of chart pattern recognition, providing traders and analysts with a powerful tool for making informed decisions.

## About
WhentobullAI leverages the power of YOLOv8, a state-of-the-art object detection algorithm, to identify and classify patterns in financial charts. The model provides outputs in two classes: Buy and Sell, based on candlestick patterns. This application provides a robust solution for traders and analysts to quickly recognize significant chart formations, aiding in more informed decision-making.

![Output Chart](images/out3.jpg)

## Problem Statement
In the financial market, timely and accurate identification of chart patterns is crucial for making profitable trading decisions. Manual detection is not only time-consuming but also prone to human error. There is a need for an automated system that can analyze charts in real-time, identify patterns with high accuracy, and present the results in an accessible format.

## Data Collection and Data Annotation
The dataset for this project was meticulously curated from various financial sources, ensuring a diverse range of chart patterns. The data collection process involved:
1. **Downloading Charts**: Using the `yfinance` library to download stock and cryptocurrency data.
2. **Plotting Charts**: Generating candlestick plots with `mplfinance`.
3. **Annotation**: Annotating the charts using `Roboflow` to create a comprehensive training dataset.

![Sample Chart](images/AAPL_latest_180_candles.png)

Using `Roboflow`, various chart patterns were labeled, enabling the YOLOv8 model to learn and detect these patterns with high accuracy. The annotated dataset serves as the foundation for training the model, making it capable of recognizing complex patterns in financial charts.

## WhentobullAI App
The WhentobullAI app, built with Streamlit, offers a seamless interface for users to upload charts, analyze them, and view the detected patterns. Key features include:
- **User-Friendly Interface**: Intuitive design for easy navigation and use.
- **Real-Time Analysis**: Upload a chart and get instant results.
- **High Accuracy**: Powered by the YOLOv8 model, ensuring reliable pattern detection.
- **Versatile**: Supports both stock and cryptocurrency charts.

![WhentobullAI App](images/app.png)


