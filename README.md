# Crop Recommendation System Using Machine Learning 🌱

A Flask web application that predicts the most suitable crop based on soil and environmental parameters using a Random Forest algorithm.

## Demo Screenshot
![Crop Recommendation System Interface]
*Interactive web interface for crop recommendation based on environmental parameters*

## Overview
This project provides a simple, user-friendly interface for farmers and agricultural experts to get crop recommendations based on:
- Nitrogen content
- Phosphorus content
- Potassium content
- Temperature
- Humidity
- pH value
- Rainfall

## Key Features
- **Intuitive Interface**: Clean and user-friendly design for easy parameter input
- **Real-time Predictions**: Instant crop recommendations using machine learning
- **High Accuracy**: Achieved 99.54% accuracy using Random Forest algorithm
- **Environmental Parameters**: Comprehensive analysis of soil and climate conditions

## Model Performance
We evaluated several machine learning models and achieved the following accuracy scores:

| Model | Accuracy |
|------------------------|-----------------| 
| Logistic Regression | 96.06% |
| Naive Bayes | 99.39% |
| SVC | 98.33% |
| KNN | 97.57% |
| Decision Tree | 98.03% |
| Random Forest | **99.54%** |
| Bagging | 98.94% |
| AdaBoost | 21.21% |

The Random Forest model was selected for its superior accuracy of 99.54%.

## Technologies Used
- Flask
- Python 3.x
- HTML/CSS
- Random Forest Classifier
- scikit-learn

## Setup & Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/crop-recommendation.git


# Run the application
python app.py
```


## Usage
1. Start the Flask server:
   ```bash
   python app.py
   ```
2. Open web browser and go to `http://localhost:5000`
3. Enter the required soil and environmental parameters:
   - Nitrogen (N): 0-140
   - Phosphorus (P): 5-145
   - Potassium (K): 5-205
   - Temperature: 8.83°C-43.68°C
   - Humidity: 14.26%-99.98%
   - pH: 3.5-9.94
   - Rainfall: 20.21mm-298.56mm
4. Click "Get Recommendation" to receive crop suggestion

## Requirements
```
Flask==2.0.1
numpy==1.21.2
pandas==1.3.3
scikit-learn==0.24.2
```

