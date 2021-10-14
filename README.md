# flight-price-prediction
SDAIA Bootcamp project 2 - web scraping/linear regression.

This project aims to predict ticket prices for upcoming flights to help customers in selecting the optimum time for travel and the cheapest flight to the desired destination. A random forest regression model is applied to forecast the flight prices based on data scraped from Kayak.

## Table of Contents

- [Proposal](#proposal)
- [MVP](#mvp)
- [Scraping](#scraper)
- [Analysis and Results](#project)
- [Presentation](#presentation)

## Project Proposal <a name="proposal" />
#### The project proposal can be found [here](https://github.com/MeshalAlamr/web-scraping-regression/blob/main/proposal/README.md).


## Project MVP <a name="mvp" />
#### The project MVP can be found [here](https://github.com/MeshalAlamr/web-scraping-regression/tree/main/MVP).

## Scraping <a name="scraper" />
#### The Kayak Scraper Notebook can be found [here](https://github.com/MeshalAlamr/flight-price-prediction/blob/main/kayak-scraper.ipynb).
#### The scraped data can be found [here](https://github.com/MeshalAlamr/flight-price-prediction/tree/main/data).

![image](https://user-images.githubusercontent.com/68873733/137396148-c6b1ae8f-eb64-408a-8606-469eda33bd9a.png)

##### In total, the data consists of 55,363 rows and 7 columns.


## Analysis and Results <a name="project" />

#### The project notebook can be [here](https://github.com/MeshalAlamr/flight-price-prediction/blob/main/flight-price-prediction.ipynb).

#### Selected features are:
- Source (4 Sources were selected for this project)
- Destination (4 Destinations were selected for this project)
- Total Stops
- Average Price per Airline
- Duration
- Price (Target)

#### Correlation of features:

![image](https://user-images.githubusercontent.com/68873733/137396490-c72e4f89-441e-430a-b4a9-831081ff6375.png)

#### Experiments:
![image](https://user-images.githubusercontent.com/68873733/137396989-02b3f69b-d336-4600-b436-420e68069fb6.png)

#### The final selected model is the random forest regression model with:
| Metric | Score |
|:---:|:---:|
| MAE | 61.87 |
| MSE | 40409.87  |
| RMSE | 201.02 |

#### Therefore, the final model is able to predict flight ticket prices within around  ≈ $61.87

## Presentation <a name="presentation" />
#### The presentation can be found [here](https://github.com/MeshalAlamr/flight-price-prediction/blob/main/final-presentation.pdf).
