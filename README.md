Earthquake Early Warning & Risk Prediction System

A real-time machine learning pipeline that fetches live seismic data from the USGS API to analyze, visualize, and predict earthquake risk levels globally, with a special focus on Bangladesh.


Features
- Live Data Fetching: Automatically downloads the latest 30-day earthquake data directly from the USGS API.
- Data Cleaning:Handles missing values, removes negative magnitudes, and engineers a new 'Risk Level' feature (Safe to Extreme Danger).
- Interactive Geospatial Visualization:Beautiful, interactive global and regional maps using Plotly Express to identify seismic hotspots.
-Machine Learning Prediction: Trains and compares Gaussian Naive Bayes and Support Vector Machine (SVM) models to classify earthquake risk based on latitude, longitude, depth, and magnitude.
- Regional Focus: Includes a dedicated risk assessment module and map for Bangladesh and surrounding regions.

Technologies & Libraries Used
- Language: Python
- Data Manipulation:pandas,numpy
- Machine Learning:scikit-learn` (GaussianNB, SVC, train_test_split, metrics)
- Visualization:plotly.express` (Interactive Maps),matplotlib`,seaborn` (Confusion Matrix)
- Utilities:urllib`,datetime`,warnings`

##  Dataset
- Source: United States Geological Survey (USGS) Earthquake Hazards Program.
- Update Frequency: Real-time (Last 30 days summary).
- Link: [USGS All Month Earthquake Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.csv)

## 💻 How to Run
1. Clone this repository:
  ``bash
   git clone https://github.com/mahinmahmud123/Earthquake-Early-Warning-System-for-Bangladesh.git
