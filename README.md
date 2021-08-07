# Human-Activity-Recognition-Using-Neural-Networks
* Classified human activities into one of the 6 categories.
* Data has 10,299 rows.
* Used neural networks for classification.
* Used keras tuner and random search to hypertune the model.

## Languages Used 
**Python Version:** 3.9.0

## Resources and Tools Used
**Tools:** Jupyter Notebook

**Packages:** Pandas, NumPy, sklearn, Matplotlib, TensorFlow, Keras, Seeborn.

## Data Used
* **Data taken from kaggle** : https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones
* The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKINGUPSTAIRS, WALKINGDOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. 
* Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz.
* The experiments have been video-recorded to label the data manually.
* The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

## Data Wrangling and Data Visualization
* Label encoded the target variable.
* Used min max scaling to scale the data.

## Model Building 

Firstly, created a sequential base model. Later on, hypertuned the model to find out how many layers are needed, how many units needed and, which all activation functions 
arer giving the best results.

## Metrics Used For Evaluation
* Accuracy

## Model performance

**Results:**

* Validation Accuracy: 95.83%
