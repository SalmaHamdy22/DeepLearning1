
# Price Prediction Using Artificial Neural Networks (ANN) in PyTorch

The objective of this task aims to make an analysis that explains the relationship between Area and Prices using a Linear regression model implemented with a neural network. The goal is to achieve a model with R2 score greater than or equal 0.75.



## Dataset description
The dataset contains 13 features.

The feature to be predicted is the price.

The dataset is processed by checking for nulls and being normalized using StandardScaler.

Then being used to train a NN model model for Linear regression.
## Steps to Run the Code in Jupyter Notebook
Open Anaconda:

-> You can upload this code directly to a Jypyter notebook .

Upload or Load the Dataset:

-> Upload the dataset using the file upload functionality (Files tab).

Run the Code:

-> Once the dataset is uploaded or loaded, execute the code cells sequentially in the Jupyter notebook.

The code will handle preprocessing, model training, evaluation, and visualization.
## Dependencies and Installation Instructions
bash

!!pip install torch torchvision numpy pandas matplotlib scikit-learn

## Example Output
After running the code, you will see the model's performance in terms of evaluation metrics (MSE, MAE, R²), along with a plot showing the predicted prices compared to the actual prices in the dataset. The goal is for the predicted prices to closely match the actual prices, and for the model's R-squared score to be greater than 0.75.