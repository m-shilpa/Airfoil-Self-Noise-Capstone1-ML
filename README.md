# Airfoil Self-Noise Prediction

# Dataset
The data consists of 1,503 instances, each with 6 attributes obtained from a series of aerodynamic and acoustic tests of two and
three-dimensional airfoil blade sections conducted in an anechoic wind tunnel. More details about the dataset can be found at the 
University of California, Irvine at UCI Machine Learning Repository Data Set page 
[http://archive.ics.uci.edu/ml/datasets/Airfoil+Self-Noise](http://archive.ics.uci.edu/ml/datasets/Airfoil+Self-Noise).

# Install
This project requires python 3.6 or anyother higher versions of python, along with these libraries
•	NumPy
•	Pandas
•	matplotlib
•	scikit-learn
•	seaborn
You also need a software to run this python notebook "Jupyter Notebook". It is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

# Feature Description
This problem has the following inputs: 
1. Frequency, in Hertzs. 
2. Angle of attack, in degrees. 
3. Chord length, in meters. 
4. Free-stream velocity, in meters per second. 
5. Suction side displacement thickness, in meters. 

# Desired Target
Scaled sound pressure level, in decibels. 

# Models Trained On
| Algorithm | RMSE |
| --- | --- |
| Linear Regression(raw code) | 0.09 |
| Linear Regression(Sklearn) | 0.01 |
