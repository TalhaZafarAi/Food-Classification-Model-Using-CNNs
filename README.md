### Food Classification Using CNNs

This project aimed to create an efficient food classification model using Convolutional Neural Networks (CNNs). By leveraging the Food-101 dataset, the project focused on classifying images into one of ten randomly selected food categories. The process involved data exploration, baseline model creation, hyperparameter tuning, and model evaluation to optimize classification accuracy. The project also included visualizing the model’s performance and deploying it to make predictions on new images.

Dataset Link is Given Below:
https://www.kaggle.com/datasets/dansbecker/food-101/data

### Getting the Environment Ready

To start, the necessary libraries were installed, including PyForest for lazy imports and Keras Tuner for hyperparameter optimization. TensorFlow and Keras were utilized for building and training the CNN model.

### Data Exploration

#### Selecting Classes

We selected 10 random classes from the Food-101 dataset, which consists of 101 food categories. The selected classes served as the target labels for the classification task.

#### Data Visualization

We visualized the dataset by displaying a random image from each of the selected classes, providing an overview of the data.

### Baseline CNN Model

#### Model Architecture

A baseline CNN model was created with several layers, including convolutional, pooling, and dense layers, designed to capture the features of the food images.

#### Model Training

The model was trained using data augmentation techniques to increase the dataset’s diversity and robustness. Early stopping was implemented to prevent overfitting.

### Model Evaluation

The baseline model's performance was evaluated on the validation set. The evaluation metrics, including loss and accuracy, were visualized for better understanding.


### Training History Visualization

The training and validation loss, along with accuracy, were plotted to visualize the model's performance over the epochs.

### Hyperparameter Tuning with Keras Tuner

#### Model Building Function

Keras Tuner was employed to search for the optimal hyperparameters, enhancing the model’s performance.

#### Hyperparameter Search and Best Model Training

The search for the best hyperparameters was conducted using the Hyperband algorithm. The best model was then trained and evaluated.

### Model Deployment and Prediction

The best-performing model was deployed to make predictions on new images, demonstrating its practical application.

### Conclusion

The project successfully developed a CNN model for classifying food images into 10 categories. Starting with data exploration, a baseline model was built and trained, followed by hyperparameter tuning to optimize performance. The final model demonstrated strong accuracy and was capable of predicting the class of new food images effectively.
