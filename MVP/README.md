## Minimum Viable Product (MVP) of the Web Scraping / Regression Project
One of the goals of this project is to predict flight prices. In order to accomplish this we started off with analyzing a dataset that contains previous flight prices
of India to build a regression model.

Initially, we cleaned the dataset to select relevant features and performed one-hot encoding to prepare the data for the regression model. 

Then we plotted the feature importance to the target variable "Price".

![feature_importance](https://raw.githubusercontent.com/MeshalAlamr/web-scraping-regression/main/MVP/feature_importance.png)

From the figure above, we can see that the total stops and duration of the flight are the most useful in predicting the target variable, the price.

We then built the model and obtained the following results before and after hyperparameter tuning:
|  | MAE | MSE | RMSE |
|:---:|:---:|:---:|:---:|
| Before Hyperparameter Tuning | 1774.21 | 9541811.91 | 3088.98 |
| After Hyperparameter Tuning | 1749.21 | 8508459.31 | 2916.93 |

Currently, we're in the midst of tuning the model to obtain better results as the initial results were not satisfactory.

Additionally, we managed to scrape Kayak to create a dataset of similar features to the original dataset in order to test the regression model.
