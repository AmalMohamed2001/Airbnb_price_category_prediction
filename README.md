# Airbnb_price_category_prediction
multi-modality solution
#**Problem Definition**
Problem here is about building a model to classify the price and type.

**Input:** summary and image (7627) for a training dataset.

**Output:** price and type (7627) .

**Data mining function**
- load the data from the source.
- preprocess and manipulating the data.
- build and train the model.
- classification and prediction.

**Impact**
It will help hosts to put the true and suitable price for their residence place and that will increase their sales, also it will help guests to predict the night price for the place that they are looking for it to stay in it at holidays or in the work trip days.

**Challengs:**
Null values in summary feature in training dataset.
summary feature in both training dataset and test dataset is multilingual.
imbalanced labels distribution.
multi-prediction problem.
huge time in training and prediction.

**The ideal solution**
using the embedding layer for text data with conv2d layer and maxpooling layer for the image data that gote the highest score on kaggle (68.206%).
