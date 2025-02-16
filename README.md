## Capital Bikeshare Machine Learning Project
### Overview
This project focuses on analyzing and predicting bike availability at the 22nd & H St NW Capital Bikeshare station in Washington, D.C. The goal is to predict whether the number of pickups (PU_ct) exceeds the number of dropoffs (DO_ct) at any given time using machine learning models. The project includes data preprocessing, exploratory analysis, feature engineering, and the evaluation of several classification models.

### Dataset
The dataset consists of bike trip data from February to April 2024, including:

Pickups (PU_ct): Number of bikes picked up at the station.

Dropoffs (DO_ct): Number of bikes dropped off at the station.

Weather features: (Optional, if available) Temperature, precipitation, etc.

Temporal features: Hour, day of the week, weekend indicator.

The dataset is preprocessed to handle missing values, encode categorical variables, and create new features.

### Tasks Overview
1. Train a KNN classifier model with 𝑘=5 and report training & test accuracy.
2. Plot training & test accuracy of the KNN model against 𝑘 values i.e n_neighbours from 1 to 15.
3. Identify the optimal n_neighbours from the plot and report test accuracy.
4. Train a logistic regression model and report training & test accuracy.
5. Train a linear SVC model (C=10), and report the training and test accuracy. 
6. Train a nonlinear SVC model with RBF kernel (C=10), and report the training and test accuracy.
7. Plot decision tree accuracy vs. max depth from 1 to 15.
8. Report best perfoming model.

### Code Structure
The project is organized as follows:

Notebook: The main Jupyter Notebook (Capital_Bikeshare_ML.ipynb) contains all the code, analysis, and visualizations.

### Data:
This project continues with 
  - Bike Data is obtained from Capital Bikeshare data from https://ride.capitalbikeshare.com/system-data for three months: 2024/02, 2024/03 and 2024/04.
  - Weather data is obtained from https://www.visualcrossing.com/weather-history/

### Libraries used:
pandas 
numpy 
scikit-learn 
seaborn 
matplotlib

### Dependencies
Python 3.x
google colab
genAI also used to generate codes

### Future Work
- Incorporate additional features (e.g., weather data, holidays) to improve model performance.
- Experiment with other machine learning algorithms (e.g., Random Forest, Gradient Boosting).
- Deploy the best-performing model as a web application for real-time predictions.

### License
This project is licensed under the MIT License. See the LICENSE file for details.
