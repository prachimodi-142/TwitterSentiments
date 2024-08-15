# TwitterSentiments

This repository contains a project aimed at analyzing the sentiment of Twitter data related to stock market trends. The project is built as an iOS application using Swift and leverages CoreML 2 and Create ML for real-time sentiment analysis. It processes live Twitter data to determine whether the general sentiment is positive, negative, or neutral, helping investors make informed decisions.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

In today's fast-paced financial markets, understanding public sentiment is crucial for making informed investment decisions. This project aims to provide a tool for investors to gauge public sentiment on specific stocks by analyzing tweets in real-time. The iOS app captures live Twitter data, processes it, and classifies the sentiment as positive, negative, or neutral using machine learning models.

## Features

- **Real-time Sentiment Analysis**: The app fetches live tweets related to specific stocks and provides an immediate sentiment analysis.
- **User-Friendly Interface**: A simple and intuitive iOS interface that allows users to input stock symbols and view sentiment trends.
- **Machine Learning Integration**: Utilizes CoreML 2 and Create ML to train and deploy custom sentiment analysis models.

## Technologies Used

- **Swift**: For building the iOS application.
- **CoreML 2**: To deploy machine learning models on the device.
- **Create ML**: For training the sentiment analysis model.
- **Twitter API**: To fetch live tweets related to specific stocks.

## Project Structure

- `Model/`: Contains the machine learning models and related files.
- `Views/`: Holds the UI components and layouts for the app.
- `Controllers/`: Contains the logic that connects the views with the models.
- `Utilities/`: Includes helper functions and utilities used across the app.
- `Tests/`: Unit tests for validating the functionality of the app.
- `Docs/`: Documentation related to the project.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/prachimodi-142/TwitterSentiments.git
   ```
2. **Open the project in Xcode**:
   ```bash
   cd TwitterSentiments
   open TwitterSentiments.xcodeproj
   ```
3. **Install dependencies**:
   - Ensure you have a valid Twitter API key to fetch live tweets.
   - Integrate your CoreML models within the project.

4. **Build and Run the Project**:
   - Select your target device or simulator and hit the 'Run' button in Xcode.

## Usage

1. Open the app on your iOS device.
2. Enter a stock symbol or related keyword to analyze.
3. View the sentiment analysis in real-time, displayed as positive, negative, or neutral.
