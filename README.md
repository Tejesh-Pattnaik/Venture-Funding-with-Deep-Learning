### Deep Learning in Venture Funding

## Required Packages
To set up the necessary environment, execute the command: pip install x, where x corresponds to the following packages:

* pandas
* pathlib
* tensorflow
* scikit-learn

## Objective
The aim was to develop a predictive model for assessing the likelihood of success for organizations receiving funding from Alphabet Soup. Leveraging machine learning and neural networks, a binary classifier was constructed using features from the provided dataset. This model predicts whether an applicant will evolve into a successful business.

## Analysis Breakdown
*Data Preparation for Neural Network Model:
Organizing the dataset for effective utilization in a neural network.

* Compilation and Evaluation of Binary Classification Model:
Building and assessing a binary classification model using a neural network.

* Optimization of Neural Network Model:
Fine-tuning the neural network model for improved performance.

## File Structure
Resources: Directory housing essential CSV files and models.
venture_funding_with_deep_learning.ipynb: Notebook encompassing all data analysis and prediction activities.
Results

## Original Model:

First Hidden Layer: 58 nodes (half of total features)
Second Hidden Layer: 29 nodes
Accuracy Score: 73.03%


## Alternative Model 1:

First Hidden Layer: 232 nodes (double the total features)
Accuracy Score: 72.89%


## Alternative Model 2:

First Hidden Layer: 348 nodes (triple the total features)
Accuracy Score: 72.94%

### The observed differences in results among the three models appear marginal. Notwithstanding, the orignal model exhibited the highest accuracy at 73.03%.
