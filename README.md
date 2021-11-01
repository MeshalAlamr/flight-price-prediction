# flight-price-prediction
SDAIA Bootcamp project 2 - web scraping/linear regression.

This project aims to predict ticket prices for upcoming flights to help customers in selecting the optimum time for travel and the cheapest flight to the desired destination. A random forest regression model is applied to forecast the flight prices based on data scraped from Kayak.

## Table of Contents

- [Proposal](#proposal)
- [MVP](#mvp)
- [Scraping](#scraper)
- [Analysis and Results](#project)
- [Presentation](#presentation)
- [Mobile App](#app)
- [Authors](#authors)

## Project Proposal <a name="proposal" />
#### The project proposal can be found [here](https://github.com/MeshalAlamr/web-scraping-regression/blob/main/proposal/README.md).


## Project MVP <a name="mvp" />
#### The project MVP can be found [here](https://github.com/MeshalAlamr/web-scraping-regression/tree/main/MVP).

## Scraping <a name="scraper" />
#### The Kayak Scraper Notebook can be found [here](https://github.com/MeshalAlamr/flight-price-prediction/blob/main/kayak-scraper.ipynb).

#### Here's a demo of the scraper in action (played at 2x speed):
![scraper (1)](https://user-images.githubusercontent.com/68873733/137405620-e8af4863-4359-4799-b518-7f1605ceb2a2.gif)

#### The scraped data can be found [here](https://github.com/MeshalAlamr/flight-price-prediction/tree/main/data).

![image](https://user-images.githubusercontent.com/68873733/137396148-c6b1ae8f-eb64-408a-8606-469eda33bd9a.png)

#### In total, the data consists of 55,363 rows and 7 columns.


## Analysis and Results <a name="project" />

#### The project notebook can be found [here](https://github.com/MeshalAlamr/flight-price-prediction/blob/main/flight-price-prediction.ipynb).

#### Selected features are:
- Source (4 Sources were selected for this project)
- Destination (4 Destinations were selected for this project)
- Total Stops
- Average Price per Airline
- Duration
- Price (Target)

#### Correlation of features:

![image](https://user-images.githubusercontent.com/68873733/137396490-c72e4f89-441e-430a-b4a9-831081ff6375.png)

#### Experimenting with different models:
![image](https://user-images.githubusercontent.com/68873733/137396989-02b3f69b-d336-4600-b436-420e68069fb6.png)

#### The final selected model is the random forest regression model with:
| Metric | Score |
|:---:|:---:|
| MAE | 61.87 |
| MSE | 40409.87  |
| RMSE | 201.02 |

#### Therefore, the final model is able to predict flight ticket prices within around  ≈ $61.87.

#### The final model can be found [here](https://github.com/MeshalAlamr/flight-price-prediction/tree/main/model).

![image](https://user-images.githubusercontent.com/68873733/137399435-4e2da145-512b-4df6-80e3-809e603b1727.png)

## Presentation <a name="presentation" />
#### The presentation can be found [here](https://github.com/MeshalAlamr/flight-price-prediction/blob/main/final-presentation.pdf).

## Mobile App <a name="app" />
#### We've also developed an app on Android that finds the average estimated prices for a selected route and month based on our scraped data.
![image](https://user-images.githubusercontent.com/68873733/137400084-6a63edf3-5c63-4c18-9974-f46e827a8b14.png) 
![image](https://user-images.githubusercontent.com/68873733/137400440-bb827740-6460-4412-ace1-1478f53e98ea.png)

#### Below, a demo of the mobile app is shown:
![flight-pred-app](https://user-images.githubusercontent.com/68873733/137401604-e7118c1c-fd79-4b0d-ac4d-91b019eeb31f.gif)

## Authors <a name="authors"/>
- ### [Meshal Alamr](https://github.com/MeshalAlamr)
- ### [Norah Alkhalifah](https://github.com/NorahAlkhalifah)

